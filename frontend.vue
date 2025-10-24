<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>ModernVueSite</title>
<link rel="stylesheet" href="/src/assets/main.css" />
</head>
<body>
<div id="app"></div>
<script type="module" src="/src/main.ts"></script>
</body>
</html>
@import
url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
* {
margin: 0;
padding: 0;
box-sizing: border-box;
}
body {
font-family: 'Poppins', sans-serif;
background-color: #fff;
color: #333;
overflow-x: hidden;
}
h1, h2, h3 {
font-weight: 600;
margin-bottom: 1rem;
}
p {
line-height: 1.6;
font-weight: 300;
}
button {
font-family: inherit;
}
import { createApp } from 'vue'
import App from './App.vue'
import './assets/main.css'
createApp(App).mount('#app')
{
"name": "modernvuesite-client",
"version": "1.0.0",
"private": true,
"scripts": {
"dev": "vite",
"build": "vite build",
"preview": "vite preview"
},
"dependencies": {
"vue": "^3.4.0"
},
"devDependencies": {
"@vitejs/plugin-vue": "^5.0.0",
"typescript": "^5.3.0",
"vite": "^5.0.0"
}
}