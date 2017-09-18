# lingJuan
lingJuan一套可以设置代理的淘客系统

前段时间自己想做淘客，发现市场上的APP都是网站打包的，说打包都过了，就是webview里面放一个h5的网址，恕我直言，很水，于是就萌生了自己写一个的想法

APP内所有的API调用自轻淘客，很不错的一个网站，最起码api能看，技术也很热心，不向某某基地，另外上啦下拉刷新引用了开源库PullToRefreshListView

网络层：rxjava+retrofit2 图片加载和轮播glide+convenientbanner 跳转淘宝引用了阿里的百川SDK，都是坑，该项目属于练手项目 代码写的有很多不足勿喷

安装说明:将项目中houtaiwenjian目录下的houtaiwenjian.rar解压，其他gx是负责APK更新已经首页轮播图的接口，lingjuan则是后台文件，如下流程图中的网页端，需自行修改lingjuan/yewu/目录下的三个PHP文件中的数据库为自己的，然后在项目中api/getLatest.java中修改服务器地址即可

注：lingjuan必须放到网站根目录，如需放到其他目录请自行修改后台文件中的地址，gx目录随意，放到哪里 项目中写哪里即可

Github地址

https://github.com/CrackgmKey/lingJuan/ 欢迎start


流程图如下
![image](https://github.com/CrackgmKey/lingJuan/blob/master/tupian/jdfw.gif)

首页UI
![image](https://github.com/CrackgmKey/lingJuan/blob/master/tupian/1.jpg)

商品UI
![image](https://github.com/CrackgmKey/lingJuan/blob/master/tupian/2.jpg)

搜索UI
![image](https://github.com/CrackgmKey/lingJuan/blob/master/tupian/4.jpg)