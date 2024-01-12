<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'


  document.addEventListener("DOMContentLoaded", function () {
  const mobileMenuButton = document.querySelector('[aria-controls="mobile-menu"]');
  const mobileMenu = document.getElementById('mobile-menu');

  // Initially hide the mobile menu by adding the 'hidden' class
  mobileMenu.classList.add('hidden');

  mobileMenuButton.addEventListener('click', function () {
    mobileMenu.classList.toggle('hidden');
  });
});




</script>

<main class="">
    <div class="w-screen h-screen bg-zinc-950">
    <nav class="bg-zinc-950 z-30">
        <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
          <div class="relative flex h-16 items-center justify-between">
            <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
              <!-- Mobile menu button-->
              <button type="button" class="relative inline-flex items-center justify-center  text-gray-400  select-none " aria-controls="mobile-menu" aria-expanded="false">
                <span class="absolute -inset-0.5"></span>
                <span class="sr-only">Open main menu</span>
                <!--
                  Icon when menu is closed.
      
                  Menu open: "hidden", Menu closed: "block"
                -->
                <svg class="ham hamRotate ham-menu fill-blue-100 size-16" viewBox="0 0 100 100" width="80" onclick="this.classList.toggle('active')">
                  <path class="line top" d="m 30,33 h 40 c 3.722839,0 7.5,3.126468 7.5,8.578427 0,5.451959 -2.727029,8.421573 -7.5,8.421573 h -20" />
                  <path class="line middle" d="m 30,50 h 40" />
                  <path class="line bottom" d="m 70,67 h -40 c 0,0 -7.5,-0.802118 -7.5,-8.365747 0,-7.563629 7.5,-8.634253 7.5,-8.634253 h 20" />
                </svg>
                
              </button>
            </div>
            <div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start">
              <div class="flex flex-shrink-0 items-center">
                
                <svg  class="h-8 w-auto fill-blue-100" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 932.4 530.5" style="enable-background:new 0 0 932.4 530.5;" xml:space="preserve"><g>
                                        <path d="M386.9,212.1c-34.8,32-57.3,101.7,3,118.2c24.3,6.7,24.3,6.7,28.5-17.8c10.5-67.7,24.9-134.1,33-202.1
                                            c-45.6,11.2-87,25.6-129.9,43.3c-6.5,2.5-11.5,5.7-10.8,14.9c0.2,21.9-34.3,18.1-40.6,1.2c-26.2-41.1,144.3-84.3,177.5-93.2
                                            c9-2.2,11.3-6.7,12.2-14.9c1.7-15.5,4.3-31,6.8-46.4c1.6-9.6,7.8-14.8,17.2-15.3c25.7,0.2,15.9,45,19.8,63.8
                                            c50.6-8.7,99.5-13.5,150.2-19c10.9-1.2,18,5.1,18.8,15.1c0.8,10.6-5.5,17.5-16.7,18.9c-49.6,7-99,11.2-148.4,20.1
                                            c11.1,121.5,29.5,241.8,53.6,361.4c1.9,15,17.8,6.3,24.2,22.6c6.7,21.7-27.4,46.9-42.6,21.9c-14.6-23.7-19.7-58.6-26.1-82.5
                                            c-5.9,18.1-11.3,40.1-20.5,60.4c-17.3,40.7-73.5,63.1-97.8,15.4c-21.2-42.2-3.1-86.6,8-129.1c-214.9-36.6,25.8-298.2,30.5-202.4
                                            c-4.7,16.3-11.6,32.2-19.5,47.2C411.6,224.5,399.4,223.5,386.9,212.1z M479.7,168.4c-0.4-0.1-0.8-0.3-1.1-0.4
                                            c-9.8,56.7-19.6,113.4-29.5,170.5c23.5,3.6,43.9,11.3,58,32.6C497.8,302,488.8,235.2,479.7,168.4z M441.3,372
                                            c-5.6,20.9-12.3,40.2-15.7,60.1c-4.8,20.5-2,80.2,30.2,49.6c18-20.7,24.5-48.4,25-75.1C482.4,381.8,462.9,375.2,441.3,372z"/>
                                        <path d="M307.3,387.5c-6.6,19.4-12.4,39.6-20.3,58.9c-13.7,41.8-64.9,39.1-76.7-2.5c-4.7-12.5-7-25.8-10-37.4
                                            c-5.1,9.4-5.3,11.6-0.8,22.9c3.7,9.5-0.7,21.3-10.3,22.7c-7.9,1.2-10.6,6-14.1,11.5c-28.2,43.9-67.7,66.9-120.8,64.5
                                            c-17.1-0.2-40.2,11.7-43.1-14.9c-10.6-126-19.7-253.5,2.3-378.9c1.8-21.4,30.6-36.3,39.4-11.3c1.3,16.4,2.4,33-10.1,47.4
                                            c-15.5,73.5-8.8,153.8-4.9,229.1c13.4-40.6,23.2-82.4,46.3-118.5c24.8-38.5,65.6-40.3,95.4-5.2c14.9,17.6,21.8,38.4,24.4,60.9
                                            c0.9,3.6-0.7,8,2.8,10.4c12.8-29.6,23.4-61.9,68.2-54.7c-1.2-15.6-13.3-45.3,7.3-49.5c11.7-2.5,19.1,2.9,22.3,16.6
                                            c15.7,57,27.2,120.3,67.8,165.5c15.8,13-0.9,39.7-18.9,28.2C330,438.4,319.8,409.9,307.3,387.5z M59.2,463.8
                                            c30.9-18.6,61-32.8,94-40c2.3-0.5,5.1-3.2,6-5.5c15.1-41.2,23.9-104.9-20.4-131c-7.2-3.4-13.8-3.2-18.5,3.4
                                            C83,341,74.3,402.5,59.2,463.8z M249.8,442.7c18.9-30.3,23.2-65.6,26.2-100.3c0.9-16.9-18.2-20.8-25.7-7.2
                                            C232.5,367.3,226.4,410.9,249.8,442.7z M123.4,473.7c-0.7-1.4-1.4-2.7-2.1-4.1c-12.6,6.5-25.2,13-37.8,19.5c0.7,1.3,1.4,2.7,2.1,4
                                            C98.2,486.6,110.8,480.1,123.4,473.7z"/>
                                        <path d="M748.3,335.8c-10.4,48.1-1.5,96.4-12,144.2c-3.3,17.8-33.2,17.6-35.4-0.2c-12.8-52.3,0.8-95.8,10.4-146.8
                                            c-4.5-0.2-7.9-0.4-10.1-0.5c-4.9,14.4-8.2,28.3-14.1,41c-25.5,61.4-111.8,48.1-124.1-14c-12-72.5,10.5-85.8,10.6-115.4
                                            c-2.5-22.8,9-37.1,32.3-36.2c57.1-0.3,81.1,34.8,97.3,89.5c2.4-3.1,6.9-6.2,6.8-9.2c-2.5-79.9-21.3-159-15.5-239.3
                                            c2.2-21.9,32.2-25.6,38.2-4.3c16,69,6,141.1,12.5,211.5c25.6-43.7,50.2-86.3,77-129c7.3-9.7,16.9-11.9,25.5-6
                                            c8.1,5.6,8.7,16,2.6,26.3c-17.5,29.4-35.9,58.3-51.5,88.8C713,427,918.6,268.6,931,312.4c3.9,9.5-0.7,19.1-12.7,24
                                            C866,354.5,789.4,394.6,748.3,335.8z M599.4,284.5c-6.5,24.6-9.6,50.7-0.1,75.4c7.7,19.4,38.8,29.2,52.4,5.6
                                            c6.6-11.3,9.7-24.8,13.3-37.6C665.1,315,612.8,294.4,599.4,284.5z M610.6,242.6c14,17.7,29.7,27.5,49,35.7
                                            C651.4,255.1,635.3,245.6,610.6,242.6z"/></g>
                </svg>
              </div>
              <div class="hidden sm:ml-6 sm:block">
                <div class="flex space-x-4">
                  <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
                  
                  <a href="#" class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium">Projects</a>
                  <a href="#" class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium">Contact</a>
                </div>
              </div>
            </div>
            <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
              <button type="button" class="relative rounded-full bg-gray-800 p-1 text-gray-400 hover:text-white focus:outline-none focus:ring-2 focus:ring-white focus:ring-offset-2 focus:ring-offset-gray-800">
                <span class="absolute -inset-1.5"></span>
                <span class="sr-only">View notifications</span>
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M14.857 17.082a23.848 23.848 0 005.454-1.31A8.967 8.967 0 0118 9.75v-.7V9A6 6 0 006 9v.75a8.967 8.967 0 01-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 01-5.714 0m5.714 0a3 3 0 11-5.714 0" />
                </svg>
              </button>
      
       
            </div>
          </div>
        </div>
      
        <!-- Mobile menu, show/hide based on menu state. -->
        <div class="sm:hidden" id="mobile-menu">
          <div class="space-y-1 px-2 pb-3 pt-2 bg-blue-700">
            <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
            <a href="#" class="text-gray-300 hover:bg-zinc-900 hover:text-white block rounded-md px-3 py-2 text-base font-medium">Projects</a>
            <a href="#" class="text-gray-300 hover:bg-zinc-900 hover:text-white block rounded-md px-3 py-2 text-base font-medium">Contact</a>
          </div>
        </div>
      </nav>
    
    <!--<img class="size-72" src="src\assets\bastok_logo.svg" alt="">-->
      <p class="text-lg text-slate-50 w-full pt text-center mt-5">
        Hello, This is Bastok. <br>
        Currently building this website. <br>


        Contact me on instagram <br> <a class="text-cyan-300" href='https://www.instagram.com/bastok.art'>@bastok.art</a> <br><a class="text-cyan-300" href='https://www.instagram.com/siam_19'>@siam_19</a>

        
      </p>
 
    </div>
</main>

<style global lang="postcss">
  @tailwind utilities;
  @tailwind components;
  @tailwind base;

  
</style>