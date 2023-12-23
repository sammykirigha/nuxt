<template>
    <div class="  w-full h-screen">
        <div class="flex h-[60px] gap-44 bg-gray-300 w-full">
            <div class="text-[25px]">Logo</div>
            <div>
                <ul class=" flex items-center gap-4 justify-center">
                    <li class="text-[14px] font-[700] leading-6">Home</li>
                    <li class="text-[14px] font-[700] leading-6">Students</li>
                    <li class="text-[14px] font-[700] leading-6">Scores</li>
                </ul>
            </div>
        </div>
        <div class="flex flex-row h-full">
            <div class="bg-blue-500 w-[240px]">
                <ul class=" mt-16 px-3 flex flex-col items-center justify-center gap-5">
                    <li class="text-black text-[16px] font-[700] cursor-pointer ">
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li class="text-black text-[16px] font-[700] cursor-pointer">
                        <NuxtLink to="/students">Students</NuxtLink>
                    </li>
                </ul>
            </div>
            <div class="bg-gray-100 flex-1">
                <NuxtPage />
            </div>
        </div>
    </div>
</template>