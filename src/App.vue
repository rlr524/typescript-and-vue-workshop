<script>
	import TheNavBar from "./components/TheNavBar.vue";
	import TheFooter from "./components/TheFooter.vue";

	export default {
		components: {
			TheNavBar,
			TheFooter,
		},
	};
</script>

<template>
	<TheNavBar />
	<RouterView />
	<TheFooter />
</template>

<style scoped></style>
