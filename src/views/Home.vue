<template>
  <!--banner image-->

  <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
    <div  class="images">
      <div class="profile">
        <img src="../assets/widyacantikk-removebg-preview.png" class="rounded-circle"
             height="200px" width="200px">
      </div>
      <div class="content text-center">
        <h1 class="text-white">Widya Maulida Putri</h1>

      </div>
    </div>
  </div>


</template>

<script>
export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
.text-center{
  margin-top: 50px;
}
.images {
  margin-top: 50px;
}
.banner-image{
  background: rgb(94, 94, 157);
  background-size: cover;
}


</style>
