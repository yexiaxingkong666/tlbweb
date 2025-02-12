<template>
	<div>
		<div class="grid grid-cols-3">
			<a href="https://vitejs.dev" target="_blank">
				<img :src="safeResolve('/vite.svg')" class="logo" alt="Vite logo" />
			</a>
		</div>
		<HelloWorld msg="Daily Check-in" />
	</div>
</template>

<style>
.logo {
	width: 10em;
	height: 10em;
	padding: 1.5rem;
	will-change: filter;
	transition: filter 300ms;
}
.logo:hover {
	filter: drop-shadow(0 0 1em #646cffaa);
}
</style>
