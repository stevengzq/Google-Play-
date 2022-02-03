# Google Play 应用评论爬虫
1.技术路线：基于python语言下的selenium和re模块实现

2.爬取信息：用户昵称、发表日期、完整评论、用户评分、点赞数量
![image](https://user-images.githubusercontent.com/74779928/152338407-9b10eda4-a034-4b38-9f00-3276f72f6d22.png)

3.功能特性：输入相应应用评论页面URL即可进行多次下拉爬取，每进行网页一次评论加载完成一次内容爬取（40条），解决了Google PLay网页加载评论总数限制问题（下拉网页加载到一定数量的评论后会从第41条评论开始重新加载新的评论）
