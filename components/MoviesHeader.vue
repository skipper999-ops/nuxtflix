<template>
  <header
    class="absolute left-0 top-0 right-0 z-40 max-w-7xl mx-auto p-4 flex items-center"
  >
    <div class="">
      <img class="h-10" src="logo.png" />
    </div>
    <div class="flex ml-10 actions">
      <NuxtLink class="active" to="/movies">Movies</NuxtLink>
      <NuxtLink to="/series">Tv Series</NuxtLink>
      <NuxtLink to="/list">My List</NuxtLink>
    </div>
  </header>
</template>

<style lang="scss" scoped>
.actions {
  a {
    @apply text-white px-3 text-gray-400;
    &.active.nuxt-link-active {
      @apply text-white px-3;
    }
  }
}
</style>
