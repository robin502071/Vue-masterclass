<template>
  <img
    :src="imageLink"
    class="w-8 h-8 object-contain rounded-3xl"
  />
</template>

<script>
export default {
  name: "ProfileImage",
  data() {
    return {
      imageLink: "https://cdn-icons-png.flaticon.com/512/147/147144.png",
    };
  },
};
</script>
