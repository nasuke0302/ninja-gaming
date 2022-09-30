<script>
	import Title from '$lib/title.svelte';
</script>

<div class="index">
	<Title />
	<div>
		<a href="/about">About my site</a>
		<a href="/guides">Guides</a>
	</div>
</div>

<style>
	a {
		margin: 20px;
	}
	.index {
		font-size: 1.2rem;
		color: gray;
		text-align: center;
	}
</style>
