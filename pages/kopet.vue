<template>
  <div>
    <KopetCom :user="usr" />
    <KopetClass :user="usr" />
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import KopetCom from '~/components/kopetcom'
import KopetClass from '~/components/kopetclass'

export default Vue.extend({
  components: {
    KopetCom,
    KopetClass,
  },
  data() {
    return {
      usr: {
        firstName: 'paijo',
        lastName: 'dakkar',
      },
    }
  },
})
</script>
