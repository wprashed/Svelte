<script>
	import Data from "./Data.svelte"
	let name = 'world';
</script>

<style>
	.block{
		background-color: aqua;
		width: 900px;
		margin: 0px auto;
		padding: 20px 40px;
	}
</style>

<div class="block">
	<h1>Hello {name}</h1>
	<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
	Minus ex, quam officia repudiandae inventore eveniet facilis quisquam quod similique libero, 
	praesentium voluptatum dicta perferendis totam, maiores ipsam quae nisi vel.</p>

	<Data name='Rashed' />

	<h1>Name : {name}</h1>
</div>