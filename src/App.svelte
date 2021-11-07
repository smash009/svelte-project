<script>
	let count = 0;
	function increase() {
		count++;
	}
</script>

<main>
	<h1>Simple Counter</h1>
	<p>count : { count }</p>
	<button on:click="{ increase }">1 Add Count</button>
</main>