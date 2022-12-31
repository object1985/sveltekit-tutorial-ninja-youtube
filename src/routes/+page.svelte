<script>
	let title = "First Gaming Guides";

	const updateTitle = () => {
		console.log("test update title	");
		title = "something completely different";
	};
</script>

<div class="index">
	<h2>{title}</h2>
	<p>
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore
		obcaecati reprehenderit adipisci ipsa tempora, itaque nulla praesentium
		iste totam accusantium repudiandae, eum, illo aliquam omnis in
		architecto aut cumque. Nulla eveniet quam eos nihil repellendus
		consequatur. Iure, pariatur. Repudiandae saepe perferendis sapiente
		nulla, blanditiis eos, dignissimos et ad excepturi aliquid eaque veniam
		quaerat placeat earum natus totam voluptatem in quisquam?
	</p>
	<button on:click={updateTitle}>change title</button>
	<input type="text" bind:value={title} />
</div>

<style>
	.index {
		text-align: center;
		display: block;
		margin: 20px auto;
	}
</style>
