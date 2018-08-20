# 小游戏项目结构简介

## 根目录下 
index.html 为主页  
games文件夹为各个小游戏  
webroot文件夹下存放各种公用的静态资源（css,js,image,font  

## games文件夹下
每个游戏单独建立一个文件夹，并将所有需要的静态资源（不包括一些jquery.min.js之类的通用资源）放置其中  

## webroot文件夹下
包含五个文件夹：css,js,imgs,fonts,index  
其中css,js,imgs,fonts为各种公用资源  
index 文件夹提供主页所需静态资源  

## 开发环境
需要在本地起一个前端的服务  
推荐vscode+LiveServer  