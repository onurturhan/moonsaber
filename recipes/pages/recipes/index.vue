<template>
  <section class="articles">
    <article class="recipe">
      <div
        class="thumbnail"
        style="background-image: url('https://article.images.consumerreports.org/f_auto/prod/content/dam/CRO-Images-2020/Magazine/05May/CR-Health-Inlinehero-HealthyFastFood-3-20-v2')"
      ></div>
      <h1>Title</h1>
      <p>Some nice preview text</p>
    </article>
    <article class="recipe">
      <div
        class="thumbnail"
        style="background-image: url('https://www.elpolloloco.com/content/img/menu/NEW_BajaShrimpTostada_M2_2020_761x561.webp')"
      ></div>
      <h1>Title</h1>
      <p>Some vvv preview text</p>
    </article>
  </section>
</template>

<style scoped>
.recipes {
  display: flex;
  flex-flow: row wrap;
}

.recipe {
  box-sizing: border-box;
  width: 280px;
  padding: 8px;
  border: 1px solid #aaa;
  box-shadow: 0 2px 2px #aaa;
  margin: 10px;
}
.thumbnail {
  background-position: center;
  background-size: cover;
  width: 200px;
  height: 200px;
}
</style>
