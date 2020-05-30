<!--hero-section-end-->
	<nav class="navbar">
		<div class="container">
			<a href="#">PLATO</a>
			<ul id="activeclass">
				<li><a href="#" class="active">Home</a></li>
				<li><a href="#">About</a></li>
				<li><a href="#">Services</a></li>
				<li><a href="#">portfolio</a></li>
				<li><a href="#">Pricing</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</div>
	</nav>
<!--hero-section-end-->



<script>
$(document).ready(function(){
$('nav ul li a').click(function(){
	$('li a').removeClass("active");
	$(this).addClass("active");
});
});
</script>
