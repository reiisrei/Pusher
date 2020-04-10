<template>
  <v-card
    color="grey lighten-4"
    flat
    height="200px"
    tile
  >
    <v-toolbar dark>
      <v-toolbar-title>Marjon</v-toolbar-title>

      <v-spacer></v-spacer>

        <div class="hidden-sm-and-down">
            <router-link to="/forum">
              <v-btn text>Forum</v-btn>
            </router-link>
            <router-link to="/">
             <v-btn text>Ask Question</v-btn>
            </router-link>
             <router-link to="/">
             <v-btn text>Category</v-btn>
            </router-link>
            <router-link to="/login">
              <v-btn text>Login</v-btn>
            </router-link>
        </div>
    </v-toolbar>
  </v-card>
</template>

<script>
export default {
    
}
</script>

<style>

</style>