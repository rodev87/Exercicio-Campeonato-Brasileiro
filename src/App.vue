<template>
  <v-app>
    <v-main>
      <AppTopBar/>
      <Inicio/>
    </v-main>
  </v-app>
</template>

<script>
import AppTopBar from './components/shared/AppTopBar'
import Inicio from './components/Inicio'

export default {
  name: 'App',
    components: {
      AppTopBar,
      Inicio
    }
}
</script>

<style lang="scss">

</style>
