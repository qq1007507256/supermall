<template>
 <div id="app">
   <router-view/>
<Main-Tab-Bar/>
 </div>
</template>
<script>
import MainTabBar from 'components/content/mainTabbar/MainTabBar'

export default {
  name:'app',
  components: {
    MainTabBar
  }
}
</script>
<style>
 @import "assets/css/base.css";
</style>
