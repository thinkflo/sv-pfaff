<script>
	export let className;
</script>

<section class={`content ${className}`}>
	<div class="max-w-2xl mx-auto text-center">
		<slot />
	</div>
</section>
