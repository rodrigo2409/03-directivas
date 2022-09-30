<template>
  <div>
    <h1>directivas en vue.js</h1>
    <hr />
    <h2>v.tex</h2>
   

    <span v-text="`hola desde la directiva v-text`">      </span>
    <br>
    <span v-text="titulo"> </span>
      <br>
      esta es una trasmutacion de texto con una variable prop
      <br>
      {{titulo}}

    
  </div>

</template>
<script>
    export default {
        data: () => ({
            titulo: "hola desde VUE.js",
        }),
    };
</script>
<style>
    div {
        text-align: center;
        margin: 0px 2rem;
    }
</style>