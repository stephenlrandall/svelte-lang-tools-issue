<script>
	import Greeting from "$lib/Greeting.svelte";
	import SharedGreeting from "$shared/SharedGreeting.svelte";
</script>

<h1>
	<Greeting name="world" />
</h1>

<h2>
	<SharedGreeting name="Svelte" />
</h2>
