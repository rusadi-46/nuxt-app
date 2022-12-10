<template>
  <div class="min-h-full">
    <Header/>
    
    <main>
      <div class="pt-16">
        <Splide :options="{ rewind: true, isNavigation: false }" aria-label="My Favorite Images">
          <SplideSlide>
            <img class="min-w-full" src="https://www.w3schools.com/howto/img_nature_wide.jpg" alt="Sample 1">
          </SplideSlide>
          <SplideSlide>
            <img class="min-w-full" src="https://www.w3schools.com/howto/img_snow_wide.jpg" alt="Sample 2">
          </SplideSlide>
        </Splide>
      </div>
      <div class="pt-2">
        <div class="py-2 px-4 sm:px-6 lg:px-8">
          <div class="relative -mt-[5.75rem] overflow-hidden pt-[5.75rem]">
            <div class="mt-10 pb-px">
              <div class="container mx-auto px-4 pb-10">
                <h3 class="text-3xl font-semibold text-center py-2 pb-2 underline underline-offset-8">Mengasihi Orang Miskin dan Menderita</h3>
                <div class="flex flex-wrap pt-6">
                  <div class="relative w-full md:w-5/12 ml-auto px-4 pt-4">
                    <div class="md:pr-12">
                      <p class="text-lg leading-relaxed text-slate-500">
                        HOPE worldwide Indonesia idirikan pada tahun 1994 dengan misi sederhana untuk mengasihi orang miskin dan membantu orang sakit dan menderita.
                      </p>
                      <p class="mt-4 text-lg leading-relaxed text-slate-500">
                        Kami terdaftar di Kementerian Hukum dan Hak Asasi Manusia dan Dinas Sosial Republik Indonesia sejak tahun 1998.
                      </p>
                      <div class="absolute bottom-0">
                        <div class="flex flex-wrap items-center">
                          <a href="#" class="items-center text-lg leading-relaxed text-blue-800">Selebihnya tentang kami</a>
                          <svg class="ml-2" style="width:24px;height:24px" viewBox="0 0 24 24">
                            <path fill="currentColor" d="M4,11V13H16L10.5,18.5L11.92,19.92L19.84,12L11.92,4.08L10.5,5.5L16,11H4Z" />
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="w-full md:w-6/12 mr-auto px-4 pt-24 md:pt-4">
                    <img alt="..." class="max-w-full rounded-lg shadow-xl" src="https://www.hopeindonesia.org/wp-content/uploads/2021/08/Main_Page_6-1024x683.jpg">
                  </div>
                </div>
              </div>

              <div class="container mx-auto px-4 pb-10">
                <h3 class="text-3xl font-semibold text-center py-2 pb-6 underline underline-offset-8">Ribuan Masyarakat Membutuhkan Bantuan Kita</h3>
                <div class="flex flex-wrap item-center justify-center mt-4 pb-8">
                  <p class="text-lg leading-relaxed text-slate-500 mr-4">Saya ingin mendukung</p>
                  <select name="" id="" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-md focus:ring-blue-500 focus:border-blue-500 block w-200 p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                    <option value="">Pilihan kategori</option>
                    <option value="">Gempa Sukabumi</option>
                    <option value="">Banjir Jakarta</option>
                    <option value="">Kebakaran Rumah</option>
                  </select>
                </div>

                <Splide :options="{ rewind: true, perPage: 3, gap: 8 }" aria-label="My Favorite Images">
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                  </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                            <h6 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pembangunan rumah di Nias</h6>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Nama Yayasan</p>
                          <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-blue-600 h-2.5 rounded-full" style="width: 45%"></div>
                          </div>
                          <p class="mt-3 font-normal text-gray-700 dark:text-gray-400">Terkumpul</p>
                          <h6 class="mb-3 text-gray-700 dark:text-gray-400 font-semibold">Rp 1.000.000</h6>
                          <div class="flex flex-wrap">
                            <div class="flex items-start mr-6">
                              <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-sm hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                  Dukung Sekarang
                              </a>
                            </div>
                            <div class="flex items-end">
                              <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-sm hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                <svg style="width:24px;height:24px" viewBox="0 0 24 24">
                                  <path fill="currentColor" d="M18,16.08C17.24,16.08 16.56,16.38 16.04,16.85L8.91,12.7C8.96,12.47 9,12.24 9,12C9,11.76 8.96,11.53 8.91,11.3L15.96,7.19C16.5,7.69 17.21,8 18,8A3,3 0 0,0 21,5A3,3 0 0,0 18,2A3,3 0 0,0 15,5C15,5.24 15.04,5.47 15.09,5.7L8.04,9.81C7.5,9.31 6.79,9 6,9A3,3 0 0,0 3,12A3,3 0 0,0 6,15C6.79,15 7.5,14.69 8.04,14.19L15.16,18.34C15.11,18.55 15.08,18.77 15.08,19C15.08,20.61 16.39,21.91 18,21.91C19.61,21.91 20.92,20.61 20.92,19A2.92,2.92 0 0,0 18,16.08Z" />
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                  </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                            <h6 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pembangunan rumah di Nias</h6>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Nama Yayasan</p>
                          <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-blue-600 h-2.5 rounded-full" style="width: 45%"></div>
                          </div>
                          <p class="mt-3 font-normal text-gray-700 dark:text-gray-400">Terkumpul</p>
                          <h6 class="mb-3 text-gray-700 dark:text-gray-400 font-semibold">Rp 1.000.000</h6>
                          <div class="flex flex-wrap">
                            <div class="flex items-start mr-6">
                              <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-sm hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                  Dukung Sekarang
                              </a>
                            </div>
                            <div class="flex items-end">
                              <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-sm hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                <svg style="width:24px;height:24px" viewBox="0 0 24 24">
                                  <path fill="currentColor" d="M18,16.08C17.24,16.08 16.56,16.38 16.04,16.85L8.91,12.7C8.96,12.47 9,12.24 9,12C9,11.76 8.96,11.53 8.91,11.3L15.96,7.19C16.5,7.69 17.21,8 18,8A3,3 0 0,0 21,5A3,3 0 0,0 18,2A3,3 0 0,0 15,5C15,5.24 15.04,5.47 15.09,5.7L8.04,9.81C7.5,9.31 6.79,9 6,9A3,3 0 0,0 3,12A3,3 0 0,0 6,15C6.79,15 7.5,14.69 8.04,14.19L15.16,18.34C15.11,18.55 15.08,18.77 15.08,19C15.08,20.61 16.39,21.91 18,21.91C19.61,21.91 20.92,20.61 20.92,19A2.92,2.92 0 0,0 18,16.08Z" />
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                  </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                            <h6 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pembangunan rumah di Nias</h6>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Nama Yayasan</p>
                          <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-blue-600 h-2.5 rounded-full" style="width: 45%"></div>
                          </div>
                          <p class="mt-3 font-normal text-gray-700 dark:text-gray-400">Terkumpul</p>
                          <h6 class="mb-3 text-gray-700 dark:text-gray-400 font-semibold">Rp 1.000.000</h6>
                          <div class="flex flex-wrap">
                            <div class="flex items-start mr-6">
                              <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-sm hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                  Dukung Sekarang
                              </a>
                            </div>
                            <div class="flex items-end">
                              <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-sm hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                <svg style="width:24px;height:24px" viewBox="0 0 24 24">
                                  <path fill="currentColor" d="M18,16.08C17.24,16.08 16.56,16.38 16.04,16.85L8.91,12.7C8.96,12.47 9,12.24 9,12C9,11.76 8.96,11.53 8.91,11.3L15.96,7.19C16.5,7.69 17.21,8 18,8A3,3 0 0,0 21,5A3,3 0 0,0 18,2A3,3 0 0,0 15,5C15,5.24 15.04,5.47 15.09,5.7L8.04,9.81C7.5,9.31 6.79,9 6,9A3,3 0 0,0 3,12A3,3 0 0,0 6,15C6.79,15 7.5,14.69 8.04,14.19L15.16,18.34C15.11,18.55 15.08,18.77 15.08,19C15.08,20.61 16.39,21.91 18,21.91C19.61,21.91 20.92,20.61 20.92,19A2.92,2.92 0 0,0 18,16.08Z" />
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                  </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                            <h6 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pembangunan rumah di Nias</h6>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Nama Yayasan</p>
                          <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-blue-600 h-2.5 rounded-full" style="width: 45%"></div>
                          </div>
                          <p class="mt-3 font-normal text-gray-700 dark:text-gray-400">Terkumpul</p>
                          <h6 class="mb-3 text-gray-700 dark:text-gray-400 font-semibold">Rp 1.000.000</h6>
                          <div class="flex flex-wrap">
                            <div class="flex items-start mr-6">
                              <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-sm hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                  Dukung Sekarang
                              </a>
                            </div>
                            <div class="flex items-end">
                              <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-sm hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                <svg style="width:24px;height:24px" viewBox="0 0 24 24">
                                  <path fill="currentColor" d="M18,16.08C17.24,16.08 16.56,16.38 16.04,16.85L8.91,12.7C8.96,12.47 9,12.24 9,12C9,11.76 8.96,11.53 8.91,11.3L15.96,7.19C16.5,7.69 17.21,8 18,8A3,3 0 0,0 21,5A3,3 0 0,0 18,2A3,3 0 0,0 15,5C15,5.24 15.04,5.47 15.09,5.7L8.04,9.81C7.5,9.31 6.79,9 6,9A3,3 0 0,0 3,12A3,3 0 0,0 6,15C6.79,15 7.5,14.69 8.04,14.19L15.16,18.34C15.11,18.55 15.08,18.77 15.08,19C15.08,20.61 16.39,21.91 18,21.91C19.61,21.91 20.92,20.61 20.92,19A2.92,2.92 0 0,0 18,16.08Z" />
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                  </div>
                  </SplideSlide>
                </Splide>
              </div>

              <div class="container mx-auto px-4 pb-10 pt-14">
                <h3 class="text-3xl font-semibold text-center py-2 pb-8 underline underline-offset-8">Perjuangan Kami untuk Masyarakat Indonesia</h3>
                <Splide :options="{ rewind: true, perPage: 4, gap: 8 }" aria-label="My Favorite Images">
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                  </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                  </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                  </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                  </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                  </div>
                  </SplideSlide>
                </Splide>
              </div>

              <div class="container mx-auto px-4 pb-10 pt-14">
                <h3 class="text-3xl font-semibold text-center py-2 pb-8 underline underline-offset-8">Berita</h3>
                <Splide :options="{ rewind: true, perPage: 3, gap: 8 }" aria-label="My Favorite Images">
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
                          <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                              Read more
                              <svg aria-hidden="true" class="w-4 h-4 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
                          </a>
                      </div>
                    </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
                          <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                              Read more
                              <svg aria-hidden="true" class="w-4 h-4 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
                          </a>
                      </div>
                    </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
                          <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                              Read more
                              <svg aria-hidden="true" class="w-4 h-4 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
                          </a>
                      </div>
                    </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
                          <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                              Read more
                              <svg aria-hidden="true" class="w-4 h-4 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
                          </a>
                      </div>
                    </div>
                  </SplideSlide>
                  <SplideSlide>
                    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md dark:bg-gray-800 dark:border-gray-700">
                      <a href="#">
                          <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                      </a>
                      <div class="p-5">
                          <a href="#">
                              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                          </a>
                          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
                          <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                              Read more
                              <svg aria-hidden="true" class="w-4 h-4 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
                          </a>
                      </div>
                    </div>
                  </SplideSlide>
                </Splide>
                
                
              </div>

              <div class="container mx-auto px-4 pb-10 pt-14">
                <h3 class="text-3xl font-semibold text-center py-2 pb-6 underline underline-offset-8">Partner Kami</h3>
                <Splide :options="{ rewind: true, perPage: 5, gap: 8 }" aria-label="My Favorite Images">
                  <SplideSlide>
                    <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                  </SplideSlide>
                  <SplideSlide>
                    <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                  </SplideSlide>
                  <SplideSlide>
                    <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                  </SplideSlide>
                  <SplideSlide>
                    <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                  </SplideSlide>
                  <SplideSlide>
                    <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                  </SplideSlide>
                  <SplideSlide>
                    <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                  </SplideSlide>
                  <SplideSlide>
                    <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                  </SplideSlide>
                  <SplideSlide>
                    <img class="rounded-t-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg" alt="" />
                  </SplideSlide>
                </Splide>
              </div>

            </div>
          </div>
        </div>
      </div>
    </main>

    <footer class="mx-auto mt-32 w-full max-w-container px-4 sm:px-6 lg:px-8">
      <div class="border-t border-slate-900/5 py-10">
        <svg class="mx-auto h-5 w-auto text-slate-900" aria-hidden="true" viewBox="0 0 160 24" fill="none">
          <path d="M18.724 1.714c-4.538 0-7.376 2.286-8.51 6.857 1.702-2.285 3.687-3.143 5.957-2.57 1.296.325 2.22 1.271 3.245 2.318 1.668 1.706 3.6 3.681 7.819 3.681 4.539 0 7.376-2.286 8.51-6.857-1.701 2.286-3.687 3.143-5.957 2.571-1.294-.325-2.22-1.272-3.245-2.32-1.668-1.705-3.6-3.68-7.819-3.68zM10.214 12c-4.539 0-7.376 2.286-8.51 6.857 1.701-2.286 3.687-3.143 5.957-2.571 1.294.325 2.22 1.272 3.245 2.32 1.668 1.705 3.6 3.68 7.818 3.68 4.54 0 7.377-2.286 8.511-6.857-1.702 2.286-3.688 3.143-5.957 2.571-1.295-.326-2.22-1.272-3.245-2.32-1.669-1.705-3.6-3.68-7.82-3.68z" class="fill-sky-400"></path>
          <path d="M51.285 9.531V6.857h-3.166v-3.6l-2.758.823v2.777h-2.348v2.674h2.348v6.172c0 3.343 1.686 4.526 5.924 4.011V17.22c-2.094.103-3.166.129-3.166-1.517V9.53h3.166zm12.087-2.674v1.826c-.97-1.337-2.476-2.16-4.468-2.16-3.472 0-6.357 2.931-6.357 6.763 0 3.805 2.885 6.763 6.357 6.763 1.992 0 3.498-.823 4.468-2.186v1.851h2.758V6.857h-2.758zM59.338 17.4c-2.297 0-4.034-1.723-4.034-4.114 0-2.392 1.736-4.115 4.034-4.115s4.034 1.723 4.034 4.115c0 2.391-1.736 4.114-4.034 4.114zM70.723 4.929c.97 0 1.762-.823 1.762-1.775 0-.977-.792-1.774-1.762-1.774s-1.762.797-1.762 1.774c0 .952.792 1.775 1.762 1.775zm-1.379 14.785h2.758V6.857h-2.758v12.857zm5.96 0h2.757V.943h-2.758v18.771zM95.969 6.857l-2.502 8.872-2.655-8.872h-2.63L85.5 15.73l-2.477-8.872h-2.91l4.008 12.857h2.707l2.68-8.665 2.656 8.665h2.706L98.88 6.857h-2.911zm6.32-1.928c.97 0 1.762-.823 1.762-1.775 0-.977-.792-1.774-1.762-1.774s-1.762.797-1.762 1.774c0 .952.792 1.775 1.762 1.775zm-1.379 14.785h2.758V6.857h-2.758v12.857zm12.674-13.191c-1.736 0-3.115.643-3.957 1.98V6.857h-2.758v12.857h2.758v-6.891c0-2.623 1.43-3.703 3.242-3.703 1.737 0 2.86 1.029 2.86 2.983v7.611h2.757V11.82c0-3.343-2.042-5.297-4.902-5.297zm17.982-4.809v6.969c-.971-1.337-2.477-2.16-4.468-2.16-3.473 0-6.358 2.931-6.358 6.763 0 3.805 2.885 6.763 6.358 6.763 1.991 0 3.497-.823 4.468-2.186v1.851h2.757v-18h-2.757zM127.532 17.4c-2.298 0-4.034-1.723-4.034-4.114 0-2.392 1.736-4.115 4.034-4.115 2.297 0 4.034 1.723 4.034 4.115 0 2.391-1.737 4.114-4.034 4.114z" fill="currentColor"></path>
          <path fill-rule="evenodd" clip-rule="evenodd" d="M145.532 3.429h8.511c.902 0 1.768.36 2.407 1.004.638.643.997 1.515.997 2.424v8.572c0 .909-.359 1.781-.997 2.424a3.394 3.394 0 01-2.407 1.004h-8.511a3.39 3.39 0 01-2.407-1.004 3.438 3.438 0 01-.997-2.424V6.857c0-.91.358-1.781.997-2.424a3.39 3.39 0 012.407-1.004zm-5.106 3.428c0-1.364.538-2.672 1.495-3.636a5.09 5.09 0 013.611-1.507h8.511c1.354 0 2.653.542 3.61 1.507a5.16 5.16 0 011.496 3.636v8.572a5.16 5.16 0 01-1.496 3.636 5.086 5.086 0 01-3.61 1.506h-8.511a5.09 5.09 0 01-3.611-1.506 5.164 5.164 0 01-1.495-3.636V6.857zm10.907 6.251c0 1.812-1.359 2.916-3.193 2.916-1.823 0-3.182-1.104-3.182-2.916v-5.65h1.633v5.52c0 .815.429 1.427 1.549 1.427 1.12 0 1.549-.612 1.549-1.428v-5.52h1.644v5.652zm1.72 2.748V7.457h1.644v8.4h-1.644z" fill="currentColor"></path>
        </svg>
        <p class="mt-5 text-center text-sm leading-6 text-slate-500">© 2022 Tailwind Labs Inc. All rights reserved.</p>
        <div class="mt-16 flex items-center justify-center space-x-4 text-sm font-semibold leading-6 text-slate-700">
          <a href="/privacy-policy">Privacy policy</a>
          <div class="h-4 w-px bg-slate-500/20"></div>
          <a href="/changelog">Changelog</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { Splide, SplideSlide } from '@splidejs/vue-splide';
import '@splidejs/vue-splide/css';

export default defineComponent( {
  components: {
    Splide,
    SplideSlide,
  },
} );
</script>
