<template>
  <Layout>
    <div class="horizontal-container">
      <div class="vertical-container" style="margin-right: 1em;">
        <p>Username</p>
        <p>Password</p>
      </div>
      <div class="vertical-container">
        <input type="text" id="username" name="username" required minlength="1" maxlength="20" />
        <input type="text" id="password" name="password" required minlength="1" maxlength="20" />
      </div>
    </div>
    <button>Register</button>
  </Layout>
</template>

<script setup>
</script>

<style>
p {
  margin: 0
}

.vertical-container {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.horizontal-container {
  display: flex;
  flex-direction: row;
  align-items: center;
}
</style>