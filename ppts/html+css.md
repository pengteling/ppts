title: HTML+CSS
speaker: 泛艺学苑
url: https://www.fydesigner.com
transition: slide2
files: /js/demo.js,/css/demo.css,/js/zoom.js
theme: fanyi
usemathjax: yes

[slide]
# 前端
## 泛艺学苑前端前导课程

[slide]
## 什么是前端
----
* 前端开发工程师是Web前端开发工程师的简称，是近五年才真正开始受到重视的一个新兴职业。Web前端开发技术是一个先易后难的过程，主要包括三个要素:HTML、CSS和JavaScript，这就要求前端开发工程师不仅要掌握基本的Web前端开发技术，网站性能优化、SEO和服务器端的基础知识，而且要学会运用各种工具进行辅助开发以及理论层面的知识，包括代码的可维护性、组件的易用性、分层语义模板和浏览器分级支持等。 {:&.rollIn}
* 前端不只是写网页，更重要的是要解决属于前端领域的各种问题。从广义上来讲，所有用户终端产品与视觉和交互有关的部分，都是前端工程师的专业领域。
[note]
那些著名网站的90年代 http://blog.csdn.net/comsharp/article/details/4532152

从Web1.0 - >  web2.0 -> 移动互联网

从Frontpage 到 网页三剑客（dreamwaver\fireworks\flash）到现代编辑器（sublime\atom\webstorm\hbuilder\aptana\notepad++\editplus\IntelliJ IDEA\vs

WEB图表技术：从服务器生成图片、VML到flashchart到纯JS框架hightcharts到基于html5/canvans/svg的图表框架Echarts

手机WEB：从WML（WAP）到XHTML到HTML5（各种前端框架）



[/note]

[slide]
## 理解HTML、CSS、javascript之间的关系
* 结构层(HTML)、表示层(CSS)、行为层(Javascript)：对于一个网页，HTML定义网页的结构，CSS描述网页的样子，JavaScript设置网页的功能。一个很经典的例子是说HTML就像 一个人的骨骼、器官，而CSS就是人的皮肤，有了这两样也就构成了一个植物人了，加上javascript这个植物人就可以对外界刺激做出反应，可以思考、运动、可以给自己整容化妆（改变CSS）等等，成为一个活生生的人 {:&.fadeIn}
* 如果说HTML是肉身、CSS就是皮相、Javascript就是灵魂。没有Javascript,HTML+CSS是植物人，没有Javascript、CSS是个毁容的植物人。
* 如果说HTML是建筑师，CSS就是干装修的，Javascript是魔术师。
[note]
<pre><code class="markdown">
&lt;html&gt;
    &lt;head&gt;...&lt;/head&gt; 
    &lt;body&gt;...&lt;/body&gt; 
&lt;/html&gt;
</code></pre>
[/note]


[slide]
# 理解HTML、HTML5 {:&.flexbox.vleft}
* HTML是由多种骨头(标签)组成的骨架。HTML5是更多的新骨头(标签),同时去掉了以前觉得不好用的骨头.
* 初学者可以跳过 HTML 直接学习 HTML5 吗？
HTML5只是HTML下一代的技术规范，相应的，HTML5包含了旧规范的绝大多数内容，在此的基础上加了好多新鲜的玩意（JavaScript API，画布、媒体播放等），HTML5无非是现今常用的XHTML1.0（HTML4.0）的升级版罢了，就像PS6和PS的关系。HTML5的基础还HTML，学HTML5之前也必须有js基础，否则你是学不会HTML5，只会感觉多了几个标签。

[note]
由于HTML5的新增API及JS的强大功能，浏览器不再是单纯浏览网页，而是变成了一个编程的SDK与操作系统互通的中间层。<br>
H5 != HTML5 <br>
易企秀 ih5
[/note]

[slide]
# 了解CSS历史
* HTML为了满足人们不断膨胀的欲望和要求努力扩充技能树，最后弄得自己苦不堪言，一大堆描述样式的标签（现在还有的&lt;i&gt;&lt;em&gt;等）搞得开发乱七八糟。结构化标记语言就这样变成了一坨一坨的字符串。网页样式是借鉴于传统的报纸等印刷品的排版。
* CSS的本质可以分为宏观与微观两方面。 
宏观上它的存在就是为了控制页面的显示样式。包括布局，颜色，字体等。微观上则是实现这种控制功能的各种属性的定义和工作原理。了解定义就能干活，知道原理才能把活干好。
* CSS 那么多属性，而且每个属性都有多个值怎么记？
CSS 其属性名和大部分属性值都是语义化的。在系统的了解这些知识之后，应该会找到适合自己的记忆方式。记住常用的，不常用的会查手册。

[slide]
## JavaScript能做什么：
* 页面交互、动画效果 {:&.zoomIn}
* 开发手机APP <br>
Web App  <a href="http://m.dianping.com/">例子：大众点评</a><br>
混合式开发 Hybird App<br>
跨平台开发利器 Covdova(phoneGap) <a href="http://cordova.apache.org/">链接</a><br>
React Native移动应用开发框架 <a href="http://facebook.github.io/react-native/">链接</a><br>
微信小程序 <a href="https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-request.html">链接</a>
* 开发桌面程序 Adodb AIR 、React
* TV端开发：TV盒子、智能电视
* 游戏引擎 Unity3D coco2d-js(WebGL)  creatjs
* 服务器程序 nodejs

[note]
从后端走向前端<br>
<img src="/img/front-end.png" alt=""><br>
从前端走向全栈<br>
阮一峰说：未来只有两种工程师？<br>
端工程师：手机端 PC端 TV端 VR端 ...<br>
云工程师：大数据 云计算<br>
[/note]
[slide]
## 案例欣赏
<note>
<pre>
纯CSS画叮当猫 http://codepen.io/pengteling/pen/BpvPpE 
纯CSS实现蒙娜丽莎，http://codepen.io/jaysalvat/pen/HaqBf
感兴趣
html5情书：http://keleyi.com/keleyi/phtml/html5/31.htm
爱心表白：http://www.html5tricks.com/demo/jiaoben1892/index.html
下雨效果：http://www.zzfriend.com/demo/bbs/yudi/demo1.html
http://www.zzfriend.com/demo/bbs/yudi/demo3.html
实际商业项目 
http://promotion.geely.com/gc9/ 
http://www.changan.com.cn/car/cs75
H5全站效果案例：
http://www.genechem.com.cn/
http://www.shiatang.com/
http://www.hnyfh.cn/
http://intacto10years.com/index_start.php （领英公司10周年）
3D网页
https://paperplanes.world/
</pre>
</note>