<script lang="ts">
	import { Button } from "$lib/components/ui/button"

	let count = $state(0)

	const incrementCount = () => {
		count += 1
	}
</script>

<p class="text-lg py-4">The current count is: <span class="text-orange-500">{count}</span></p>

<Button onclick={incrementCount}>Click me</Button>
