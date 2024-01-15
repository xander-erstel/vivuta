<script setup>
</script>
<template>
  <div class="bg-amber-100 h-screen">
    <div class="container mx-auto px-4 pb-32 pt-48">
      <div class="items-center flex flex-wrap">
        <div class="w-full md:w-5/12 ml-auto px-12 md:px-4">
          <div class="md:pr-12">
            <a href="https://github.com/xander-erstel/vivuta">
              <div
                  class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg hover:shadow-sm rounded-full bg-white"
              >

                <i class="fas fa-file-alt text-xl"></i>

              </div>
            </a>
            <div class="pt-32 sm:pt-0">
              <h1 class="font-semibold text-4xl text-blueGray-600"> Vivuta - A beautiful<br/>
              Development Pack. </h1>
              <p class="mt-4 text-lg leading-relaxed text-blueGray-500"> Vivuta is Free and Open Source. Contains Vite, Vue 3, Tailwindcss. </p>
              <div class="mt-12"><a
                  href="https://github.com/xander-erstel/vivuta"
                  target="_blank"
                  class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-emerald-500 active:bg-emerald-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150">
                Get started </a>
                </div>
            </div>
          </div>
        </div>

        <div class="w-full md:w-6/12 mr-auto px-4 pt-24 md:pt-0">
          <img
              alt="..."
              class="max-w-full rounded-lg shadow-xl"
              style="
                transform: scale(1) perspective(1040px) rotateY(-11deg)
                  rotateX(2deg) rotate(2deg);
              "
              src="/xander.png"
          />
        </div>
      </div>
    </div>
  </div>
</template>
