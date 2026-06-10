# Portofolio-ku-
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Portfolio Profesional</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 antialiased selection:bg-blue-500 selection:text-white">

    <nav class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-200/80">
        <div class="max-w-4xl mx-auto px-6 h-16 flex justify-between items-center">
            <span class="text-lg font-bold tracking-tight text-slate-900">Portfolio<span class="text-blue-600">.</span></span>
            <div class="flex space-x-6 text-sm font-medium text-slate-600">
                <a href="#filosofi" class="hover:text-blue-600 transition-colors">Filosofi</a>
                <a href="#artefak" class="hover:text-blue-600 transition-colors">Artefak</a>
                <a href="#kontak" class="hover:text-blue-600 transition-colors">Kontak</a>
            </div>
        </div>
    </nav>

    <section class="max-w-4xl mx-auto px-6 pt-20 pb-16">
        <div class="space-y-4 max-w-2xl">
            <span class="inline-flex items-center gap-1.5 py-1 px-3 rounded-full text-xs font-medium bg-blue-50 text-blue-700 border border-blue-200">
                Teacher Candidate & Educator
            </span>
            <h1 class="text-4xl font-extrabold tracking-tight text-slate-900 sm:text-5xl leading-tight">
                Menjembatani Teori Pedagogi dengan <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-indigo-600">Praktik Nyata</span>
            </h1>
            <p class="text-base text-slate-600 leading-relaxed pt-2">
                Selamat datang di ruang portofolio digital saya. Di sini, saya mendokumentasikan sintesis pemikiran, rancangan pembelajaran berbasis aktivitas, serta refleksi kritis atas implementasi instruksional di lapangan.
            </p>
        </div>
    </section>

    <section id="filosofi" class="max-w-4xl mx-auto px-6 py-12 border-t border-slate-200">
        <h2 class="text-xl font-bold tracking-tight text-slate-900 mb-6">Prinsip & Metodologi Kerja</h2>
        <div class="grid gap-6 md:grid-cols-2">
            <div class="bg-white border border-slate-200 p-6 rounded-2xl shadow-xs">
                <div class="w-10 h-10 rounded-lg bg-blue-50 flex items-center justify-center text-blue-600 font-bold mb-4">UbD</div>
                <h3 class="font-semibold text-slate-900 mb-2">Backward Design</h3>
                <p class="text-sm text-slate-600 leading-relaxed">
                    Merancang pembelajaran dengan menetapkan tujuan akhir dan bukti asesmen terlebih dahulu, memastikan setiap aktivitas instruksional berjalan terarah dan bermakna.
                </p>
            </div>
            <div class="bg-white border border-slate-200 p-6 rounded-2xl shadow-xs">
                <div class="w-10 h-10 rounded-lg bg-indigo-50 flex items-center justify-center text-indigo-600 font-bold mb-4">DI</div>
                <h3 class="font-semibold text-slate-900 mb-2">Differentiated Instruction</h3>
                <p class="text-sm text-slate-600 leading-relaxed">
                    Mengakomodasi keberagaman karakteristik, kesiapan, dan gaya belajar individu melalui diferensiasi konten, proses, maupun produk pembelajaran.
                </p>
            </div>
        </div>
    </section>

    <section id="artefak" class="max-w-4xl mx-auto px-6 py-12 border-t border-slate-200">
        <div class="flex justify-between items-center mb-8">
            <h2 class="text-xl font-bold tracking-tight text-slate-900">Galeri Artefak & Studi Kasus</h2>
            <span class="text-xs text-slate-500 font-medium">Repository Aktif</span>
        </div>
        
        <div class="space-y-6">
            <div class="group bg-white border border-slate-200 rounded-2xl p-6 hover:border-blue-300 hover:shadow-xs transition-all duration-200">
                <div class="flex justify-between items-start gap-4">
                    <div class="space-y-2">
                        <span class="text-[10px] font-bold tracking-wider uppercase text-blue-600 bg-blue-50 px-2 py-0.5 rounded-md">Desain Instruksional</span>
                        <h3 class="text-lg font-bold text-slate-900 group-hover:text-blue-600 transition-colors">
                            Modul Geometri Berbasis Aktivitas Konkret
                        </h3>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Rancangan pelaksanaan pembelajaran pengukuran sudut untuk kelas V SD yang memprioritaskan pemahaman konseptual mendalam (deep learning) daripada hafalan prosedural.
                        </p>
                    </div>
                </div>
            </div>

            <div class="group bg-white border border-slate-200 rounded-2xl p-6 hover:border-indigo-300 hover:shadow-xs transition-all duration-200">
                <div class="flex justify-between items-start gap-4">
                    <div class="space-y-2">
                        <span class="text-[10px] font-bold tracking-wider uppercase text-indigo-600 bg-indigo-50 px-2 py-0.5 rounded-md">Teknologi Pendidikan</span>
                        <h3 class="text-lg font-bold text-slate-900 group-hover:text-indigo-600 transition-colors">
                            Aplikasi Manajer Profil Karakteristik Siswa
                        </h3>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Pengembangan alat bantu digital berbasis web untuk memetakan kepribadian dan profil belajar siswa guna mendukung efektivitas penataan pembelajaran berdiferensiasi.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer id="kontak" class="bg-slate-950 text-slate-400 mt-20 border-t border-slate-900">
        <div class="max-w-4xl mx-auto px-6 py-12 flex flex-col md:flex-row justify-between items-center gap-6 text-sm">
            <div class="space-y-1 text-center md:text-left">
                <p class="text-white font-medium">E-Portfolio Digital</p>
                <p class="text-xs text-slate-500">Mendokumentasikan perjalanan profesional secara kritis.</p>
            </div>
            <div class="flex space-x-6 text-slate-400">
                <a href="#" class="hover:text-white transition-colors">GitHub</a>
                <a href="#" class="hover:text-white transition-colors">Email</a>
            </div>
        </div>
        <div class="max-w-4xl mx-auto px-6 py-4 border-t border-slate-900 text-center text-xs text-slate-600">
            &copy; 2026. Hak Cipta Dilindungi.
        </div>
    </footer>

</body>
</html>
