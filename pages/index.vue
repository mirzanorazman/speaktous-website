<template>
  <main>
    <div class="intro-section flex flex-wrap px-6 py-6 sm:px-12">
      <div class="w-full sm:pt-10 sm:w-3/5">
        <div class="sm:w-64">
          <h1 class="font-extrabold text-4xl">You Share</h1>
          <h1 class="font-extrabold text-4xl -mt-2">We Care</h1>
        </div>
        <div class="section-desc sm:pr-12 text-left">
          <p class="text-lg">
            Speak To Us is an
            <strong class>online chat platform</strong>
            for Malaysian students in the United States to share and express
            their feelings to a fellow Malaysian.
            <br />
            <span class="mt-10">Tell us how you feel. We are here to listen.</span>
          </p>
        </div>
        <div class="buttons flex flex-wrap w-full mt-8 p-0 sm:w-full">
          <button
            class="justify-center text-center text-white bg-green-400 rounded hover:bg-green-700 w-full sm:w-1/3 py-3 px-3 mr-0 sm:mr-2"
            @click.prevent="$router.push('/chat')"
          >Get started</button>
          <button
            class="justify-center text-center text-white bg-gray-400 rounded hover:bg-gray-700 w-full sm:w-1/3 py-3 px-3 mt-3 sm:mt-0"
            @click.prevent="$router.push('/about')"
          >Learn more</button>
        </div>
      </div>
      <div class="logo-placeholder w-full sm:pt-8 sm:w-2/5">
        <img class="w-full" src="../assets/graphics/STU-logo.jpg" alt="SpeakToUs
        Logo" />
      </div>
    </div>

    <div class="share-section bg-gray-200 px-6 sm:px-12 py-6 sm:py-10">
      <div class="title-with-underline relative content-center items-center">
        <h1 class="font-extrabold text-4xl mb-2">Why Share With Us?</h1>
        <div class="underline relative w-1/2 border-b-2 border-green-500"></div>
      </div>
      <div class="hidden flex flex-wrap p-8">
        <div class="w-1/2 flex items-center mb-10">
          <div class="relative">
            <img class="w-40" src="../assets/graphics/login.png" />
            <img class="w-20 absolute top-0 transform translate-x-6" src="../assets/graphics/x.png" />
          </div>
          <h1 class="font-normal text-xl ml-4">No registration needed</h1>
        </div>
        <div class="w-1/2 flex items-center mb-10">
          <img class="w-40" src="../assets/graphics/anon.png" />
          <h1 class="font-normal text-xl ml-4">You are 100% anonymous on our online chat</h1>
        </div>
        <div class="w-1/2 flex items-center">
          <img class="w-40" src="../assets/graphics/Listener.png" />
          <h1 class="font-normal text-xl ml-4">
            Supported by passionate listeners who have signed
            <a
              class="text-green-800 underline"
              href="https://www.cdc.gov/aging/emergency/legal/privacy.htm"
              target="_blank"
            >HIPAA Confidentiality Agreement</a>.
          </h1>
        </div>
        <div class="w-1/2 flex items-center">
          <img class="w-40" src="../assets/graphics/file.png" />
          <h1 class="font-normal text-xl ml-4">Your confidentiality is guaranteed</h1>
        </div>
      </div>
    </div>

    <div class="join-us-section sm:py-10 px-12">
      <div class="bg-green-600 w-1/2 pl-1">
        <h1 class="font-extrabold text-4xl mb-2">Be part of us!</h1>
      </div>
      <div class="flex-wrap flex">
        <div class="w-1/2">
          <h2 class="section-desc mt-5">
            In the SpeakToUs Family, we consist of inspiring individuals with
            passion to care for others and dedication to destigmatize mental health.
            <br />
            <br />We are, first and foremost, Malaysian, and we aim to be a source of
            support to our fellow Malaysians abroad in need.
            <br />
            <br />Does this description “speak” you? Come and join us!
          </h2>
          <div class="mt-8">
            <button
              class="justify-center px-4 py-2 mb-2 w-40 text-center text-white bg-green-400 rounded hover:bg-green-700"
              @click.prevent="$router.push('/joinus')"
            >Join us!</button>
          </div>
        </div>
        <div class="w-1/2">
          <img class="ml-12 w-4/5" src="../assets/graphics/meeting.png" />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {}
</script>

<style>
.main-screen {
  height: 95vh;
}
.section-title {
  @apply font-semibold text-center text-gray-700 text-4xl mb-4;
}
.section-desc {
  @apply text-gray-700;
}
</style>
