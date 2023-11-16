<template>
  <section>
    <h2>My Friends</h2>
    <ul>
      <friend-contact></friend-contact>
      <friend-contact></friend-contact>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: "daniel",
          name: "Prophet Daniel",
          phone: "012345678900",
          email: " prophetdaniel@netcall.com",
        },
        {
          id: "siloaun",
          name: "St Siloaun",
          phone: "012345678900",
          email: " prophetdaniel@netcall.com",
        },
      ],
    };
  },
};
</script>
