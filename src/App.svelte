<script>


	document.addEventListener('DOMContentLoaded', function() {
    var elems = document.querySelectorAll('.carousel');
    var instances = M.Carousel.init(elems);
  });
</script>

<main>
	<h1>Hello!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>


	<div class="carousel">
		<a class="carousel-item" href="#one!"><img src="img/Han_Solo.jpg"></a>
		<a class="carousel-item" href="#two!"><img src="img/Han_Solo.jpg"></a>
		<a class="carousel-item" href="#three!"><img src="img/Han_Solo.jpg"></a>
		<a class="carousel-item" href="#four!"><img src="img/Han_Solo.jpg"></a>
		<a class="carousel-item" href="#five!"><img src="img/Han_Solo.jpg"></a>
	  </div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>