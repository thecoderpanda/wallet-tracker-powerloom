<script>
	function validate() {
		console.log("I'm the validate() function")
	}
</script>

<form on:submit|preventDefault={validate}>
    <input type="text" placeholder="Enter your Wallet Address">
    <input type="text" placeholder="Enter your Email">

	<button type="submit">
		Subscribe
	</button>
</form>