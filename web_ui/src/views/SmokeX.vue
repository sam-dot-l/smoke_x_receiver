<template>
  <div class="home">
    <smoke-x-config-form />
  </div>
</template>

<script>
// @ is an alias to /src
import SmokeXConfigForm from "@/components/SmokeXConfigForm.vue";

export default {
  name: "Smoke X",
  components: {
    SmokeXConfigForm
  }
};
</script>
