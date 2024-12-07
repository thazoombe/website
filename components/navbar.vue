<template>
    <div class="bg-cover bg-center h-screen relative" style="background-image: url('/image.png')">
      <nav class="absolute top-0 left-0 w-full flex justify-between p-6 text-white bg-black bg-opacity-50">
        <h1 class="text-2xl font-bold">Attraction Management</h1>
      <ul class="flex space-x-6">
        <li class="hover:underline"><NuxtLink to="/">Home</NuxtLink></li>
        <li class="hover:underline"><NuxtLink to="/planning">Planning</NuxtLink></li>
        <li class="hover:underline"><NuxtLink to="/view">Review</NuxtLink></li>
        <li class="hover:underline"><NuxtLink to="/about">About Us</NuxtLink></li>
      </ul>
          <!-- <li><a href="/" class="hover:underline">Home</a></li>
          <li><a href="" class="hover:underline">Planning</a></li>
          <li><a href="/view" class="hover:underline">Review</a></li>
          <li><a href="/about" class="hover:underline">About Us</a></li> -->
    
      </nav>
  
      <div class="flex flex-col justify-center items-center text-center h-full">
        <h2 class="text-4xl sm:text-6xl font-bold text-white">FIND THE PERFECT PLACE TO GO</h2>
        <div class="mt-6 flex items-center">
          <input
            type="text"
            placeholder="What would you like to go?"
            class="p-3 rounded-l-lg w-80 sm:w-96 focus:outline-none"
          />
          <button class="p-3 bg-blue-500 text-white rounded-r-lg hover:bg-blue-600">
            Planning
          </button>
        </div>
      </div>
    </div>
    
  </template>
  
  <script setup>
  // No additional JavaScript needed for this simple layout
  </script>
  
  <style>
  /* You can optionally add more global styles here */
  </style>
