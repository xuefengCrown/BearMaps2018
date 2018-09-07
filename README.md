# BearMaps2018
Berkeley cs61b proj3--BearMaps2018

---

## Intro

Berkeley cs61b proj3: BearMaps（实现一个简单版的Google Maps）；

这是一个web项目，前端已经写好，你只需要写后端的核心代码，基本功能包括：

1. 位图构建（根据经纬度参数来选择图片以构建地图）
2. 解析真实的地图数据（.xml文件），存储为Graph
3. 两点的最短路径

## 准备工作

[项目的详细文档](https://sp18.datastructur.es/materials/proj/proj3/proj3)

[项目的初始代码你可以在这里找到](https://github.com/Berkeley-CS61B/skeleton-sp18)

1. [library-sp18](https://github.com/Berkeley-CS61B/library-sp18)/[data](https://github.com/Berkeley-CS61B/library-sp18/tree/master/data)/**proj3_imgs**/ 

   包含所有构建前端展示地图所需图片

2. [library-sp18](https://github.com/Berkeley-CS61B/library-sp18)/[data](https://github.com/Berkeley-CS61B/library-sp18/tree/master/data)/**berkeley-2018.osm.xml** 

   是真实的地图数据，你需要解析它来构建Graph

## 所需知识

1. QuadTree（四分树）
2. Sax Parser 解析 xml 文件
3. Dijkstra's algorithm
4. A* algorithm

## 我实现的部分

map displaying, zooming in/out, and finding the shortest path between 2 user-inputted points.

## TODO

1. Locations（定位，根据地点名称查询）
2. Autocomplete（查询关键词的自动补全）