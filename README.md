# MIGRATION STEPS - EN

1. Setup LAMP environment
   * Apache 2.2+
   * PHP 5.2+ (5.6+ recommended)
   * MySQL 5.0+ (5.6+ recommended)
2. Upload the provided Wordpress package (everything under `/wordpress/` folder) via FTP
3. Setup database for Wordpress
   * IF you want fresh installation: create a database & login using phpMyAdmin
   * IF you want existing setup: import SQL zip file with phpMyAdmin *(ziyoucaishi.sql.zip)*
4. Setup Wordpress using its wizard via `http://www.yourhostname.com/yourdirectory/wordpress`
   1. Leave all Wordpress settings to default
   2. Update `Wordpress/wp-config.php` file to use your own database settings
5. Login to Wordpress admin interface with `http://www.yourhostname.com/yourdirectory/wordpress/wp-admin`
6. Go to *"Appearance -> Theme -> Add New"*
7. Search & install theme **Zerif-Lite**

## IF you are using existing setup (imported SQL)
1. Upload all uploaded media pictures to `/wp-content/uploads/2016/03` if they are not there
2. You will have to go into *"Appearance -> Customize"* & update the location of images used on the site

**OPTIONAL:** Install plugin *WP REST API* [Documentation](http://v2.wp-api.org/)

----

# 设置步骤-中文

1. 配置LAMP/WAMP环境
   * Apache 2.2+
   * PHP 5.2+ (建议 5.6+)
   * MySQL 5.0+ (建议 5.6+)
2. 通过FTP把Wordpress package (`/wordpress/`文件夹下所有内容) 上传至服务器
3. 建立并设置Wordpress database
   * 如果从新安装的话用 phpMyAdmin 来建立一个新的 Wordpress database
   * 如果使用现有设置的话用 phpMyAdmin 导入SQL ZIP文件 *(ziyoucaishi.sql.zip)*
4. 通过 `http://www.yourhostname.com/yourdirectory/wordpress` 来安装 Wordpress
   1. 用缺省Wordpress设置
   2. 修改 `Wordpress/wp-config.php` 文件里的有关database设置的信息
5. 登录Wordpress管理员界面 `http://www.yourhostname.com/yourdirectory/wordpress/wp-admin`
6. 到 *"Appearance -> Theme -> Add New"*
   * 如果希望使用中文界面，可以在 *"Settings -> General -> Site Language"* 下设置
7. 搜寻一个叫 **Zerif-Lite** 的Theme并安装

## 如果你选择使用现有设置 (导入了SQL)
1. 确认 `/wp-content/uploads/2016/03` 文件夹里有图片
2. 到 *"Appearance -> Customize"* 下从新设置各个图片
 
**OPTIONAL:** 安装插件 *WP REST API* [Documentation](http://v2.wp-api.org/)