<template>
    <div class="w-full">
        <div class="p-8 bg-gray-50 flex justify-center section-1">
            <div class="w-full sm:w-3/4 rounded-md bg-wedding relative shadow-xl shadow-black-500"></div>
            <div class="absolute text-white left-10 md:left-8 top-10 md:top-40 text-center" style="z-index: 10">
                <h1 class="text-2xl md:text-7xl font-wedding font-semibold">
                    Rizky & Syifa
                </h1>

                <p class="text-xl md:text-4xl font-wedding text-white">Wedding</p>
            </div>
            <div class="">
                <div class="blob w-44 md:w-80">
                <!-- This SVG is from https://codepen.io/Ali_Farooq_/pen/gKOJqx -->
                <svg xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 310 350">
                    <!-- <defs>
                        <linearGradient id="gradient">
                            <stop offset="14%" stop-color="#fc6b6b" />
                            <stop offset="65%" stop-color="#f77a7a" />
                            <stop offset="97%" stop-color="#fa4343" />
                        </linearGradient>
                    </defs> -->
                    <path d="M156.4,339.5c31.8-2.5,59.4-26.8,80.2-48.5c28.3-29.5,40.5-47,56.1-85.1c14-34.3,20.7-75.6,2.3-111  c-18.1-34.8-55.7-58-90.4-72.3c-11.7-4.8-24.1-8.8-36.8-11.5l-0.9-0.9l-0.6,0.6c-27.7-5.8-56.6-6-82.4,3c-38.8,13.6-64,48.8-66.8,90.3c-3,43.9,17.8,88.3,33.7,128.8c5.3,13.5,10.4,27.1,14.9,40.9C77.5,309.9,111,343,156.4,339.5z"/>
                </svg>
                </div>
            </div>
        </div>

        <div class="text-left bg-gray-50 p-8 pb-16 -mt-48 flex flex-col md:flex-row justify-center">
            <div class="mt-48 w-full md:w-3/4 text-center">
                <h1>Kami Yang Berbahagia</h1>

                <div class="mt-14 text-center md:text-left flex flex-col md:flex-row items-center justify-between">
                    <div class="w-full md:w-1/2 pb-8 md:pr-8">
                        <h2 class="font-wedding text-4xl text-semibold text-gray-800 mb-3">Rizky Adjie Rahmansyah</h2>
                        <p class="text-sm tracking-normal leading-relaxed text-justify text-gray-700">
                            Anak pertama dari Ayah Anda Yohandi dan Ibu Romlah, juga sebagai kakak kelas dari Syifa di SMKN 14 Jakarta, 
                            yang menjadi tempat pertama kami bertemu dan menjalani hubungan sampai saat ini.
                        </p>
                    </div>
                    <div class="w-full md:w-1/2">
                        <div class="w-full relative z-0">
                            <img src="@/assets/aji.jpg" alt="" class="rounded-lg shadow-xl shadow-black-500">
                        </div>
                    </div>
                </div>

                <div class="mt-14 text-center md:text-left flex flex-col md:flex-row items-center justify-between">
                    <div class="w-full md:w-1/2 hidden md:block">
                        <div class="w-full relative z-0">
                            <img src="@/assets/syifa.jpg" alt="" class="rounded-lg shadow-xl shadow-black-500">
                            <div class="hidden md:block">
                                <div class="blob-2">
                                    <svg xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 310 350">
                                        <path d="M156.4,339.5c31.8-2.5,59.4-26.8,80.2-48.5c28.3-29.5,40.5-47,56.1-85.1c14-34.3,20.7-75.6,2.3-111  c-18.1-34.8-55.7-58-90.4-72.3c-11.7-4.8-24.1-8.8-36.8-11.5l-0.9-0.9l-0.6,0.6c-27.7-5.8-56.6-6-82.4,3c-38.8,13.6-64,48.8-66.8,90.3c-3,43.9,17.8,88.3,33.7,128.8c5.3,13.5,10.4,27.1,14.9,40.9C77.5,309.9,111,343,156.4,339.5z"/>
                                    </svg>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="w-full md:w-1/2 pb-8 md:pl-8">
                        <h2 class="font-wedding text-4xl text-semibold text-gray-800 mb-3">Syifa Nadia</h2>
                        <p class="text-sm tracking-normal leading-relaxed text-justify text-gray-700">
                            Putri ketiga dari Ayah Hari Subagyo dan Mamah Uun Yusroni, menjadi satu-satunya anak perempuan di keluarga ini.
                        </p>
                    </div>
                    <div class="w-full md:w-1/2 block md:hidden">
                        <div class="w-full relative z-0">
                            <img src="@/assets/syifa.jpg" alt="" class="rounded-lg shadow-xl shadow-black-500">
                            <div class="hidden md:block">
                                <div class="blob-2">
                                    <svg xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 310 350">
                                        <path d="M156.4,339.5c31.8-2.5,59.4-26.8,80.2-48.5c28.3-29.5,40.5-47,56.1-85.1c14-34.3,20.7-75.6,2.3-111  c-18.1-34.8-55.7-58-90.4-72.3c-11.7-4.8-24.1-8.8-36.8-11.5l-0.9-0.9l-0.6,0.6c-27.7-5.8-56.6-6-82.4,3c-38.8,13.6-64,48.8-66.8,90.3c-3,43.9,17.8,88.3,33.7,128.8c5.3,13.5,10.4,27.1,14.9,40.9C77.5,309.9,111,343,156.4,339.5z"/>
                                    </svg>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="text-center p-8 section-3 flex flex-col md:flex-row justify-center">
            <div class="text-white w-full md:w-2/4 p-8 text-center backdrop-blur-sm bg-white/40">
                <p class="drop-shadow-lg">
                    Bermaksud mengundang {{ getCaller }} :
                </p>
                <h1 class="my-5 font-wedding text-5xl text-semibold text-wedding drop-shadow-lg">{{ name }}</h1>
                <p class="drop-shadow-lg">
                    Untuk datang pada {{ getEvent }} pernikahan kami <br> yang dilaksanakan pada <br> 
                </p>

                <p v-if="schedule == 4" class="mt-5 drop-shadow-lg p-3 border border-white rounded-lg">
                    <span class="font-bold">Minggu, 29 Mei 2022</span> <br>
                    Bertempat di Masjid Al Mabruk, Jl. Pisangan Baru III Pisangan Baru, Kec. Matraman, Kota Jakarta Timur
                </p>
                <p v-else class="mt-5 drop-shadow-lg p-3 border border-white rounded-lg">
                    <span class="font-bold">Sabtu, 4 Juni 2022</span> <br>
                    Bertempat di Aula RPTRA Kelurahan Rawabunga (RPTRA Citra Permata), Jl. Jatinegara Timur IV No.65 Rawabunga, Kec. Jatinegara, Kota Jakarta Timur
                </p>
            </div>

            <div class="w-full md:w-2/4">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d572.4280013569028!2d106.86791138609458!3d-6.212664640871165!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f54631acc2ef%3A0xca542d5a7cba79d0!2sMesjid%20Al%20Mabruk!5e0!3m2!1sen!2sid!4v1652092050195!5m2!1sen!2sid" width="100%" height="100%" style="border:0; min-height: 300px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomePage',
    data() {
        return {
            name: '',
            type: '',
            schedule: ''
        }
    },
    computed: {
        getCaller() {
            if (this.type == '2') {
                return 'Saudara/i'
            } else {
                return 'Bapak/Ibu'
            }
        },
        getEevent() {
            if (this.schedule == 29) {
                return 'akad dan resepsi'
            } else if (this.schedule == 4) {
                return 'resepsi'
            }

            return ''
        }
    },
    mounted() {
        let params = (new URL(document.location)).searchParams;
        this.name = params.get("n");
        this.type = params.get("t");
        this.schedule = params.get("s");
    }
}
</script>

<style scoped>
    .section-1 {
        background: url('@/assets/bg-1.jpeg') no-repeat center;
        background-size: cover;
    }

    .section-3 {
        background: url('@/assets/photo-2.jpg') no-repeat right center;
        background-size: cover;
    }

    .bg-wedding {
        background: url('@/assets/main-banner.jpg') no-repeat center;
        background-size: cover;
        height: 30rem;
    }

    .font-wedding {
        font-family: 'Great Vibes';
    }

    .text-wedding {
        color: #fc6b6b;
    }

    .blob {
        position: absolute;
        top: 0;
        left: 0;
        fill: #fc6b6b;
        /* width: 22rem; */
        /* fill: linear-gradient(90deg, rgba(252,110,248,1) 0%, rgba(250,121,250,1) 35%, rgba(186,0,255,1) 100%); */
        animation: move 10s ease-in-out infinite;
        transform-origin: 50% 50%;
    }

    .blob-2 {
        position: absolute;
        top: 0;
        left: 0;
        fill: #fc6b6b;
        z-index: -1;
        width: 25rem;
        animation: move_2 10s ease-in-out infinite;
        transform-origin: 50% 50%;
        overflow: hidden;
    }

    @keyframes move {
        0%   { transform: scale(1)   translate(10px, -30px); }
        50% { transform: scale(1)   translate(100px, 30px); }
        100% { transform: scale(1)   translate(10px, -30px); }
    }

    @keyframes move_2 {
        0%   { transform: scale(1)   translate(30px, -60px); }
        50% { transform: scale(1)   translate(98px, 100px); }
        100% { transform: scale(1)   translate(30px, -60px); }
    }
</style>
