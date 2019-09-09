<template>
	<a class="button is-primary">Primary</a>
</template>

<script>
	import "bulma/css/bulma.css"
	
	export default {
		props: {
			colors: {
				type: String
			}
		}
	};
</script>
