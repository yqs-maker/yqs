<template>
  <div class="about">
    <h1>This is an about page</h1>
	<button @click="aaa">按钮</button>
  </div>
  
</template>
<script>
	export default {
		methods:{
			aaa() {
				this.$router.replace('/')
				console.log(this);
			}
		}
	}
</script>