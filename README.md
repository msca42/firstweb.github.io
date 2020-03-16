# msca42.site/firstweb.github.io/

	* 安装基础软件

		* 计算机
		* 文本编辑器

			* 纯文本
			* 混合编辑器
		* 浏览器
		* 图像编辑器
		* 版本控制系统
		* FTP工具软件

			* FileZila
		* 自动化构建工具

			* Grunt
			* Gulp
	* 设置一个本地测试服务器

		* 异步问题通过本地运行一个HTTP服务器解决
		* 具体服务端代码，通过具体服务端语言选择
	* 做出计划

		* 你的网页内容是什么？
		* 你的主题中要展示什么信息？
		* 你的网页长得什么样？

			* 背景颜色
			* 字体
			* 参考手册实例： https://mozilla.design/
	* 选择你的内容

		* 文本
		* 主题颜色： https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Colors/Color_picker_tool

			* RGB:三原色交织
			* HSL:色相（颜色名称），饱和度（纯度），L（明亮度）
			* alpha 通道：透明度
			* 六位编码：#30E2C5
		* 图片： Google Images 
		* 字体： https://fonts.google.com/

    <link href="https://fonts.googleapis.com/css?family=Great+Vibes&display=swap" rel="stylesheet">font-family: 'Great Vibes', cursive;HTML文档详解：<!DOCTYPE html>  <head>    <meta charset="utf-8">    <title>测试页面</title>  </head>  <body>    <img src="images/firefox-icon.png" alt="测试图片">  </body></html>
	* <!DOCTYPE html> 文档类型
	* <html></html> :包含整个页面的内容，根元素
	* <head></head>： 不是展现给用户的，包含搜索关键字，页面描述，CS样式表，字符编码声明
	* <mate charset="utf-8"> :指定当前文档使用UTF-8字符编码
	* <title></title> 设置页面的标题，显示在浏览器标签页上，同时作为收藏网页的描述文字
	* <body></body> :包含期望让用户在访问页面时看到的内容

CSS 规则集详解
	* 规则集：上述整体结构
	* 选择器： html元素名称位于规则集开始。它选择了一个或多个需要添加样式的元素
	* 声明：一个单独的规则，用来指定样式元素的属性
	* 属性: 改变HTML元素样式的途径
	* 属性的值：在属性的右边，冒号后面

常用选择器
	* 元素选择器 ：所有指定类型的HTML元素 

		* P <p>
	* ID选择器: 具有特定ID的元素(每个ID只对应一个元素)

		* #my-id  <p id="my-id">
	* 类选择器：具有特定类的元素(单个页面中，一个类可以有多个实例)

		* .my-class  <p class="my-class">
	* 属性选择器：拥有特定属性的元素

		* img[src]   <img src="">
	* 伪类选择器 ：特定状态下的特定元素（鼠标指针悬停）

		* a:hover <a>

盒模型 
	* padding: 内边距，围绕内容的空间
	* border：边距，紧接着内边距的线
	* margin: 外边距，围绕元素外部的空间

去Adobe化

		* https://itsfoss.com/adobe-alternatives-linux/


