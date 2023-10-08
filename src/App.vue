<template>
  <nav class="bg-blue-500 p-4 shadow-lg flex flex-col lg:flex-row">
    <router-link
      to="/"
      class="text-while px-4 py-2 m-1 rounded-md"
      exact-active-class="bg-red-300"
      >Home</router-link
    >
    <router-link
      to="/about"
      class="text-while px-4 py-2 m-1 rounded-md"
      exact-active-class="bg-red-300"
      >About</router-link
    >
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
