<script setup>

let services = ["Personalized Gifts", "Professional Branding Items", "Home Decor", "Keepsakes", "And More"]

</script>

<template>
	<main class="py-6 px-2">
		<h1 class="font-semibold text-2xl text-red-600">Services</h1>
		<div class="flex flex-row items-center">
		<div>
		<ul class="px-4 py-6">
			<li v-for="service in services" :key="service">
				{{ service }}
			</li>
		</ul>
		</div>
		<div class="mr-0 ml-auto max-w-[60%]">
			<h2 class="font-bold text-xl">Whether for a special occasion, business needs, or just something unique, my services cater to both practical and creative projects!</h2>
		</div>
		</div>
	</main>
</template>
