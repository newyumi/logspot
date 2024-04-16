<template>
  <header class="py-12 px-4 sm:px-6 lg:px-8">
    <div class="relative mx-auto max-w-[35.5rem] pt-20 text-center pb-10">
      <div class="flex items-center justify-center space-x-3">
        <img loading="lazy" src="/logo.png" alt="Logspot" class="h-20 w-20" />
        <h1 class="text-2xl font-extrabold tracking-tight text-slate-700 sm:text-5xl">FE skill interview Q&A</h1>
      </div>
      <p class="mt-6 text-base leading-5 text-slate-600 text-left">
        <span class="text-red-400">Front-end 기술면접</span>을 준비하면서 예상 질문과 답을 적어둔 페이지입니다. 틀린 내용이 있거나 추가하고 싶은
        내용이 있으면 <a class="text-primary underline" href="mailto:queen0701@gmail.com?Subject=Hero에서%20보내는%20메일" target="_top">메일</a>을
        보내주세요 <span class="text-xl">📬</span>
      </p>
      <p class="mt-2 text-sm leading-5 text-slate-600 text-left">
        Logspot 템플릿을 사용해서 만들었습니다. Nuxt, Vue, and Tailwindcss로 만들어진 오픈 소스 로그 템플릿으로
        <a class="text-primary underline" href="https://twitter.com/fayazara" target="_blank">여기</a>를 참고하세요.
      </p>
    </div>
  </header>
</template>

<script setup></script>

<style scoped>
.form-input {
  @apply block h-10 w-full rounded-md bg-white pr-3 pl-12 text-slate-900 shadow-md shadow-black/5 ring-1 ring-slate-900/5 placeholder:text-slate-400 focus:outline-none focus:ring-2 focus:ring-primary sm:text-sm sm:leading-6;
}
.form-submit {
  @apply inline-flex justify-center rounded-lg text-sm font-semibold py-2.5 px-4 bg-slate-900 text-white hover:bg-slate-700 ml-4 flex-none;
}
</style>
