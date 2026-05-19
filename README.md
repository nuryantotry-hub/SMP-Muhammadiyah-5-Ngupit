# SMP-Muhammadiyah-5-Ngupit
Web Profile SMP Muhammadiyah 5 Ngupit
<!doctype html>
<html lang="id" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Website profil resmi SMP Muhammadiyah 5 Ngupit. Sekolah Islami modern yang membentuk generasi cerdas, berprestasi, dan berakhlak mulia.">
  <meta name="keywords" content="SMP Muhammadiyah 5 Ngupit, sekolah Islam, PPDB, pendidikan Muhammadiyah, sekolah unggulan">
  <title>SMP Muhammadiyah 5 Ngupit</title>
  <script src="/_sdk/element_sdk.js"></script>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&amp;family=Plus+Jakarta+Sans:wght@400;600;700;800&amp;display=swap" rel="stylesheet">
  <style>
    html, body {
      height: 100%;
      width: 100%;
      margin: 0;
      scroll-behavior: smooth;
    }

    body {
      font-family: "Poppins", "Plus Jakarta Sans", sans-serif;
      background: #f5f7f8;
      color: #17231f;
    }

    .app-shell {
      min-height: 100%;
      height: 100%;
      width: 100%;
      overflow-auto;
      background:
        radial-gradient(circle at 8% 10%, rgba(0, 137, 76, 0.14), transparent 30%),
        radial-gradient(circle at 88% 16%, rgba(37, 99, 235, 0.12), transparent 28%),
        linear-gradient(180deg, #f5f7f8 0%, #ffffff 42%, #eef7f3 100%);
    }

    .dark .app-shell {
      background:
        radial-gradient(circle at 8% 10%, rgba(0, 137, 76, 0.22), transparent 30%),
        radial-gradient(circle at 88% 16%, rgba(37, 99, 235, 0.18), transparent 28%),
        linear-gradient(180deg, #0c1713 0%, #101b18 52%, #07120f 100%);
      color: #ecfdf5;
    }

    .glass {
      background: rgba(255,255,255,0.78);
      backdrop-filter: blur(18px);
      border: 1px solid rgba(255,255,255,0.65);
      box-shadow: 0 20px 70px rgba(15, 46, 34, 0.10);
    }

    .dark .glass {
      background: rgba(16, 27, 24, 0.78);
      border-color: rgba(255,255,255,0.10);
      box-shadow: 0 20px 70px rgba(0,0,0,0.28);
    }

    .section-card {
      background: rgba(255,255,255,0.92);
      border: 1px solid rgba(0,137,76,0.10);
      box-shadow: 0 18px 48px rgba(20, 64, 46, 0.08);
    }

    .dark .section-card {
      background: rgba(18, 31, 27, 0.92);
      border-color: rgba(255,255,255,0.10);
      box-shadow: 0 18px 48px rgba(0,0,0,0.22);
    }

    .hero-visual {
      background:
        linear-gradient(135deg, rgba(0,137,76,0.95), rgba(37,99,235,0.82)),
        url("https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
    }

    .soft-grid {
      background-image:
        linear-gradient(rgba(0,137,76,0.08) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0,137,76,0.08) 1px, transparent 1px);
      background-size: 38px 38px;
    }

    .reveal {
      opacity: 0;
      transform: translateY(28px);
      transition: opacity 700ms ease, transform 700ms ease;
    }

    .reveal.show {
      opacity: 1;
      transform: translateY(0);
    }

    .floaty {
      animation: floaty 5s ease-in-out infinite;
    }

    @keyframes floaty {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-14px); }
    }

    .nav-link {
      position: relative;
    }

    .nav-link::after {
      content: "";
      position: absolute;
      left: 0;
      bottom: -7px;
      width: 0;
      height: 2px;
      background: #00894c;
      transition: width 240ms ease;
      border-radius: 999px;
    }

    .nav-link:hover::after,
    .nav-link:focus-visible::after {
      width: 100%;
    }

    .masonry {
      columns: 3 220px;
      column-gap: 18px;
    }

    .masonry-item {
      break-inside: avoid;
      margin-bottom: 18px;
    }

    .map-card {
      background:
        linear-gradient(135deg, rgba(0,137,76,0.10), rgba(37,99,235,0.10)),
        repeating-linear-gradient(45deg, rgba(0,137,76,0.08) 0 2px, transparent 2px 14px);
    }

    .focus-ring:focus-visible {
      outline: 3px solid #2563eb;
      outline-offset: 3px;
    }

    .toast {
      opacity: 0;
      transform: translateY(14px);
      pointer-events: none;
      transition: all 260ms ease;
    }

    .toast.show {
      opacity: 1;
      transform: translateY(0);
    }

    .mobile-menu {
      max-height: 0;
      overflow: hidden;
      transition: max-height 320ms ease;
    }

    .mobile-menu.open {
      max-height: 780px;
    }

    .dark .muted-text {
      color: #b7c8c1;
    }

    .dark .dark-surface {
      background: rgba(12, 23, 19, 0.9);
    }

    @media (max-width: 768px) {
      .hero-visual {
        background-position: center;
      }
    }
  </style>
  <style>body { box-sizing: border-box; }</style>
  <script src="https://cdn.tailwindcss.com/3.4.17" type="text/javascript"></script>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full">
  <div id="app" class="app-shell">
   <header class="sticky top-0 z-50 px-4 py-3">
    <nav class="glass mx-auto max-w-7xl rounded-3xl px-4 py-3" aria-label="Navigasi utama">
     <div class="flex items-center justify-between gap-4">
      <a href="#beranda" class="flex items-center gap-3 focus-ring rounded-2xl" aria-label="Beranda SMP Muhammadiyah 5 Ngupit">
       <div id="logoContainer" class="relative h-12 w-12 rounded-2xl overflow-hidden shadow-lg shadow-green-900/20 bg-[#00894c] text-white grid place-items-center"><img id="schoolLogo" src="" alt="Logo sekolah" class="h-full w-full object-cover hidden" loading="lazy" onerror="console.error('Logo gagal dimuat:', this.src); this.parentElement.style.display='none'; document.getElementById('logoFallback').style.display='grid';">
        <div id="logoFallback" class="h-full w-full grid place-items-center bg-[#00894c] text-white font-extrabold text-lg">
         M5
        </div>
       </div>
       <div>
        <p id="navSchoolName" class="font-extrabold leading-tight text-[#17231f]">SMP Muhammadiyah 5 Ngupit</p>
        <p class="text-xs text-slate-500 muted-text">Sekolah Islami Modern</p>
       </div></a>
      <div class="hidden xl:flex items-center gap-5 text-sm font-semibold text-slate-700 muted-text">
       <a class="nav-link focus-ring rounded" href="#beranda">Beranda</a> <a class="nav-link focus-ring rounded" href="#profil">Profil Sekolah</a> <a class="nav-link focus-ring rounded" href="#visi">Visi &amp; Misi</a> <a class="nav-link focus-ring rounded" href="#guru">Guru &amp; Staff</a> <a class="nav-link focus-ring rounded" href="#akademik">Akademik</a> <a class="nav-link focus-ring rounded" href="#kesiswaan">Kesiswaan</a> <a class="nav-link focus-ring rounded" href="#ekskul">Ekstrakurikuler</a> <a class="nav-link focus-ring rounded" href="#galeri">Galeri</a> <a class="nav-link focus-ring rounded" href="#berita">Berita</a> <a class="nav-link focus-ring rounded" href="#ppdb">PPDB</a> <a class="nav-link focus-ring rounded" href="#kontak">Kontak</a>
      </div>
      <div class="flex items-center gap-2">
       <button id="darkToggle" class="focus-ring rounded-2xl border border-slate-200 bg-white/80 p-3 text-slate-700 hover:bg-slate-100 transition" aria-label="Aktifkan mode gelap"> <i data-lucide="moon" class="h-5 w-5"></i> </button> <a id="navPpdbButton" href="#ppdb" class="hidden sm:inline-flex focus-ring rounded-2xl bg-[#00894c] px-5 py-3 text-sm font-bold text-white shadow-lg shadow-green-900/20 hover:bg-[#007342] transition">Daftar PPDB</a> <button id="menuBtn" class="xl:hidden focus-ring rounded-2xl border border-slate-200 bg-white/80 p-3 text-slate-700 hover:bg-slate-100 transition" aria-label="Buka menu"> <i data-lucide="menu" class="h-5 w-5"></i> </button>
      </div>
     </div>
     <div id="mobileMenu" class="mobile-menu xl:hidden">
      <div class="grid gap-2 pt-4 text-sm font-semibold text-slate-700 muted-text">
       <a href="#beranda" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Beranda</a> <a href="#profil" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Profil Sekolah</a> <a href="#visi" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Visi &amp; Misi</a> <a href="#guru" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Guru &amp; Staff</a> <a href="#akademik" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Akademik</a> <a href="#kesiswaan" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Kesiswaan</a> <a href="#ekskul" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Ekstrakurikuler</a> <a href="#galeri" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Galeri</a> <a href="#berita" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Berita</a> <a href="#ppdb" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">PPDB</a> <a href="#kontak" class="rounded-2xl px-4 py-3 hover:bg-emerald-50">Kontak</a>
      </div>
     </div>
    </nav>
   </header>
   <main>
    <section id="beranda" class="px-4 pb-16 pt-6">
     <div class="hero-visual relative mx-auto max-w-7xl overflow-hidden rounded-[2rem] px-6 py-16 text-white shadow-2xl md:px-12 md:py-24">
      <div class="absolute inset-0 bg-gradient-to-r from-black/40 via-black/15 to-transparent"></div>
      <div class="absolute -right-24 -top-24 h-72 w-72 rounded-full bg-white/15 blur-3xl"></div>
      <div class="absolute bottom-8 right-8 hidden lg:block floaty">
       <div class="rounded-3xl bg-white/18 p-5 backdrop-blur-xl border border-white/30">
        <div class="flex items-center gap-3">
         <div class="rounded-2xl bg-white p-3 text-[#00894c]">
          <i data-lucide="graduation-cap" class="h-7 w-7"></i>
         </div>
         <div>
          <p class="text-sm opacity-90">Akreditasi &amp; Mutu</p>
          <p class="text-xl font-extrabold">Sekolah Unggulan</p>
         </div>
        </div>
       </div>
      </div>
      <div class="relative max-w-3xl reveal show">
       <span class="inline-flex items-center gap-2 rounded-full bg-white/18 px-4 py-2 text-sm font-semibold backdrop-blur-md border border-white/25"> <i data-lucide="sparkles" class="h-4 w-4"></i> Pendidikan Islami Modern </span>
       <h1 id="heroTitle" class="mt-6 text-4xl font-extrabold leading-tight md:text-6xl">Selamat Datang di SMP Muhammadiyah 5 Ngupit</h1>
       <p id="heroSubtitle" class="mt-6 max-w-2xl text-lg leading-8 text-white/92 md:text-xl">Mewujudkan Generasi Islami, Cerdas, Berprestasi, dan Berakhlak Mulia</p>
       <div class="mt-8 flex flex-col gap-3 sm:flex-row">
        <a href="#profil" class="focus-ring inline-flex items-center justify-center rounded-2xl bg-white px-6 py-4 font-bold text-[#00894c] shadow-xl hover:scale-[1.02] transition"> Profil Sekolah <i data-lucide="arrow-right" class="ml-2 h-5 w-5"></i> </a> <a href="#ppdb" id="heroPpdbButton" class="focus-ring inline-flex items-center justify-center rounded-2xl bg-[#2563eb] px-6 py-4 font-bold text-white shadow-xl hover:scale-[1.02] transition"> PPDB Online <i data-lucide="send" class="ml-2 h-5 w-5"></i> </a>
       </div>
      </div>
     </div>
    </section>
    <section id="profil" class="px-4 py-14">
     <div class="mx-auto max-w-7xl">
      <div class="grid gap-8 lg:grid-cols-[1.15fr_0.85fr]">
       <div class="reveal section-card rounded-[2rem] p-7 md:p-10">
        <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Profil Sekolah</span>
        <h2 id="aboutTitle" class="mt-3 text-3xl font-extrabold text-[#17231f] md:text-4xl">Tentang Sekolah</h2>
        <p class="mt-5 leading-8 text-slate-600 muted-text">SMP Muhammadiyah 5 Ngupit hadir sebagai lingkungan belajar yang menumbuhkan kecerdasan, karakter Islami, kepedulian sosial, serta kesiapan menghadapi masa depan. Dengan pendekatan humanis, guru mendampingi siswa agar berkembang sesuai potensi terbaiknya.</p>
        <p class="mt-4 leading-8 text-slate-600 muted-text">Pembelajaran dirancang aktif, menyenangkan, dan relevan dengan kehidupan. Sekolah mengintegrasikan nilai Al-Islam dan Kemuhammadiyahan, literasi digital, prestasi akademik, serta pembinaan akhlak mulia.</p>
        <div class="mt-8 grid grid-cols-2 gap-4 md:grid-cols-4">
         <div class="rounded-3xl bg-emerald-50 p-5 text-center">
          <p class="text-3xl font-extrabold text-[#00894c]">320+</p>
          <p class="mt-1 text-sm text-slate-600">Siswa</p>
         </div>
         <div class="rounded-3xl bg-blue-50 p-5 text-center">
          <p class="text-3xl font-extrabold text-[#2563eb]">28</p>
          <p class="mt-1 text-sm text-slate-600">Guru</p>
         </div>
         <div class="rounded-3xl bg-emerald-50 p-5 text-center">
          <p class="text-3xl font-extrabold text-[#00894c]">75+</p>
          <p class="mt-1 text-sm text-slate-600">Prestasi</p>
         </div>
         <div class="rounded-3xl bg-blue-50 p-5 text-center">
          <p class="text-3xl font-extrabold text-[#2563eb]">12</p>
          <p class="mt-1 text-sm text-slate-600">Ekskul</p>
         </div>
        </div>
       </div>
       <div class="reveal section-card rounded-[2rem] p-7 md:p-8">
        <div class="aspect-[4/3] overflow-hidden rounded-[1.6rem] bg-gradient-to-br from-[#00894c] to-[#2563eb] p-1">
         <div class="grid h-full place-items-center rounded-[1.4rem] bg-white/90 text-center">
          <div>
           <div class="mx-auto grid h-28 w-28 place-items-center rounded-full bg-[#00894c] text-white">
            <i data-lucide="user-round" class="h-14 w-14"></i>
           </div>
           <p class="mt-5 text-xl font-extrabold text-[#17231f]">Kepala Sekolah</p>
           <p class="mt-1 text-slate-600">Sambutan &amp; Inspirasi Pendidikan</p>
          </div>
         </div>
        </div>
        <blockquote class="mt-6 rounded-3xl bg-slate-50 p-6 text-slate-600 leading-8">
         “Kami berkomitmen menghadirkan sekolah yang aman, religius, berprestasi, dan dekat dengan keluarga. Setiap anak adalah amanah yang harus tumbuh dengan ilmu, adab, dan kepercayaan diri.”
        </blockquote>
       </div>
      </div>
     </div>
    </section>
    <section id="visi" class="px-4 py-14 soft-grid">
     <div class="mx-auto max-w-7xl">
      <div class="reveal text-center">
       <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Arah Pendidikan</span>
       <h2 class="mt-3 text-3xl font-extrabold md:text-4xl">Visi, Misi, dan Karakter</h2>
      </div>
      <div class="mt-10 grid gap-5 md:grid-cols-2 lg:grid-cols-4">
       <article class="reveal section-card rounded-[2rem] p-7 hover:-translate-y-2 transition">
        <div class="mb-5 inline-grid rounded-2xl bg-emerald-100 p-4 text-[#00894c]"><i data-lucide="eye" class="h-7 w-7"></i>
        </div>
        <h3 class="text-xl font-extrabold">Visi Sekolah</h3>
        <p class="mt-3 leading-7 text-slate-600 muted-text">Terwujudnya peserta didik Islami, cerdas, mandiri, berprestasi, dan berakhlak mulia.</p>
       </article>
       <article class="reveal section-card rounded-[2rem] p-7 hover:-translate-y-2 transition">
        <div class="mb-5 inline-grid rounded-2xl bg-blue-100 p-4 text-[#2563eb]"><i data-lucide="target" class="h-7 w-7"></i>
        </div>
        <h3 class="text-xl font-extrabold">Misi Sekolah</h3>
        <p class="mt-3 leading-7 text-slate-600 muted-text">Menyelenggarakan pembelajaran berkualitas, pembinaan ibadah, literasi, teknologi, dan budaya prestasi.</p>
       </article>
       <article class="reveal section-card rounded-[2rem] p-7 hover:-translate-y-2 transition">
        <div class="mb-5 inline-grid rounded-2xl bg-emerald-100 p-4 text-[#00894c]"><i data-lucide="heart-handshake" class="h-7 w-7"></i>
        </div>
        <h3 class="text-xl font-extrabold">Nilai Islami</h3>
        <p class="mt-3 leading-7 text-slate-600 muted-text">Menanamkan adab, kejujuran, disiplin, kepedulian, dan semangat beribadah dalam keseharian.</p>
       </article>
       <article class="reveal section-card rounded-[2rem] p-7 hover:-translate-y-2 transition">
        <div class="mb-5 inline-grid rounded-2xl bg-blue-100 p-4 text-[#2563eb]"><i data-lucide="star" class="h-7 w-7"></i>
        </div>
        <h3 class="text-xl font-extrabold">Pelajar Muhammadiyah</h3>
        <p class="mt-3 leading-7 text-slate-600 muted-text">Berilmu, berkemajuan, berakhlak, tangguh, kreatif, dan bermanfaat bagi umat.</p>
       </article>
      </div>
     </div>
    </section>
    <section id="akademik" class="px-4 py-14">
     <div class="mx-auto max-w-7xl">
      <div class="reveal flex flex-col justify-between gap-5 md:flex-row md:items-end">
       <div>
        <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Program Unggulan</span>
        <h2 class="mt-3 text-3xl font-extrabold md:text-4xl">Pembelajaran yang Membentuk Masa Depan</h2>
       </div>
       <p class="max-w-xl leading-7 text-slate-600 muted-text">Program sekolah dirancang seimbang antara ilmu, iman, teknologi, bahasa, karakter, dan pengalaman nyata.</p>
      </div>
      <div class="mt-10 grid gap-5 md:grid-cols-2 lg:grid-cols-3">
       <div class="reveal section-card rounded-[2rem] p-7 hover:shadow-2xl hover:-translate-y-2 transition">
        <i data-lucide="book-open-check" class="h-9 w-9 text-[#00894c]"></i>
        <h3 class="mt-5 text-xl font-extrabold">Tahfidz Al-Qur’an</h3>
        <p class="mt-3 text-slate-600 muted-text leading-7">Pembinaan hafalan bertahap dengan pendampingan guru dan suasana yang menyenangkan.</p>
       </div>
       <div class="reveal section-card rounded-[2rem] p-7 hover:shadow-2xl hover:-translate-y-2 transition">
        <i data-lucide="laptop" class="h-9 w-9 text-[#2563eb]"></i>
        <h3 class="mt-5 text-xl font-extrabold">Teknologi &amp; Informatika</h3>
        <p class="mt-3 text-slate-600 muted-text leading-7">Literasi digital, kreativitas media, dan pengenalan teknologi untuk masa depan siswa.</p>
       </div>
       <div class="reveal section-card rounded-[2rem] p-7 hover:shadow-2xl hover:-translate-y-2 transition">
        <i data-lucide="languages" class="h-9 w-9 text-[#00894c]"></i>
        <h3 class="mt-5 text-xl font-extrabold">English Program</h3>
        <p class="mt-3 text-slate-600 muted-text leading-7">Pembiasaan komunikasi dasar bahasa Inggris untuk meningkatkan percaya diri.</p>
       </div>
       <div class="reveal section-card rounded-[2rem] p-7 hover:shadow-2xl hover:-translate-y-2 transition">
        <i data-lucide="moon-star" class="h-9 w-9 text-[#2563eb]"></i>
        <h3 class="mt-5 text-xl font-extrabold">Kegiatan Keislaman</h3>
        <p class="mt-3 text-slate-600 muted-text leading-7">Shalat berjamaah, pengajian, kultum, pembinaan akhlak, dan budaya salam.</p>
       </div>
       <div class="reveal section-card rounded-[2rem] p-7 hover:shadow-2xl hover:-translate-y-2 transition">
        <i data-lucide="trophy" class="h-9 w-9 text-[#00894c]"></i>
        <h3 class="mt-5 text-xl font-extrabold">Prestasi Akademik</h3>
        <p class="mt-3 text-slate-600 muted-text leading-7">Pendampingan lomba, olimpiade, literasi, numerasi, dan pengembangan bakat.</p>
       </div>
       <div id="ekskul" class="reveal section-card rounded-[2rem] p-7 hover:shadow-2xl hover:-translate-y-2 transition">
        <i data-lucide="sparkles" class="h-9 w-9 text-[#2563eb]"></i>
        <h3 class="mt-5 text-xl font-extrabold">Ekstrakurikuler</h3>
        <p class="mt-3 text-slate-600 muted-text leading-7">Pramuka, olahraga, seni, jurnalistik, tapak suci, hizbul wathan, dan klub minat.</p>
       </div>
      </div>
     </div>
    </section>
    <section id="guru" class="px-4 py-14 bg-white/55">
     <div class="mx-auto max-w-7xl">
      <div class="reveal text-center">
       <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Guru &amp; Staff</span>
       <h2 class="mt-3 text-3xl font-extrabold md:text-4xl">Tim Pendidik Profesional</h2>
      </div>
      <div class="mt-10 grid gap-5 sm:grid-cols-2 lg:grid-cols-4">
       <article class="reveal section-card rounded-[2rem] p-6 text-center">
        <div class="mx-auto grid h-24 w-24 place-items-center rounded-full bg-gradient-to-br from-[#00894c] to-[#2563eb] text-white"><i data-lucide="user" class="h-10 w-10"></i>
        </div>
        <h3 class="mt-5 font-extrabold">Ahmad Fauzi, S.Pd.</h3>
        <p class="text-sm text-[#00894c] font-bold">Kepala Sekolah</p>
        <p class="mt-2 text-sm text-slate-500">Manajemen Pendidikan</p>
       </article>
       <article class="reveal section-card rounded-[2rem] p-6 text-center">
        <div class="mx-auto grid h-24 w-24 place-items-center rounded-full bg-gradient-to-br from-[#00894c] to-[#2563eb] text-white"><i data-lucide="user" class="h-10 w-10"></i>
        </div>
        <h3 class="mt-5 font-extrabold">Siti Aminah, S.Ag.</h3>
        <p class="text-sm text-[#00894c] font-bold">Guru PAI</p>
        <p class="mt-2 text-sm text-slate-500">Al-Islam &amp; Kemuhammadiyahan</p>
       </article>
       <article class="reveal section-card rounded-[2rem] p-6 text-center">
        <div class="mx-auto grid h-24 w-24 place-items-center rounded-full bg-gradient-to-br from-[#00894c] to-[#2563eb] text-white"><i data-lucide="user" class="h-10 w-10"></i>
        </div>
        <h3 class="mt-5 font-extrabold">Rizky Pratama, S.Kom.</h3>
        <p class="text-sm text-[#00894c] font-bold">Guru Informatika</p>
        <p class="mt-2 text-sm text-slate-500">Teknologi &amp; Digital</p>
       </article>
       <article class="reveal section-card rounded-[2rem] p-6 text-center">
        <div class="mx-auto grid h-24 w-24 place-items-center rounded-full bg-gradient-to-br from-[#00894c] to-[#2563eb] text-white"><i data-lucide="user" class="h-10 w-10"></i>
        </div>
        <h3 class="mt-5 font-extrabold">Dewi Lestari, S.Pd.</h3>
        <p class="text-sm text-[#00894c] font-bold">Guru Bahasa Inggris</p>
        <p class="mt-2 text-sm text-slate-500">English Program</p>
       </article>
      </div>
     </div>
    </section>
    <section id="kesiswaan" class="px-4 py-14">
     <div class="mx-auto max-w-7xl">
      <div class="grid gap-6 lg:grid-cols-3">
       <div class="reveal section-card rounded-[2rem] p-7 lg:col-span-1">
        <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Kesiswaan</span>
        <h2 class="mt-3 text-3xl font-extrabold">Fasilitas &amp; Prestasi</h2>
        <p class="mt-4 leading-7 text-slate-600 muted-text">Sekolah mendukung perkembangan siswa melalui fasilitas belajar, pembinaan prestasi, dan lingkungan yang aman.</p>
       </div>
       <div class="reveal grid gap-5 md:grid-cols-2 lg:col-span-2">
        <div class="section-card rounded-[2rem] p-6">
         <i data-lucide="building-2" class="h-8 w-8 text-[#00894c]"></i>
         <h3 class="mt-4 font-extrabold text-xl">Fasilitas Sekolah</h3>
         <ul class="mt-4 space-y-2 text-slate-600 muted-text">
          <li>• Ruang kelas nyaman</li>
          <li>• Perpustakaan &amp; literasi</li>
          <li>• Laboratorium komputer</li>
          <li>• Lapangan olahraga</li>
         </ul>
        </div>
        <div class="section-card rounded-[2rem] p-6">
         <i data-lucide="medal" class="h-8 w-8 text-[#2563eb]"></i>
         <h3 class="mt-4 font-extrabold text-xl">Prestasi Siswa</h3>
         <ul class="mt-4 space-y-2 text-slate-600 muted-text">
          <li>• Lomba tahfidz tingkat kecamatan</li>
          <li>• Olimpiade sains sekolah</li>
          <li>• Juara olahraga pelajar</li>
          <li>• Festival seni Islami</li>
         </ul>
        </div>
       </div>
      </div>
     </div>
    </section>
    <section id="galeri" class="px-4 py-14 bg-slate-50">
     <div class="mx-auto max-w-7xl">
      <div class="reveal flex flex-col justify-between gap-5 md:flex-row md:items-end">
       <div>
        <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Galeri Sekolah</span>
        <h2 class="mt-3 text-3xl font-extrabold md:text-4xl">Momen Belajar dan Bertumbuh</h2>
       </div>
       <p class="max-w-xl leading-7 text-slate-600">Dokumentasi kegiatan sekolah, pembelajaran, olahraga, pengajian, dan agenda siswa.</p>
      </div>
      <div class="masonry mt-10">
       <div class="masonry-item reveal rounded-[2rem] bg-gradient-to-br from-emerald-100 to-blue-100 p-8 h-64">
        <i data-lucide="book-open" class="h-10 w-10 text-[#00894c]"></i>
        <h3 class="mt-4 text-xl font-extrabold">Kegiatan Belajar</h3>
        <p class="mt-2 text-slate-600">Pembelajaran aktif dan kolaboratif.</p>
       </div>
       <div class="masonry-item reveal rounded-[2rem] bg-gradient-to-br from-blue-100 to-white p-8 h-80">
        <i data-lucide="flag" class="h-10 w-10 text-[#2563eb]"></i>
        <h3 class="mt-4 text-xl font-extrabold">Pramuka &amp; HW</h3>
        <p class="mt-2 text-slate-600">Membangun disiplin dan kepemimpinan.</p>
       </div>
       <div class="masonry-item reveal rounded-[2rem] bg-gradient-to-br from-emerald-100 to-white p-8 h-56">
        <i data-lucide="dumbbell" class="h-10 w-10 text-[#00894c]"></i>
        <h3 class="mt-4 text-xl font-extrabold">Olahraga</h3>
        <p class="mt-2 text-slate-600">Sehat, sportif, dan percaya diri.</p>
       </div>
       <div class="masonry-item reveal rounded-[2rem] bg-gradient-to-br from-blue-100 to-emerald-50 p-8 h-72">
        <i data-lucide="moon-star" class="h-10 w-10 text-[#2563eb]"></i>
        <h3 class="mt-4 text-xl font-extrabold">Pengajian</h3>
        <p class="mt-2 text-slate-600">Menguatkan iman dan akhlak.</p>
       </div>
       <div class="masonry-item reveal rounded-[2rem] bg-gradient-to-br from-white to-emerald-100 p-8 h-64">
        <i data-lucide="bus" class="h-10 w-10 text-[#00894c]"></i>
        <h3 class="mt-4 text-xl font-extrabold">Study Tour</h3>
        <p class="mt-2 text-slate-600">Belajar langsung dari lingkungan.</p>
       </div>
       <div class="masonry-item reveal rounded-[2rem] bg-gradient-to-br from-blue-100 to-emerald-100 p-8 h-60">
        <i data-lucide="party-popper" class="h-10 w-10 text-[#2563eb]"></i>
        <h3 class="mt-4 text-xl font-extrabold">Event Sekolah</h3>
        <p class="mt-2 text-slate-600">Perayaan karya dan prestasi siswa.</p>
       </div>
      </div>
     </div>
    </section>
    <section id="berita" class="px-4 py-14">
     <div class="mx-auto max-w-7xl">
      <div class="reveal text-center">
       <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Berita &amp; Informasi</span>
       <h2 class="mt-3 text-3xl font-extrabold md:text-4xl">Kabar Terbaru Sekolah</h2>
      </div>
      <div class="mt-10 grid gap-5 md:grid-cols-3">
       <article class="reveal section-card overflow-hidden rounded-[2rem]">
        <div class="h-40 bg-gradient-to-br from-[#00894c] to-[#2563eb] grid place-items-center text-white"><i data-lucide="newspaper" class="h-12 w-12"></i>
        </div>
        <div class="p-6">
         <p class="text-sm font-bold text-[#00894c]">Artikel Sekolah</p>
         <h3 class="mt-2 text-xl font-extrabold">Pembiasaan Pagi Islami</h3>
         <p class="mt-3 text-slate-600 muted-text">Program harian untuk membangun karakter, adab, dan kedisiplinan siswa.</p>
        </div>
       </article>
       <article class="reveal section-card overflow-hidden rounded-[2rem]">
        <div class="h-40 bg-gradient-to-br from-[#2563eb] to-[#00894c] grid place-items-center text-white"><i data-lucide="megaphone" class="h-12 w-12"></i>
        </div>
        <div class="p-6">
         <p class="text-sm font-bold text-[#2563eb]">Pengumuman</p>
         <h3 class="mt-2 text-xl font-extrabold">Informasi PPDB Dibuka</h3>
         <p class="mt-3 text-slate-600 muted-text">Pendaftaran peserta didik baru telah dibuka untuk tahun ajaran mendatang.</p>
        </div>
       </article>
       <article class="reveal section-card overflow-hidden rounded-[2rem]">
        <div class="h-40 bg-gradient-to-br from-emerald-500 to-blue-500 grid place-items-center text-white"><i data-lucide="calendar-days" class="h-12 w-12"></i>
        </div>
        <div class="p-6">
         <p class="text-sm font-bold text-[#00894c]">Agenda</p>
         <h3 class="mt-2 text-xl font-extrabold">Pekan Kreativitas Siswa</h3>
         <p class="mt-3 text-slate-600 muted-text">Ajang menampilkan karya, minat, bakat, dan kreativitas siswa.</p>
        </div>
       </article>
      </div>
     </div>
    </section>
    <section class="px-4 py-14 bg-white/60">
     <div class="mx-auto max-w-7xl grid gap-6 lg:grid-cols-2">
      <div class="reveal section-card rounded-[2rem] p-7">
       <div class="flex items-center gap-3">
        <i data-lucide="calendar-check" class="h-8 w-8 text-[#00894c]"></i>
        <h2 class="text-2xl font-extrabold">Kalender Akademik</h2>
       </div>
       <div class="mt-6 space-y-3">
        <div class="rounded-2xl bg-slate-50 p-4 flex justify-between gap-4"><span>Awal Tahun Ajaran</span><strong>15 Juli</strong>
        </div>
        <div class="rounded-2xl bg-slate-50 p-4 flex justify-between gap-4"><span>Penilaian Tengah Semester</span><strong>September</strong>
        </div>
        <div class="rounded-2xl bg-slate-50 p-4 flex justify-between gap-4"><span>Class Meeting</span><strong>Desember</strong>
        </div>
        <div class="rounded-2xl bg-slate-50 p-4 flex justify-between gap-4"><span>Ujian Akhir Semester</span><strong>Mei</strong>
        </div>
       </div>
      </div>
      <div class="reveal section-card rounded-[2rem] p-7">
       <div class="flex items-center gap-3">
        <i data-lucide="table-2" class="h-8 w-8 text-[#2563eb]"></i>
        <h2 class="text-2xl font-extrabold">Jadwal &amp; Download</h2>
       </div>
       <div class="mt-6 overflow-hidden rounded-3xl border border-slate-200">
        <div class="grid grid-cols-3 bg-[#00894c] p-4 text-sm font-bold text-white">
         <span>Hari</span><span>Program</span><span>Waktu</span>
        </div>
        <div class="grid grid-cols-3 p-4 text-sm border-t"><span>Senin</span><span>Upacara &amp; KBM</span><span>07.00</span>
        </div>
        <div class="grid grid-cols-3 p-4 text-sm border-t"><span>Rabu</span><span>Tahfidz</span><span>07.15</span>
        </div>
        <div class="grid grid-cols-3 p-4 text-sm border-t"><span>Jumat</span><span>Pengajian</span><span>07.00</span>
        </div>
       </div><button id="downloadBtn" class="focus-ring mt-6 inline-flex items-center rounded-2xl bg-[#2563eb] px-5 py-3 font-bold text-white hover:bg-blue-700 transition"> <i data-lucide="download" class="mr-2 h-5 w-5"></i> Download Brosur PPDB </button>
      </div>
     </div>
    </section>
    <section id="ppdb" class="px-4 py-14">
     <div class="mx-auto max-w-7xl">
      <div class="reveal overflow-hidden rounded-[2rem] bg-gradient-to-br from-[#00894c] via-emerald-700 to-[#2563eb] p-7 text-white md:p-10">
       <div class="grid gap-8 lg:grid-cols-[1fr_0.85fr] lg:items-center">
        <div>
         <span class="inline-flex rounded-full bg-white/15 px-4 py-2 text-sm font-bold backdrop-blur">PPDB Tahun Ajaran Baru</span>
         <h2 class="mt-5 text-3xl font-extrabold md:text-5xl">Ayo Bergabung Bersama SMP Muhammadiyah 5 Ngupit</h2>
         <p class="mt-5 max-w-2xl leading-8 text-white/90">Daftarkan putra-putri terbaik Anda untuk mendapatkan pendidikan Islami, berkualitas, ramah anak, dan berorientasi masa depan.</p>
         <div class="mt-6 grid gap-3 sm:grid-cols-3">
          <div class="rounded-2xl bg-white/14 p-4"><strong>Syarat</strong>
           <p class="text-sm text-white/85">Ijazah/SKL, KK, Akta</p>
          </div>
          <div class="rounded-2xl bg-white/14 p-4"><strong>Gelombang</strong>
           <p class="text-sm text-white/85">Dibuka terbatas</p>
          </div>
          <div class="rounded-2xl bg-white/14 p-4"><strong>Info</strong>
           <p class="text-sm text-white/85">Konsultasi via WA</p>
          </div>
         </div><a href="#kontak" id="ppdbCtaButton" class="focus-ring mt-8 inline-flex rounded-2xl bg-white px-6 py-4 font-extrabold text-[#00894c] shadow-xl hover:scale-[1.02] transition">Daftar Online Sekarang</a>
        </div>
        <div class="rounded-[2rem] bg-white/15 p-6 backdrop-blur-xl border border-white/20">
         <p class="text-center font-bold">Countdown Tahun Ajaran Baru</p>
         <div class="mt-5 grid grid-cols-4 gap-3 text-center">
          <div class="rounded-2xl bg-white text-[#17231f] p-4">
           <p id="days" class="text-2xl font-extrabold">00</p><span class="text-xs">Hari</span>
          </div>
          <div class="rounded-2xl bg-white text-[#17231f] p-4">
           <p id="hours" class="text-2xl font-extrabold">00</p><span class="text-xs">Jam</span>
          </div>
          <div class="rounded-2xl bg-white text-[#17231f] p-4">
           <p id="minutes" class="text-2xl font-extrabold">00</p><span class="text-xs">Menit</span>
          </div>
          <div class="rounded-2xl bg-white text-[#17231f] p-4">
           <p id="seconds" class="text-2xl font-extrabold">00</p><span class="text-xs">Detik</span>
          </div>
         </div>
         <div class="mt-6">
          <h3 class="font-extrabold">FAQ PPDB</h3>
          <div class="mt-3 space-y-3">
           <button class="faqBtn focus-ring w-full rounded-2xl bg-white/15 p-4 text-left font-bold" data-answer="Pendaftaran dapat dilakukan melalui formulir kontak atau WhatsApp sekolah.">Bagaimana cara mendaftar?</button> <button class="faqBtn focus-ring w-full rounded-2xl bg-white/15 p-4 text-left font-bold" data-answer="Calon siswa menyiapkan KK, akta lahir, pas foto, dan ijazah atau SKL.">Apa saja berkas yang diperlukan?</button>
           <p id="faqAnswer" class="hidden rounded-2xl bg-white p-4 text-[#17231f]"></p>
          </div>
         </div>
        </div>
       </div>
      </div>
     </div>
    </section>
    <section class="px-4 py-14">
     <div class="mx-auto max-w-5xl text-center">
      <div class="reveal">
       <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Testimoni</span>
       <h2 class="mt-3 text-3xl font-extrabold md:text-4xl">Cerita Siswa dan Wali Murid</h2>
      </div>
      <div class="reveal section-card mt-10 rounded-[2rem] p-8 md:p-10">
       <i data-lucide="quote" class="mx-auto h-10 w-10 text-[#00894c]"></i>
       <p id="testimonialText" class="mt-5 text-xl leading-9 text-slate-700 muted-text">Sekolahnya nyaman, gurunya ramah, dan anak kami semakin disiplin dalam ibadah serta percaya diri dalam belajar.</p>
       <p id="testimonialName" class="mt-5 font-extrabold text-[#00894c]">Wali Murid Kelas VIII</p>
       <div class="mt-6 flex justify-center gap-3">
        <button id="prevTestimonial" class="focus-ring rounded-full bg-slate-100 p-3 hover:bg-slate-200" aria-label="Testimoni sebelumnya"><i data-lucide="chevron-left" class="h-5 w-5"></i></button> <button id="nextTestimonial" class="focus-ring rounded-full bg-[#00894c] p-3 text-white hover:bg-emerald-700" aria-label="Testimoni berikutnya"><i data-lucide="chevron-right" class="h-5 w-5"></i></button>
       </div>
      </div>
     </div>
    </section>
    <section id="kontak" class="px-4 py-14 bg-slate-50">
     <div class="mx-auto max-w-7xl">
      <div class="grid gap-8 lg:grid-cols-2">
       <div class="reveal">
        <span class="text-sm font-bold uppercase tracking-[0.2em] text-[#00894c]">Kontak &amp; Lokasi</span>
        <h2 id="contactHeading" class="mt-3 text-3xl font-extrabold md:text-4xl">Hubungi Kami</h2>
        <p class="mt-4 leading-8 text-slate-600">Silakan hubungi sekolah untuk informasi PPDB, kunjungan, kerja sama, atau konsultasi pendidikan.</p>
        <div class="mt-8 grid gap-4">
         <div class="section-card rounded-3xl p-5 flex gap-4">
          <i data-lucide="map-pin" class="h-7 w-7 text-[#00894c]"></i>
          <div><strong>Alamat</strong>
           <p class="text-slate-600 muted-text">Ngupit, wilayah Klaten dan sekitarnya</p>
          </div>
         </div>
         <div class="section-card rounded-3xl p-5 flex gap-4">
          <i data-lucide="phone" class="h-7 w-7 text-[#2563eb]"></i>
          <div><strong>WhatsApp</strong>
           <p class="text-slate-600 muted-text">0812-0000-0000</p>
          </div>
         </div>
         <div class="section-card rounded-3xl p-5 flex gap-4">
          <i data-lucide="mail" class="h-7 w-7 text-[#00894c]"></i>
          <div><strong>Email</strong>
           <p class="text-slate-600 muted-text">info@smpmuh5ngupit.sch.id</p>
          </div>
         </div>
        </div>
        <div class="map-card mt-6 rounded-[2rem] p-8 text-center">
         <i data-lucide="map" class="mx-auto h-12 w-12 text-[#00894c]"></i>
         <h3 class="mt-4 text-xl font-extrabold">Peta Lokasi Sekolah</h3>
         <p class="mt-2 text-slate-600">Area peta interaktif disiapkan sebagai tampilan lokasi sekolah.</p><a href="https://www.google.com/maps" target="_blank" rel="noopener noreferrer" class="focus-ring mt-4 inline-flex rounded-2xl bg-[#2563eb] px-5 py-3 font-bold text-white">Buka Google Maps</a>
        </div>
       </div>
       <form id="contactForm" class="reveal section-card rounded-[2rem] p-7 md:p-8" aria-label="Form kontak sekolah">
        <h3 class="text-2xl font-extrabold">Kirim Pesan</h3>
        <p class="mt-2 text-slate-600 muted-text">Pesan akan ditampilkan sebagai konfirmasi di halaman ini.</p>
        <div class="mt-6 grid gap-4">
         <div>
          <label for="name" class="font-semibold">Nama</label> <input id="name" name="name" required class="focus-ring mt-2 w-full rounded-2xl border border-slate-200 bg-white px-4 py-3" placeholder="Nama lengkap">
         </div>
         <div>
          <label for="email" class="font-semibold">Email</label> <input id="email" name="email" type="email" required class="focus-ring mt-2 w-full rounded-2xl border border-slate-200 bg-white px-4 py-3" placeholder="nama@email.com">
         </div>
         <div>
          <label for="message" class="font-semibold">Pesan</label> <textarea id="message" name="message" required rows="5" class="focus-ring mt-2 w-full rounded-2xl border border-slate-200 bg-white px-4 py-3" placeholder="Tulis pesan Anda"></textarea>
         </div>
        </div><button type="submit" class="focus-ring mt-6 w-full rounded-2xl bg-[#00894c] px-6 py-4 font-extrabold text-white hover:bg-emerald-700 transition"> Kirim Pesan </button>
        <p id="formMessage" class="mt-4 hidden rounded-2xl bg-emerald-50 p-4 text-emerald-800"></p>
       </form>
      </div>
     </div>
    </section>
   </main>
   <footer class="px-4 py-10 bg-[#0f2019] text-white">
    <div class="mx-auto max-w-7xl">
     <div class="grid gap-8 md:grid-cols-4">
      <div>
       <div class="flex items-center gap-3">
        <div class="grid h-12 w-12 place-items-center rounded-2xl bg-[#00894c] font-extrabold">
         M5
        </div>
        <div>
         <p id="footerSchoolName" class="font-extrabold">SMP Muhammadiyah 5 Ngupit</p>
         <p class="text-sm text-white/65">Islami • Cerdas • Berprestasi</p>
        </div>
       </div>
       <p class="mt-5 text-sm leading-7 text-white/70">Website profil sekolah modern untuk informasi akademik, PPDB, kegiatan, dan layanan komunikasi sekolah.</p>
      </div>
      <div>
       <h3 class="font-extrabold">Quick Links</h3>
       <div class="mt-4 grid gap-2 text-sm text-white/70">
        <a href="#profil">Profil Sekolah</a> <a href="#akademik">Akademik</a> <a href="#ppdb">PPDB</a> <a href="#kontak">Kontak</a>
       </div>
      </div>
      <div>
       <h3 class="font-extrabold">Media Sosial</h3>
       <div class="mt-4 flex gap-3">
        <a href="https://instagram.com" target="_blank" rel="noopener noreferrer" class="focus-ring rounded-2xl bg-white/10 p-3 hover:bg-white/20" aria-label="Instagram"><i data-lucide="instagram" class="h-5 w-5"></i></a> <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="focus-ring rounded-2xl bg-white/10 p-3 hover:bg-white/20" aria-label="Facebook"><i data-lucide="facebook" class="h-5 w-5"></i></a> <a href="https://youtube.com" target="_blank" rel="noopener noreferrer" class="focus-ring rounded-2xl bg-white/10 p-3 hover:bg-white/20" aria-label="YouTube"><i data-lucide="play" class="h-5 w-5"></i></a>
       </div>
      </div>
      <div>
       <h3 class="font-extrabold">Statistik Pengunjung</h3>
       <p class="mt-4 text-3xl font-extrabold text-emerald-300" id="visitorCount">12.480</p>
       <p class="text-sm text-white/65">Estimasi kunjungan website</p>
      </div>
     </div>
     <div class="mt-10 border-t border-white/10 pt-6 text-center text-sm text-white/60">
      © 2025 SMP Muhammadiyah 5 Ngupit. Semua hak cipta dilindungi.
     </div>
    </div>
   </footer><a href="https://wa.me/6281200000000" target="_blank" rel="noopener noreferrer" class="focus-ring fixed bottom-5 right-5 z-50 inline-flex items-center gap-2 rounded-full bg-[#00894c] px-5 py-4 font-extrabold text-white shadow-2xl hover:bg-emerald-700 transition" aria-label="Hubungi WhatsApp sekolah"> <i data-lucide="message-circle" class="h-6 w-6"></i> <span class="hidden sm:inline">WhatsApp</span> </a>
   <div id="toast" class="toast fixed bottom-24 left-1/2 z-50 -translate-x-1/2 rounded-2xl bg-[#17231f] px-5 py-3 text-sm font-bold text-white shadow-2xl">
    Brosur PPDB siap diunduh.
   </div>
  </div>
  <script>
    const defaultConfig = {
      background_color: "#f5f7f8",
      surface_color: "#ffffff",
      text_color: "#17231f",
      primary_action_color: "#00894c",
      secondary_action_color: "#2563eb",
      font_family: "Poppins",
      font_size: 16,
      school_name: "SMP Muhammadiyah 5 Ngupit",
      hero_title: "Selamat Datang di SMP Muhammadiyah 5 Ngupit",
      hero_subtitle: "Mewujudkan Generasi Islami, Cerdas, Berprestasi, dan Berakhlak Mulia",
      ppdb_button: "Daftar PPDB",
      about_title: "Tentang Sekolah",
      contact_heading: "Hubungi Kami",
      school_logo: ""
    };

    function getConfigValue(config, key) {
      return config[key] || defaultConfig[key];
    }

    async function onConfigChange(config) {
      const app = document.getElementById("app");
      const font = getConfigValue(config, "font_family");
      const base = Number(getConfigValue(config, "font_size")) || 16;
      const backgroundColor = getConfigValue(config, "background_color");
      const surfaceColor = getConfigValue(config, "surface_color");
      const textColor = getConfigValue(config, "text_color");
      const primaryColor = getConfigValue(config, "primary_action_color");
      const secondaryColor = getConfigValue(config, "secondary_action_color");
      const logoUrl = getConfigValue(config, "school_logo");

      document.body.style.fontFamily = `${font}, "Plus Jakarta Sans", sans-serif`;
      document.body.style.color = textColor;
      app.style.backgroundColor = backgroundColor;

      // Update logo
      const schoolLogo = document.getElementById("schoolLogo");
      const logoFallback = document.getElementById("logoFallback");
      if (logoUrl && logoUrl.startsWith("https://")) {
        schoolLogo.src = logoUrl;
        schoolLogo.classList.remove("hidden");
        logoFallback.style.display = "none";
      } else {
        schoolLogo.classList.add("hidden");
        logoFallback.style.display = "grid";
      }

      document.getElementById("navSchoolName").textContent = getConfigValue(config, "school_name");
      document.getElementById("footerSchoolName").textContent = getConfigValue(config, "school_name");
      document.getElementById("heroTitle").textContent = getConfigValue(config, "hero_title");
      document.getElementById("heroSubtitle").textContent = getConfigValue(config, "hero_subtitle");
      document.getElementById("navPpdbButton").textContent = getConfigValue(config, "ppdb_button");
      document.getElementById("ppdbCtaButton").textContent = "Daftar Online Sekarang";
      document.getElementById("aboutTitle").textContent = getConfigValue(config, "about_title");
      document.getElementById("contactHeading").textContent = getConfigValue(config, "contact_heading");

      const headings = document.querySelectorAll("h1");
      headings.forEach(el => {
        el.style.fontFamily = `${font}, "Plus Jakarta Sans", sans-serif`;
        el.style.fontSize = `${base * 2.85}px`;
      });

      document.querySelectorAll("h2").forEach(el => {
        el.style.fontFamily = `${font}, "Plus Jakarta Sans", sans-serif`;
        el.style.fontSize = `${base * 2.1}px`;
        el.style.color = textColor;
      });

      document.querySelectorAll("h3").forEach(el => {
        el.style.fontFamily = `${font}, "Plus Jakarta Sans", sans-serif`;
        el.style.fontSize = `${base * 1.2}px`;
      });

      document.querySelectorAll("p, a, button, label, input, textarea, li, span").forEach(el => {
        el.style.fontFamily = `${font}, "Plus Jakarta Sans", sans-serif`;
      });

      document.querySelectorAll("p, a, button, label, input, textarea, li").forEach(el => {
        el.style.fontSize = `${base}px`;
      });

      document.querySelectorAll(".section-card").forEach(el => {
        el.style.backgroundColor = surfaceColor;
      });

      document.querySelectorAll(".bg-\\[\\#00894c\\]").forEach(el => {
        el.style.backgroundColor = primaryColor;
      });

      document.querySelectorAll(".text-\\[\\#00894c\\]").forEach(el => {
        el.style.color = primaryColor;
      });

      document.querySelectorAll(".bg-\\[\\#2563eb\\]").forEach(el => {
        el.style.backgroundColor = secondaryColor;
      });

      document.querySelectorAll(".text-\\[\\#2563eb\\]").forEach(el => {
        el.style.color = secondaryColor;
      });

      document.getElementById("heroPpdbButton").style.backgroundColor = secondaryColor;
      document.getElementById("downloadBtn").style.backgroundColor = secondaryColor;
    }

    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig,
        onConfigChange,
        mapToCapabilities: (config) => ({
          recolorables: [
            {
              get: () => config.background_color || defaultConfig.background_color,
              set: (value) => window.elementSdk.setConfig({ background_color: value })
            },
            {
              get: () => config.surface_color || defaultConfig.surface_color,
              set: (value) => window.elementSdk.setConfig({ surface_color: value })
            },
            {
              get: () => config.text_color || defaultConfig.text_color,
              set: (value) => window.elementSdk.setConfig({ text_color: value })
            },
            {
              get: () => config.primary_action_color || defaultConfig.primary_action_color,
              set: (value) => window.elementSdk.setConfig({ primary_action_color: value })
            },
            {
              get: () => config.secondary_action_color || defaultConfig.secondary_action_color,
              set: (value) => window.elementSdk.setConfig({ secondary_action_color: value })
            }
          ],
          borderables: [],
          fontEditable: {
            get: () => config.font_family || defaultConfig.font_family,
            set: (value) => window.elementSdk.setConfig({ font_family: value })
          },
          fontSizeable: {
            get: () => config.font_size || defaultConfig.font_size,
            set: (value) => window.elementSdk.setConfig({ font_size: value })
          }
        }),
        mapToEditPanelValues: (config) => new Map([
          ["school_name", config.school_name || defaultConfig.school_name],
          ["hero_title", config.hero_title || defaultConfig.hero_title],
          ["hero_subtitle", config.hero_subtitle || defaultConfig.hero_subtitle],
          ["ppdb_button", config.ppdb_button || defaultConfig.ppdb_button],
          ["about_title", config.about_title || defaultConfig.about_title],
          ["contact_heading", config.contact_heading || defaultConfig.contact_heading],
          ["school_logo", config.school_logo || defaultConfig.school_logo]
        ])
      });
    } else {
      onConfigChange(defaultConfig);
    }

    document.addEventListener("DOMContentLoaded", () => {
      lucide.createIcons();

      const menuBtn = document.getElementById("menuBtn");
      const mobileMenu = document.getElementById("mobileMenu");
      menuBtn.addEventListener("click", () => {
        mobileMenu.classList.toggle("open");
        menuBtn.setAttribute("aria-label", mobileMenu.classList.contains("open") ? "Tutup menu" : "Buka menu");
      });

      mobileMenu.querySelectorAll("a").forEach(link => {
        link.addEventListener("click", () => mobileMenu.classList.remove("open"));
      });

      const darkToggle = document.getElementById("darkToggle");
      darkToggle.addEventListener("click", () => {
        document.documentElement.classList.toggle("dark");
        const isDark = document.documentElement.classList.contains("dark");
        darkToggle.innerHTML = isDark ? '<i data-lucide="sun" class="h-5 w-5"></i>' : '<i data-lucide="moon" class="h-5 w-5"></i>';
        darkToggle.setAttribute("aria-label", isDark ? "Aktifkan mode terang" : "Aktifkan mode gelap");
        lucide.createIcons();
      });

      const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) entry.target.classList.add("show");
        });
      }, { threshold: 0.12 });

      document.querySelectorAll(".reveal").forEach(el => observer.observe(el));

      const targetDate = new Date("2026-07-15T07:00:00").getTime();
      function updateCountdown() {
        const now = Date.now();
        const distance = Math.max(0, targetDate - now);
        const days = Math.floor(distance / (1000 * 60 * 60 * 24));
        const hours = Math.floor((distance / (1000 * 60 * 60)) % 24);
        const minutes = Math.floor((distance / (1000 * 60)) % 60);
        const seconds = Math.floor((distance / 1000) % 60);
        document.getElementById("days").textContent = String(days).padStart(2, "0");
        document.getElementById("hours").textContent = String(hours).padStart(2, "0");
        document.getElementById("minutes").textContent = String(minutes).padStart(2, "0");
        document.getElementById("seconds").textContent = String(seconds).padStart(2, "0");
      }
      updateCountdown();
      setInterval(updateCountdown, 1000);

      const testimonials = [
        {
          text: "Sekolahnya nyaman, gurunya ramah, dan anak kami semakin disiplin dalam ibadah serta percaya diri dalam belajar.",
          name: "Wali Murid Kelas VIII"
        },
        {
          text: "Saya senang belajar di sini karena teman-temannya baik, guru mendampingi, dan kegiatan sekolahnya menyenangkan.",
          name: "Siswa Kelas VII"
        },
        {
          text: "Program keislaman dan pembinaan karakter sangat terasa. Anak tidak hanya belajar pelajaran, tetapi juga adab.",
          name: "Wali Murid Kelas IX"
        }
      ];
      let testimonialIndex = 0;
      function renderTestimonial() {
        document.getElementById("testimonialText").textContent = testimonials[testimonialIndex].text;
        document.getElementById("testimonialName").textContent = testimonials[testimonialIndex].name;
      }
      document.getElementById("prevTestimonial").addEventListener("click", () => {
        testimonialIndex = (testimonialIndex - 1 + testimonials.length) % testimonials.length;
        renderTestimonial();
      });
      document.getElementById("nextTestimonial").addEventListener("click", () => {
        testimonialIndex = (testimonialIndex + 1) % testimonials.length;
        renderTestimonial();
      });

      document.querySelectorAll(".faqBtn").forEach(btn => {
        btn.addEventListener("click", () => {
          const answer = document.getElementById("faqAnswer");
          answer.textContent = btn.dataset.answer;
          answer.classList.remove("hidden");
        });
      });

      document.getElementById("downloadBtn").addEventListener("click", () => {
        const content = "Brosur PPDB SMP Muhammadiyah 5 Ngupit\n\nPendidikan Islami Modern\nProgram: Tahfidz, Teknologi, English Program, Kegiatan Keislaman\nKontak: 0812-0000-0000";
        const blob = new Blob([content], { type: "text/plain" });
        const url = URL.createObjectURL(blob);
        const a = document.createElement("a");
        a.href = url;
        a.download = "brosur-ppdb-smp-muhammadiyah-5-ngupit.txt";
        document.body.appendChild(a);
        a.click();
        a.remove();
        URL.revokeObjectURL(url);

        const toast = document.getElementById("toast");
        toast.classList.add("show");
        setTimeout(() => toast.classList.remove("show"), 2600);
      });

      document.getElementById("contactForm").addEventListener("submit", (event) => {
        event.preventDefault();
        const formMessage = document.getElementById("formMessage");
        const name = document.getElementById("name").value.trim();
        formMessage.textContent = `Terima kasih, ${name}. Pesan Anda berhasil disiapkan. Silakan lanjutkan komunikasi melalui WhatsApp sekolah untuk respons cepat.`;
        formMessage.classList.remove("hidden");
        event.target.reset();
      });

      const visitor = document.getElementById("visitorCount");
      let number = 12480;
      setInterval(() => {
        number += Math.floor(Math.random() * 3);
        visitor.textContent = number.toLocaleString("id-ID");
      }, 5000);
    });
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9fe10040113cfdce',t:'MTc3OTE3MTY4MS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
