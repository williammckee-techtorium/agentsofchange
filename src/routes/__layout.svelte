<script>
    import '../app.css';
    import Topbar from "../components/topbar.svelte"
</script>
<Topbar/>
<main>
	<slot />
</main>



<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
		background-color: rgb(255, 255, 255);
		height: 100vw;

	}

</style>

    