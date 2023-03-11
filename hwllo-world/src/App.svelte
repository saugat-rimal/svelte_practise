<script>
	// const name = 'Saugat Rimal';
	// const channel = '<b>Code With Saugat</b>';
	// const headingId = 'heading';
	// const disabled = false;
	// const status = 'success';

	// const isPromoted = true;
	// const promoted = true;

	// const num = 4;

	// const names = ['Saugat', 'Rimal', 'hello', 'world'];

	// const fullNames = [
	// 	{first : 'Saugat', last : 'Rimal'},
	// 	{first : 'hello', last : 'world'},
	// 	{first : 'kopila', last : 'Rimal'},
	// 	{first : 'sankapla', last : 'Rimal'},
	// ]

	// let count = 0;

	// function handleClick(event, stepSize) {
	// 	count += stepSize || 1 ;
	// }




</script>

<main>
	<!-- <h1 class="underline"> Hello {name}</h1>
	<h2 class={status}> Welcome to {@html channel}</h2>
	<p> Welcome to {@html channel}</p>
	<h2 {headingId}> This is a heading</h2>
	<button {disabled}>Click Me</button>


	<h2 class={isPromoted ? 'promoted' : '' }>Movie Title</h2>
	<h2 class:promoted={isPromoted}>Movie</h2>
	<h2 class:promoted>Another way</h2> -->


	<!-- {#if num  === 0}
	<h1>The number is zero</h1>
	{:else if num < 0}
	<h1>The number {num} is negative</h1>
	{:else if num > 0}
	<h1>The number {num} is positive</h1>
	{:else}
	<h1>Not a number</h1>
    {/if} -->


	<!-- {#each names as name, index (name)}
	<h1>{index + 1}. {name}</h1>
	{/each}

	{#each fullNames as name, index (name.first)} 
	<h1>{index + 1}. {name.first} {name.last}</h1>
	{/each} -->

	<!-- <h1>{count}</h1>
	<button on:click={handleClick}>add 1</button>
	<button on:click={(event) => handleClick(event, 6)}>add 6</button>
	<button on:click={(event) => handleClick(event, 16)}>add 16</button> -->




	
</main>

<style>

	.promoted{
		font-style: italic;
	}


	.underline {
		text-decoration: underline;
	}

	.danger {
		color: red;
	}

	.success {
		color: green;
	}

	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>