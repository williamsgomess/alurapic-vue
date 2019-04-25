<template>
  <div>
    <h1>{{title}}</h1>
    <img :src="photo.url" :alt="photo.description">
  </div>
</template>

<script>
  export default {
    data() {
      return {
        title: 'Alurapic',
        photo: {
          url: 'https://abrilsuperinteressante.files.wordpress.com/2018/05/filhotes-de-cachorro-alcanc3a7am-o-c3a1pice-de-fofura-com-8-semanas1.png',
          description: 'Cachorrinho',
        },
      }
    }
  }

</script>

<style>

</style>
