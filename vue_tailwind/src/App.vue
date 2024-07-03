<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
	<header>
		<RouterLink to="/">
			<span :class="'bg-white'">Home</span>
		</RouterLink>
		<RouterLink to="/about">About</RouterLink>
	</header>

	<RouterView />
</template>