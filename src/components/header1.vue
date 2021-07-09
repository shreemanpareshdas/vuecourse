<template>
<div class="navbar">
  <a ><span>QUICK </span>Learn</a>
   <a href="">Home</a>
  <router-link to="/about">About us</router-link>
  <div class="dropdown">
    <button class="dropbtn">Course
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
      <a href="#">MBA</a>
      <a href="#">MCA</a>
      <a href="#">Btech</a>
    </div>
  </div>
  <a href="#news">contact</a>
  <input type="text" placeholder="Search..">

</div>
  
    
</template>

<script>
export default {

    name:'header1',
    
}
</script>