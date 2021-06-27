# jQuery-color-class-remove
<head>
	<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
	<title>jQuery tutorial</title>
	<style>
		body{
			background-color: powderblue;
		}
		.test{
			color:red;
			font-weight: bold;
			font-family: verdana;
			font-size: 20px;
		}
		.demo{
			color: blue;
			font-weight: italic;
			font-size:30px;
		}
	</style>
	 <script>
	 	$(document).ready(function(){
	 		$("button").click(function(){
	 			$("p").remove(".test, .demo")   
	 		})
	 	})
	 </script>
    </head>
     <body>
     <p>This is a paragraph</p>
     <p class="test">This is a p element with class .test</p>
     <p class="test">This is a p element with class .test</p>
     <p class="demo">This is a p element with class .demo</p>
     <button>Remove the all .test class and .demo class</button>
   </body>
