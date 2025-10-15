# 果汁音乐
一个基于Spring Boot和Bootstrap的音乐网站。

## 功能特性
组织架构：层次结构，包括表现层、业务逻辑层和数据层
1、表现层
（1）首页：轮播图、歌曲推荐、榜单推荐、系统介绍、播放器
（2）歌单推荐：热门推荐、个性推荐
（3）榜单：热门榜、流行榜
（4）歌手推荐:按首字母分类以及按地区（华语、欧美、日韩、其他）分类
（5）登录：分为用户和系统管理员登录
（6）注册：输入账号、用户名和密码注册
（7）播放器：歌曲封面、歌曲简介（专辑、歌手）、歌词跟随播放、底部播放器
（8）个人用户主页：个人信息（昵称、账号、签名）、我喜欢的音乐、我创建的歌单、我收藏的歌单、修改个人信息
（9）后台管理页面：数据统计、用户管理、歌手管理、歌单管理以及管理员身份管理
2.业务逻辑层
主要依靠后台管理员和系统数据库，后台管理员负责管理用户、歌手、歌单以及管理员身份，数据库辅助后台管理员进行数据统计，并且存储一系列信息（歌手、歌曲、歌单、用户信息等）
3.数据层： 
（1）关于排行榜的：分别按照热度和流行程度分为热门榜和流行榜，再根据热度分别对歌曲和歌单排榜
（2）关于推荐内容：在每个歌手/歌曲/歌单下设置类型标签，统计用户浏览次数，进行大数据推送
（3）关于用户信息：由系统数据库存储，由后台管理员管理
（4）关于歌曲信息：由系统数据库存储，由后台管理员管理
（5）关于歌手信息：由系统数据库存储，由后台管理员管理

## 技术栈
前端：Bootstrap
后端：Spring Boot
数据库：MySql

## 安装与运行

……待定……

## 截图
（1）首页个性推荐
<img width="887" height="744" alt="image" src="https://github.com/user-attachments/assets/074b66f7-00fa-4c6c-ac65-921c5cd520c0" />
（2）歌单/歌手推荐
<img width="1036" height="678" alt="image" src="https://github.com/user-attachments/assets/efc8f6cb-4f7e-40e5-98fc-85e2d00fffe2" />
<img width="1036" height="654" alt="image" src="https://github.com/user-attachments/assets/cf1005d3-b2b8-4a0b-bbba-77608ef2d42c" />

（3）榜单
<img width="1036" height="602" alt="image" src="https://github.com/user-attachments/assets/eef3dbef-c2b2-4ec0-90bc-6755e13a9107" />

（4）歌曲播放（列表可切换歌曲）
<img width="1036" height="599" alt="image" src="https://github.com/user-attachments/assets/5e3ed731-b2f8-44b5-ae83-0479262feb22" />

（5）登录/注册
<img width="520" height="303" alt="image" src="https://github.com/user-attachments/assets/c4a0488b-7d64-47ac-b7f2-f7a9e4aa0675" />
<img width="505" height="368" alt="image" src="https://github.com/user-attachments/assets/6f432b48-51e2-4938-a324-1e77b32361a6" />

（6）个人主页
<img width="888" height="518" alt="image" src="https://github.com/user-attachments/assets/2d2a281a-1194-41a4-9231-24a3b2ac2f1a" />
<img width="922" height="530" alt="image" src="https://github.com/user-attachments/assets/1f1eb78d-7eea-4044-b3c3-014b4f1068b1" />

（7）后台管理
<img width="1030" height="548" alt="image" src="https://github.com/user-attachments/assets/f66c3e34-8e0f-489c-81f1-8e266245f057" />
<img width="1032" height="545" alt="image" src="https://github.com/user-attachments/assets/21768bf2-4319-4505-94da-32370c287b69" />
<img width="1032" height="546" alt="image" src="https://github.com/user-attachments/assets/100992aa-cd21-4cd3-ab11-531375eb719e" />
<img width="1031" height="543" alt="image" src="https://github.com/user-attachments/assets/0d28c4ac-7264-4db3-b1ac-482c98eef8a3" />

## 代码目录
<img width="445" height="749" alt="image" src="https://github.com/user-attachments/assets/f671bdd0-c6e6-4b51-bb2d-4d7a96743091" />

