<template>
 <ul>
      <li><a href="#home" class="active">Home</a></li>
      <li><a href="#aboutus" >About Us</a></li>
      <li><a href="#contactus" >Contact US</a></li>
      <li><a href="./components/page2.vue" >News</a></li>
  </ul>
  
  <img alt="Vue logo" src="https://image.shutterstock.com/image-photo/golden-bitcoin-on-blue-tech-260nw-1828329179.jpg">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
 ul{
                list-style-type: none;
                margin: 0;
                padding: 0;
                overflow: hidden;
                background-color: #333;
            }
            li{
               float: left;
            }
            li a{
                display: block;
                color:white;
                padding: 14px 16px;
                text-align: center;
                text-decoration: none;
            }
            
            li a.active{
                background-color: #4CAF50;
                color: white;
            }
            
            li a:hover:not(active){
                background-color: #111;
            }
            body{
              background-color: #111;
            }

</style>
