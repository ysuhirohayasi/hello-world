<!DOCTYPE html>
<html lang="ja">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>jQuery</title>
	<style>
		.box {
			width: 200px;
			height: 200px;
			background-color: #fcc;
			padding: 10px;
		/*	transition: opacity 400ms,ease 1s;*/
		}
	</style>
</head>
<body>
<!-- 	<div>
		<button id="fadeOut">fadeOut</button>
		<button id="fadeIn">fadeIn</button>
		<button id="slide">slide</button>
	</div>
	<div class="box">box</div>
 -->
<!-- 	<script src="jquery-3.4.1.min.js"></script>
	<script>
		// $('#fadeOut').on('click', function(){
		// 	$('.box').fadeOut(1000);
		// }) -->

		// $('#fadeIn').on('click', function(){
		// 	$('.box').fadeIn(1000);
		// })

		$('#slide').on('click', function(){
			$('.box').slideToggle();
		})

		// $('#fadeOut').on('click', function(){
		// 	$('.box').css('background-color','#0f0');
		// })
		// document.getElementById('slide').addEventListener('click', function(){
		// 	document.querySelector('.box').style.height = 0;
		// })
	</script>
	
</body>
</html>
