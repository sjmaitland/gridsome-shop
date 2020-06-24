<template>
  <Layout>
    <apicart-category class="category" />
  </Layout>
</template>

<script>
  import { ApicartCategory } from '~/assets/js/app.js';

  export default {
    components: {
      'apicart-category': ApicartCategory,
    },
    metaInfo: {
      title: 'Category',
      meta: [
        { 
          key: 'description',
          name: 'description',
          content: 'Amazing e-commerce!'
        }
      ]
    }
  }
</script>