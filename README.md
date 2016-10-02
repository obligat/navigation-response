1. 响应式导航条
	- navbar  相关的类和 data 属性，用法参考 [Bootstrap 的 Components 文档][1]。
[1]: http://getbootstrap.com/components/#navbar
 
1.  支持IE8
	- Scott Jehl 的 respond.js "腻子脚本"
	- Bootstrap [自身文档][2]推荐这样做以兼容 IE8。
[2]: http://getbootstrap.com/getting-started/#browsers

3. 在站点模板文件中添加腻子脚本 
  1. [下载 respond.min.js](https://github.com/scottjehl/Respond) 
  2.  把它复制到项目文件夹的 js/vendor 目录下，与 jQuery 和 Modernizr 放到一块。
  3.  把下面加载 respond.js 的代码添加到 index.html 中
	
	  ```
	  <!--Modernizer-->
	    <script src="js/vendor/modernizr-2.8.3.min.js"></script>
	    <!--Respond.js for IE8 or less only-->
	    <!--[if (it IE 9)&(!IEMobile)]-->
	<script src="js/vendor/respond.min.js"></script>
		<!--[endif]-->
	```

