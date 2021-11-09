<script>
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
import { LotBTN } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  components: {
    LotBTN,
  }
});
</script>

<template>
  <div id="app">
    <lot-btn />
  </div>
</template>
