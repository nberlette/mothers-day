<script setup>
useHead({
  title: "🌷 Happy Mother's Day! 🌷",
  meta: [
    { charset: 'utf-8' },
    { name: 'viewport', content: 'width=device-width, initial-scale=1' },
    {
      hid: 'description',
      name: 'description',
      content:
        "Just wishing a Happy Mother's Day to a really special lady. I love you Mom, thanks for putting up with me.",
    },
  ],
  link: [
    {
      rel: 'icon',
      type: 'image/svg+xml',
      href: 'data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🌷</text></svg>',
    },
  ],
});
</script>

<template>
  <div class="w-screen min-h-screen min-w-screen max-w-[100vw] m-0 p-0 group">
    <div
      class="
        wrapper
        min-w-screen min-h-screen
        m-0
        p-0
        fixed
        inset
        [background-scale:50%]
        sm:[background-scale:100%]
      "
    ></div>
    <div
      class="
        flex flex-col flex-wrap
        justify-evenly
        place-items-center
        w-[90vw]
        align-center
        gap-y-10
        mx-auto
        absolute
        top-[10%]
        left-[20%]
        -translate-x-[50%] -translate-y-[20%]
        bg-white/50
        rounded-2xl
        px-20
        py-25
        shadow-lg
        group-hover:(shadow-2xl
        bg-white/80)
        duration-300
        transition-all
        ease-in
      "
    >
      <span
        class="
          text-[10vw]
          fixed
          top-10
          left-10
          text-white
          drop-shadow-lg
          rose
          select-none
          pointer-events-none
        "
        >🌷</span
      >
      <h1
        class="
          leading-[1.2]
          text-white
          drop-shadow-lg
          hover:drop-shadow-xl
          tracking-tighter
        "
      >
        <div
          class="
            text-7xl
            md:text-8xl
            lg:text-9xl
            2xl:text-10xl
            tracking-tighter
            opacity-100
            bg-gradient-to-r
            from-violet-500
            to-rose-500
            via-pink-400
            bg-clip-text
            text-transparent
            select-none
            pointer-events-none
            grid grid-cols-1
            flex
          "
        >
          <span class="flex col-span-1">Happy</span
          ><span class="flex col-span-1">Mother's</span
          ><span class="flex col-span-1">Day 💕</span>
        </div>
      </h1>

      <div />

      <h2
        class="
          max-w-[65vw]
          sm:max-w-[75vw]
          text-4xl
          md:text-5xl
          xl:text-6xl
          mt-10
          drop-shadow-lg
          flex flex-grow-1
          bg-gradient-to-tr
          from-violet-400
          to-rose-800
          via-pink-600
          bg-clip-text
          text-transparent
          select-none
          pointer-events-none
          leading-[1.66]
        "
      >
        <p class="mb-10">
          Thanks for putting up with me for almost 29 years now.
        </p>
        <p>Love,<br /><em>&mdash;&nbsp;Nicholas</em></p>
      </h2>
    </div>
  </div>
</template>

<style global>
@import '@typehaus/metropolis';
:is(h1, h2, h3, h4, h5, h6) {
  font-family: 'Metropolis', sans-serif !important;
  font-weight: 900 !important;
  text-transform: uppercase;
}
.wrapper {
  --bg-1: url('https://images.unsplash.com/photo-1518314144686-36a36d62a13c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=3570&q=80');
  --bg: var(--bg-1);
  background-image: var(--bg);
  background-attachment: fixed;
  background-size: cover;
  background-position: center right;
  content: '';
  opacity: 0.66;
}
.rose {
  text-shadow: 0.05rem 0.33rem 1rem #0006;
}
h1 {
  position: relative;
  text-shadow: 0 0.25rem 0 #0004, 0.05rem 0.33rem 1.33rem #0002;
}
h1 span {
  /* mix-blend-mode: color-burn; */
  opacity: 1 !important;
}
h2 {
  font-weight: 500 !important;
  text-transform: unset;
  text-shadow: 0 0.1rem 0 #0001;
}
</style>
