---
title: 聯絡我們
date: 2026-07-11T10:09:35+00:00
draft: false
language: zh
description: A test with @tailwindcss/typography & Prose
---

<!-- @format -->

<section class="lg:pb-24">
  <div class="px-4 mx-auto max-w-screen-md">
      <p class="mb-8 font-light text-center text-gray-500 lg:mb-16 dark:text-gray-400 sm:text-xl">有任何事情想要回饋？有任何想法想要建議？請填寫此表單聯絡我們。</p>
      <form name="contact" action="https://formsubmit.co/sa@ce.ncu.edu.tw" method="POST" class="space-y-8">
          <div class="my-4">
              <label for="email" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50"><strong>您的信箱：</strong></label>
              <input type="email" name="email" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500" placeholder="name@example.com" required>
          </div>
          <div class="my-4">
              <label for="subject" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50"><strong>主旨：</strong></label>
              <input type="text" name="subject" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500" placeholder="告訴我們哪裡可以幫助到您。" required>
          </div>
          <div class="my-4 sm:col-span-2">
              <label for="message" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50"><strong>您的留言：</strong></label>
              <textarea id="message" name="message" rows="6" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-white focus:border-white dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-white dark:focus:border-white" placeholder="留言……"></textarea>
          </div>
          <div class="mt-6 lg:pb-16">
             <button type="submit" class="px-5 py-3 font-bold text-center text-white bg-indigo-600 rounded-lg text-md sm:w-fit hover:bg-indigo-800 focus:ring-4 focus:outline-none focus:ring-indigo-300 dark:bg-indigo-600 dark:hover:bg-indigo-700 dark:focus:ring-indigo-800">傳送留言</button>
          </div>
      </form>
  </div>
</section>
