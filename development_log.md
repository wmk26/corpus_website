### 2016.4.25

wmk:
- 搭建本地开发环境:
	- 创建项目;
	- 设置mysql数据库, corpus_website/setting.py,其他机器测试需要修改mysql的用户名和密码
	- 上传github,用于多人协作
- 创建后台管理用户,www:www
- 后台页面汉化
	- corpus_website/setting.py中修改LANGUAGE_CODE = 'zh-CN'
	- 参考链接:[django管理后台中文支持](http://eggache.me/2015/03/22/django%E7%AE%A1%E7%90%86%E5%90%8E%E5%8F%B0%E4%B8%AD%E6%96%87%E6%94%AF%E6%8C%81/)
- 用bootstrap美化后台管理页面
	- 参考:[Admin简介](https://andrew-liu.gitbooks.io/django-blog/content/admin.html)