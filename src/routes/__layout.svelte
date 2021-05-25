<script>
import "../styles/reset.css"
</script>


<main>
	<div class="container">

		<!-- The <slot> element is where your page component will be inserted. -->
		<slot />
	</div>
</main>



<style>
  * {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
  }

	.container{
		padding: 3rem;

	}


</style>
