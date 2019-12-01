<template>
<v-app class="grey lighten-4">
  <Navbar/>
    <v-content>
      <router-view></router-view>
    </v-content>
</v-app>
</template>

<script>
import Navbar from '@/components/Navbar'
import page4 from '@/views/page4'

export default {
  name: 'App',
  components:{Navbar, page4},
  data: () => ({
    //
  }),
};
</script>
