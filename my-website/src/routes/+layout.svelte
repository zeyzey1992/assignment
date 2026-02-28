<script>
	import Narbar from "$lib/components/Narbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import favicon from '$lib/assets/favicon.svg';
</script>

<svelte:head>
	<link rel="icon" href={favicon}/>
</svelte:head>

<Narbar />

<slot /> 	<!-- the content of +page.svelte will be rendered here -->

<Footer />