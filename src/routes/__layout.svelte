<script lang="ts">
	import Header from '$lib/header/index.svelte';
	import '../app.css';
</script>

<Header />

<main>
	<slot />
</main>

<footer class="flex w-screen justify-center text-sm">
	<p class="font-mono m-auto">Created by Jack Quinn, with love.</p>
</footer>
