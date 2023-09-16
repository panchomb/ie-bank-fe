<template>
  <div class="jumbotron vertical-center">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 text-center">
          <h1>Welcome to IE Bank</h1>
          <p>This is the home page of IE Bank Platform.</p>
          <button @click="redirectToAccounts" class="btn btn-success btn-lg">
            Go to Accounts
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    redirectToAccounts() {
      this.$router.push('/accounts');
    },
  },
};
</script>

<style scoped>

</style>
