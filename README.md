
<!DOCTYPE html>

<html>

<head>

<meta charset="utf-8">

<title>module2-solution</title>

</head>

<style >

	/*basic style*/

	* {

		box-sizing: border-box;

	}

	body {

		background-color: white;

	}

	h1 {

		margin: 100px;

		text-align: center;

		font-family: Helvetica;

		font-weight: bold;

		font-size: 175%;

	}

	section {

		position: relative;

		padding: 15px;

		width: 100%;

	}

	p {

		position: relative;

		clear: right;

	}

	div {

		position: relative;

		background-color: gray;

		border: 1px solid black;

		width: 100%;

		margin-left: auto;

		margin-right: auto;

		margin-bottom: auto;

	}

	.sub1 {

		float: right;

		width: 100px;

		padding: 5px;

		margin: 0px;

		border: 1px solid black;

		text-align: center;

		font-size: 125%;

		font-weight: bold;

		background-color:  pink;

		

	}

	.sub2 {

		float: right;

		color: white;

		width: 100px;

		padding: 5px;

		margin: 0px;

		border: 1px solid black;

		text-align: center;

		font-size: 125%;

		font-weight: bold;

		background-color: red;

		

	}

	.sub3 {

		color: black;

		float: right;

		width: 100px;

		padding: 5px;

		margin: 0px;

		border: 1px solid black;

		text-align: center;

		font-size: 125%;

		font-weight: bold;

		background-color:  yellow;

		

	}

	.content {

		padding: 5px;

		border: none;

		background-color: gray;

		font-family: Helvetica;

		color: black;

		margin: 0px;

		height: 200px;

		overflow: auto;

	}

	

	.row {

		width: 90%;

	}

	

	/*desktop version*/

	@media (min-width: 992px){

		.column-lg-4 {

			float: left;

			width: 33.33%;

		}

	}

	/*tablet version*/

	@media (min-width: 768px) and (max-width: 991px){

		.colmn-md-6 {

			float: left;

			width: 50%;

			margin-left: auto;

			margin-right: auto;

		}

		.colmn-md-12 {

			float: left;

			width: 100%;

			margin-left: auto;

			margin-right: auto;

		}

	}

	/*mobile version*/

	@media (max-width: 767px){

		.colmn-sm-12 {

			float: left;

			width: 100%;

		}

	}

</style>

<body >

<h1>Our Menu</h1>

	<section class="column-lg-4 colmn-md-6 colmn-sm-12">

		<div>

			<p class="sub1">Chicken</p>

			<p class="content">

			 Lorem ipsum dolor sit amet, consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

			</p>

		</div>

	</section>

	<section class="column-lg-4 colmn-md-6 colmn-sm-12">

		<div>

			<p class="sub2">Beef</p>

			<p class="content">Lorem ipsum dolor sit amet, consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.  </p>

		</div>

	</section>

	<section class="column-lg-4 colmn-md-12 colmn-sm-12">

	<div>

		<p class="sub3">Shushi</p>

			<p class="content">Lorem ipsum dolor sit amet, consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>

	</div>

</body>

</html>
