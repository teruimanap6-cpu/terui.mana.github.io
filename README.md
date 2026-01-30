<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>照井 茉奈 | macaron 代表 / ピュアプル ファウンダー</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;700&display=swap');
        body { font-family: 'Noto Sans JP', sans-serif; }
        .hero-gradient { background: linear-gradient(135deg, #fdf2f8 0%, #fce7f3 100%); }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- Header -->
    <header class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-pink-100">
        <div class="max-w-5xl mx-auto px-6 h-16 flex items-center justify-between">
            <div class="text-xl font-bold text-pink-500">macaron</div>
            <nav class="hidden md:flex space-x-8 text-sm font-medium">
                <a href="#about" class="hover:text-pink-500 transition">About</a>
                <a href="#projects" class="hover:text-pink-500 transition">Projects</a>
                <a href="#contact" class="hover:text-pink-500 transition">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-gradient py-20 px-6">
        <div class="max-w-4xl mx-auto text-center">
            <span class="inline-block px-4 py-1.5 mb-6 text-xs font-semibold tracking-widest text-pink-600 uppercase bg-pink-100 rounded-full">Educational Support</span>
            <h1 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">
                学ぶ楽しさを、<br class="md:hidden">すべての子どもに。
            </h1>
            <p class="text-lg text-slate-600 mb-8 max-w-2xl mx-auto leading-relaxed">
                東北大学教育学部での学びと起業経験を活かし、中高生の「やりたい」を形にする探究学習支援を行っています。
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#contact" class="px-8 py-3 bg-pink-500 text-white rounded-full font-bold hover:bg-pink-600 transition shadow-lg shadow-pink-200 text-center">お問い合わせ</a>
                <a href="#projects" class="px-8 py-3 bg-white text-pink-500 border border-pink-200 rounded-full font-bold hover:bg-pink-50 transition text-center">プロジェクトを見る</a>
            </div>
        </div>
    </section>

    <!-- Profile -->
    <section id="about" class="py-20 px-6 bg-white">
        <div class="max-w-4xl mx-auto">
            <div class="flex flex-col md:flex-row gap-12 items-center">
                <div class="w-48 h-48 rounded-2xl bg-pink-100 flex-shrink-0 flex items-center justify-center overflow-hidden">
                    <span class="text-pink-300 text-5xl">Mana</span>
                </div>
                <div>
                    <h2 class="text-3xl font-bold mb-2">照井 茉奈 <span class="text-lg font-normal text-slate-400 ml-2">Mana Terui</span></h2>
                    <p class="text-pink-500 font-bold mb-4">macaron 代表 / ピュアプル 代表</p>
                    <p class="text-slate-600 leading-relaxed mb-6">
                        東北大学教育学部在籍。教育評価・学習科学を専攻。
                        高校時代の経験から、学校教育における「探究学習」の質の向上と、生徒一人ひとりの興味関心に寄り添う環境の必要性を感じ、個人事業「macaron」を開業。
                        ビジネスコンテストでの受賞を機に、伴走型学習支援プロジェクト「ピュアプル」を立ち上げ。
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm">
                        <div class="flex items-center space-x-2">
                            <div class="w-2 h-2 bg-pink-400 rounded-full"></div>
                            <span>教育学部 教育評価研究</span>
                        </div>
                        <div class="flex items-center space-x-2">
                            <div class="w-2 h-2 bg-pink-400 rounded-full"></div>
                            <span>学習支援AI「Lumii」企画</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="py-20 px-6 bg-slate-50">
        <div class="max-w-5xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold mb-4">主要プロジェクト</h2>
                <p class="text-slate-500">教育の現場で展開している主な活動です</p>
            </div>
            <div class="grid md:grid-cols-2 gap-8">
                <!-- Purepull -->
                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-blue-100 rounded-xl mb-6 flex items-center justify-center">
                        <svg class="w-6 h-6 text-blue-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">ピュアプル</h3>
                    <p class="text-slate-500 text-sm mb-4 italic">探究伴走プロジェクト</p>
                    <p class="text-slate-600 text-sm leading-relaxed mb-6">
                        中高生が社会の課題に対して自らアクションを起こすプロセスをサポート。ビジコン出場経験を活かし、アイデアの具体化から実装までを伴走します。
                    </p>
                    <ul class="text-xs text-slate-400 space-y-2">
                        <li>・アイデア創出ワークショップの開催</li>
                        <li>・個別メンタリング</li>
                        <li>・外部ネットワークとの接続支援</li>
                    </ul>
                </div>

                <!-- Lumii -->
                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-purple-100 rounded-xl mb-6 flex items-center justify-center">
                        <svg class="w-6 h-6 text-purple-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.344-6.656l.707.707m2.834 2.834C5.677 10.29 5 12.06 5 14c0 3.866 3.134 7 7 7s7-3.134 7-7c0-1.94-.677-3.71-1.879-5.121m-7.121-1.879A3 3 0 1112 4a3 3 0 01.445 5.969"/></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Lumii</h3>
                    <p class="text-slate-500 text-sm mb-4 italic">学習支援AIアシスタント</p>
                    <p class="text-slate-600 text-sm leading-relaxed mb-6">
                        生成AIを活用し、生徒の学習過程を見守るツール。生徒の「関心」を見つけ出し、教師の負担軽減と学習効果の向上を両立します。https://lumii-light-guide.lovable.app/
                    </p>
                    <ul class="text-xs text-slate-400 space-y-2">
                        <li>・現在企画中</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Contact -->
    <footer id="contact" class="bg-slate-900 text-white py-16 px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8 text-pink-400">Contact</h2>
            <p class="mb-8 text-slate-400">講演・ワークショップ・伴走支援のご依頼など、お気軽にご連絡ください。</p>
            <div class="inline-block bg-slate-800 p-6 rounded-2xl border border-slate-700">
                <p class="text-sm text-slate-400 mb-2">Email</p>
                <p class="text-lg font-bold">terui.mana.p6@dc.tohoku.ac.jp</p>
                <p class="text-xs text-slate-500 mt-4">個人事業主：macaron 照井 茉奈</p>
            </div>
            <div class="mt-12 pt-8 border-t border-slate-800 text-slate-500 text-xs">
                &copy; 2024 macaron. All rights reserved.
            </div>
        </div>
    </footer>

</body>
</html>
