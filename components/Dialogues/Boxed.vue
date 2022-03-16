<template>
  <div class="bg-gray-200 pt-10 h-screen">
      <form class="mx-auto 10 rounded-2xl shadow-lg bg-white max-w-lg">
            <div class="font-bold text-center text-base pt-4">
                PLEASE FILL THE FORM IF YOU'LL BE ATTENDING          
            </div>
            <div class="p-10">
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="username">
                        Name
                    </label>
                    <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="Name">
                </div>

                <div class="mb-6">

                <label class="block text-gray-700 text-sm font-bold mb-2" for="password">
                        Relationship with the couple
                    </label>
                    <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="friend/cousin/uncle/etc">
                </div>

                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="username">
                        Coming with how many?
                    </label>

                    <select>
                        <option class="font-bold text-sm">Alone</option>
                        <option class="font-bold text-sm">1 guest</option>
                        <option class="font-bold text-sm">2 guests</option>
                        <option class="font-bold text-sm">3 guests</option>
                        <option class="font-bold text-sm">4 guests</option>
                        <option class="font-bold text-sm">5 or more guests</option>
                    </select>
                </div>
            </div>
        </form>

        
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>