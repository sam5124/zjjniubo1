---
title: "Moments"
description: ""
theme_version: '2.8.2'
featured_image: '/images/forest.jpg'
menu:
  main:
    weight: 1
    
---
<audio controls autoplay loop>
  <source src="/audio/8bite - happy birthday.mp3" type="audio/mpeg">
</audio>

<style>
.container {
  display: flex;
  overflow-x: auto;
}

.image-container {
  flex-shrink: 0;
  width: 600px;
  height: 800px;
  margin-right: 400px;
  border-width: 800px;
}
</style>


## 川剧哥

<div class="container">
  <div class="image-container">
    <img src="/images/Opera.jpg" alt="图片1描述">
  </div>
  <div class="image-container">
    <img src="/images/Opera1.jpg" alt="图片2描述">
  </div>
     <div class="image-container">
    <img src="/images/Opera3.jpg" alt="图片3描述">
  </div>
</div>

## 截取jj哥空间照片

<!DOCTYPE html>
<html>
<head>
	<title>无缝滚动</title>
</head>
<style type="text/css">
	
*{margin: 0;padding: 0;}
	#div1{position: relative;border:1px solid #0ff;width:1510px; height: 550px;margin_top:-100px auto 0;overflow: hidden;margin-left: -500px;}
	#div1 ul{position: absolute;left: 0;}
	#div1 ul li{list-style: none;width:600px;float: left;padding: 10px;height: 1800px;}
	#div1 ul li img{width:100%;}
</style>
<script type="text/javascript">
	window.onload=function(){
		var oDiv=document.getElementById('div1');
		var oUl=oDiv.getElementsByTagName('ul')[0];
		var aLi=oUl.getElementsByTagName('li');
		var aA=document.getElementsByTagName('a');//获取向右向左的箭头
		var timer=null;
		var iSpeed=10;
		oUl.innerHTML+=oUl.innerHTML;//定义图片可以循环播放
		oUl.style.width=aLi.length*aLi[0].offsetWidth+'px';//定义外层ul的宽度，根据图片的个数和每个图片的宽度计算，保证总宽度是可调整的
		function fnMove(){
			if(oUl.offsetLeft<-oUl.offsetWidth/2){
				oUl.style.left=0;
			}else if(oUl.offsetLeft>0){
				oUl.style.left=-oUl.offsetWidth/2+'px';
			}//定义到边界的时候，实现无缝衔接
			oUl.style.left=oUl.offsetLeft+iSpeed+'px';
//定义图片的右边距随着速度不断不断增加，或减小，实现运动的效果
		}
		timer=setInterval(fnMove,200);
		aA[0].onclick=function(){
			iSpeed=-10;
//按下左箭头，定义向左运动
		}
		aA[1].onclick=function(){
			iSpeed=10;
//按下右箭头，定义向右运动
		}
		oDiv.onmouseover=function(){
			clearInterval(timer);
//鼠标移动到图片上，清除定时器，停止运动
		}
		oDiv.onmouseout=function(){
			timer=setInterval(fnMove,175);
//鼠标移出，重新开启定时器，重新运动
		}
	};
</script>
<body>
	<a href="javascript:;">←</a>
	<a href="javascript:;">→</a>
<div id="div1">
	<ul>
	<div class="carousel">
		<li><img src="/images/微信图片_20240102104640.jpg"></li>
		<li><img src="/images/微信图片_20240102104704.jpg"></li>
		<li><img src="/images/微信图片_20240102104704.jpg"></li>
		<li><img src="/images/微信图片_202401021047042.jpg"></li>
		<li><img src="/images/微信图片_20240102104705.jpg"></li>
		<div style="clear: none;"></div>
	</ul>
</div>
</body>
</html>
<br><br>

## 刚买相机就给jj哥拍了一组大片
<img src="/images/CAM.jpg" style="margin-left: -650px;"><br><br>
<img src="/images/cam (2).jpg" style="margin-left: 350px;margin-top: -380px;"><br><br>
<img src="/images/cam (3).jpg" style="margin-left: -650px;margin-top: 0px;"><br><br>
<img src="/images/cam (4).jpg" style="margin-left: 350px;margin-top: -380px;"><br><br>

## 最后放两张年轻点的照片
<img src="/images/young.jpg" style="margin-left: 0px;margin-top: -0px;"><br><br>
<img src="/images/young2.jpg" style="margin-left: 0px;margin-top: -0px;"><br><br>

