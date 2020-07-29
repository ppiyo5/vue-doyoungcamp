<template>
  <div>
    <div>
      <h1>
        Products
      </h1>
    </div>

    <div>
      <ProductListingContainer />
    </div>

    <div>
      <ArticleTeaserContainer />
    </div>
  </div>
</template>

<script>
import ArticleTeaserContainer from "../components/ArticleTeaserContainer.vue";
import ProductListingContainer from "../components/ProductListingContainer.vue";

export default {
  name: `PageProducts`,
  components: {
    ArticleTeaserContainer,
    ProductListingContainer
  }
};
</script>

<style lang="scss"></style>
