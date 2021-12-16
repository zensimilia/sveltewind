<script>
  export let name = 'world';
</script>

<main class="w-[640px] mx-auto text-center">
  <h1 class="font-bold text-2xl mt-4">Hello {name}!</h1>
  <p class="mt-4">
    Visit the <a
      class="text-blue-600 underline-offset-1 underline"
      href="https://svelte.dev/tutorial">Svelte tutorial</a
    > to learn how to build Svelte apps.
  </p>
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
