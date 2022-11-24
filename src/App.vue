<template>
  <div id="app">
    <Header></Header>
    <Input></Input>
    <List></List>
    <Footer></Footer>
  </div>
</template>

<script>
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import Input from './components/Input'
import List from './components/List'

export default {
  components : {
    'Header': Header,
    'Input' : Input,
    'List' : List,
    'Footer' : Footer
  }

}
</script>

<style>
  body{
    text-align: center;
    background-color: #F6F6F8;
  }
  input{
    border-style: groove;
    width: 200px;
  }
  botton{
    border-style: groove;
  }
  .shadow{
    box-shadow: 5px 10px 10px rgba(0, 0, 0, 0.03);
  }
</style>

