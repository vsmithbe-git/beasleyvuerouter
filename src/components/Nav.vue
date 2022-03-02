<template>
    <div class="bg-blue-800 text-blue-100 placeholder-yellow-700">
        <div class="container mx-auto flex justify-between items-center py-7">
            <h1 class="tracking-tight text-3xl font-thin"><span class="font-semibold">Beasley</span>Basic<span class="font-semibold">Router</span>
                </h1>
        
          </div>
    </div>  
          <div>
        <nav>
                <ul class="">
                  <router-link to="/"><li class=" text-blue-900 font-semibold hover:cursor-pointer  hover:text-fuchsia-600 hover:font-bold px-2">Home</li></router-link>
                   
                    
                   <router-link to="/about"><li class=" text-blue-900 font-semibold hover:cursor-pointer  hover:text-fuchsia-600 hover:font-bold px-2">About</li></router-link>

                    <router-link to="/registration"><li class=" text-blue-900 font-semibold hover:cursor-pointer  hover:text-fuchsia-600 hover:font-bold px-2">Registration</li></router-link>
                </ul>
            </nav>
            </div>
          
</template>