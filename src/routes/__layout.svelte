<script>
  import Nav from '../components/nav.svelte';
</script>

<Nav />

<slot />

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
