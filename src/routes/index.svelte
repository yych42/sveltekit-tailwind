<script>
	let count = 0;
</script>

<div class="p-12">
	<h1>Welcome to SvelteKit</h1>
	<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

	<button
		class="text-xl mt-2 bg-svelte-prime-900 text-black py-2 px-6 rounded border border-gray-300 shadow-sm"
		on:click={() => {
			count = count + 1;
		}}
	>
		Clicks: {count}
	</button>
</div>
