<template>
    <div>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand><NuxtLink to="/">LOGO</NuxtLink></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item ><NuxtLink  to="/dashboard" >Dashboard</NuxtLink></b-nav-item>
        <b-nav-item ><NuxtLink to="/student">Students</NuxtLink></b-nav-item>
        
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>

        <b-nav-item-dropdown text="Lang" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>
<style>
.nuxt-link-active{
  color: black;
}
.nuxt-link-exact-active{
  font-weight: bold;
}
.b-nav-item .nuxt-link-active{
  color: black;
}
.b-navbar-nav .b-nav-item .nuxt-link{
  color: black;
}

</style>

<script>
export default {
    
}
</script>
