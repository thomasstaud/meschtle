<script>
	let name = $state("");

	function print() {
		console.log($state.snapshot(name));
	}
</script>

<h1>Willkommen bei Meschtle!</h1>
<input type="text" placeholder="Name" bind:value={name}/>
<button onclick={print}>check</button>

<style>
	input {
      outline: #ffb931 medium auto;
  }
</style>
