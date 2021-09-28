<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark padding">
    <div class="container-fluid">
      <NuxtLink class="navbar-brand" to="/">Firengii</NuxtLink>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/products">Products</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/my-items">My Items</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.padding {
  padding: 1.5rem;
  background-color: black;
}
.nav-left {
  margin-left: auto;
}
</style>
