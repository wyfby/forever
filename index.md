<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>测试</title>
	<style type="text/css">
		body{
			background-image:url(image/IMG20180717165200.jpg);
			background-size: 100% 100%;
		/*	height: 100%;*/
		}
		html{
			height: 100%;
		}
		@keyframes myfirst{
			0% {opacity: 0}
			20% {opacity: 100}
			40%{opacity: 0}
			60% {opacity: 0}
			80% {opacity: 0}
			100% {opacity: 0}
		}
		@keyframes mysecond{
			0% {opacity: 0}
			20% {opacity: 0}
			40%{opacity: 100}
			60% {opacity: 0}
			80% {opacity: 0}
			100% {opacity: 0}
		}
		@keyframes mythird{
			0% {opacity: 0}
			20% {opacity: 0}
			40%{opacity: 0}
			60% {opacity: 100}
			80% {opacity: 0}
			100% {opacity: 0}
		}
		@keyframes myfourth{
			0% {opacity: 0}
			20% {opacity: 0}
			40%{opacity: 0}
			60% {opacity: 0}
			80% {opacity: 100}
			100% {opacity: 0}
		}
		h2{
			text-align: center;
		}
		p{
			font-size: 60px;
			position: absolute;
			width: 100%;
			text-align: center;
		}
		#one{
			animation: myfirst 10s infinite;
		}
		#two{
			animation: mysecond 10s infinite;
		}
		#three{
			animation: mythird 10s infinite;
		}
		#four{
			animation: myfourth 10s infinite;
		}

	</style>

</head>
<body>
	<audio src="wam/僕が死のうと思ったのは (曾经我也想过一了百了) - 中島美嘉.mp3" controls="controls" autoplay="autoplay"></audio>
		<h2>爱成呼吸</h2>
	<p id="one">曾经我也想过一了百了</p>
	<p id="two">可我又回到了你的身旁</p>
	<p id='three'>愿你我携手余生</p>
	<p id='four'>不负时光不负卿</p>

</body>
</html>
