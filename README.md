<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>合同会社KALEIDO | 生成AI法人研修で経費削減×生産性向上</title>
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta name="description" content="中小企業向け生成AI法人研修を提供する合同会社KALEIDO。ChatGPTやAI活用研修で業務効率化を実現し、経費削減と生産性向上をサポートします。">
  <!-- より最新のTailwind CSS -->
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <!-- FontAwesome -->
  <link href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.5.2/css/all.min.css" rel="stylesheet">
  <!-- Googleフォント - より洗練されたセット -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Poppins:wght@500;600;700&display=swap" rel="stylesheet">
  <!-- Chart.js -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.3/dist/chart.umd.min.js"></script>
  <!-- AOS (Animate On Scroll) -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    :root {
      --primary: #0284c7;
      --primary-light: #0ea5e9;
      --primary-dark: #0369a1;
      --accent: #7e22ce;
      --accent-light: #a855f7;
    }
    
    html {
      scroll-behavior: smooth;
      scroll-padding-top: 80px;
    }
    
    body {
      font-family: 'Inter', sans-serif;
      color: #1e293b;
      line-height: 1.7;
      background-color: #f8fafc;
    }
    
    .font-display {
      font-family: 'Poppins', sans-serif;
    }
    
    .hero-bg {
      background: linear-gradient(135deg, rgba(3,105,161,0.90) 0%, rgba(3,105,161,0.80) 100%), 
                  url('https://images.unsplash.com/photo-1593720219276-0b1eacd0aef4?auto=format&fit=crop&w=2000&q=80') center/cover no-repeat;
      position: relative;
    }
    
    .hero-bg::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI1NiIgaGVpZ2h0PSIxMDAiPgo8cmVjdCB3aWR0aD0iNTYiIGhlaWdodD0iMTAwIiBmaWxsPSIjMDAwMDAwIiBmaWxsLW9wYWNpdHk9IjAuMDIiPjwvcmVjdD4KPHBhdGggZD0iTTI4IDY2TDAgNTBMMCAxNkwyOCAwTDU2IDE2TDU2IDUwTDI4IDY2TDI4IDEwMCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmZmZmIiBzdHJva2Utb3BhY2l0eT0iMC4wNSIgc3Ryb2tlLXdpZHRoPSIyIj48L3BhdGg+CjxwYXRoIGQ9Ik0yOCAwTDI4IDY2TDAgNTBMMCA1MEwwIDE2TDAgMTZMMjggMCIgZmlsbD0iI2ZmZmZmZiIgZmlsbC1vcGFjaXR5PSIwLjAyIj48L3BhdGg+CjxwYXRoIGQ9Ik0yOCAwTDI4IDY2TDU2IDUwTDU2IDUwTDU2IDE2TDU2IDE2TDI4IDAiIGZpbGw9IiNmZmZmZmYiIGZpbGwtb3BhY2l0eT0iMC4wMiI+PC9wYXRoPgo8L3N2Zz4=');
      opacity: 0.4;
      z-index: 1;
      pointer-events: none;
    }
    
    .hero-content {
      position: relative;
      z-index: 2;
    }
    
    .section-title {
      font-family: 'Poppins', sans-serif;
      letter-spacing: 0.025em;
      font-weight: 700;
      position: relative;
      display: inline-block;
    }
    
    .section-title::after {
      content: '';
      position: absolute;
      bottom: -6px;
      left: 0;
      width: 60px;
      height: 3px;
      background: var(--primary);
      border-radius: 2px;
    }
    
    .btn-primary {
      background-image: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
      border-radius: 9999px;
      padding: 0.75rem 2rem;
      font-weight: 600;
      color: white;
      transition: all 0.3s ease;
      position: relative;
      overflow: hidden;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 10px 15px -3px rgba(3,105,161,0.1), 0 4px 6px -4px rgba(3,105,161,0.1);
    }
    
    .btn-primary:hover {
      transform: translateY(-2px);
      box-shadow: 0 20px 25px -5px rgba(3,105,161,0.1), 0 8px 10px -6px rgba(3,105,161,0.1);
    }
    
    .btn-primary::after {
      content: '';
      position: absolute;
      width: 30px;
      height: 300px;
      background: rgba(255,255,255,0.2);
      transform: rotate(45deg) translate(-250px, -120px);
      transition: all 0.3s ease-in-out;
    }
    
    .btn-primary:hover::after {
      transform: rotate(45deg) translate(450px, 120px);
    }
    
    .card {
      border-radius: 1rem;
      overflow: hidden;
      transition: all 0.3s ease;
      background: white;
      box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.1);
    }
    
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
    }
    
    .card-accent {
      position: relative;
      overflow: hidden;
    }
    
    .card-accent::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 4px;
      height: 100%;
    }
    
    .card-accent.primary::before {
      background: var(--primary);
    }
    
    .card-accent.secondary::before {
      background: var(--primary-light);
    }
    
    .card-accent.accent::before {
      background: var(--accent);
    }
    
    .card-accent.accent-light::before {
      background: var(--accent-light);
    }
    
    .feature-icon {
      width: 54px;
      height: 54px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 1rem;
      background: linear-gradient(135deg, rgba(3,105,161,0.1) 0%, rgba(3,105,161,0.2) 100%);
      color: var(--primary);
    }
    
    .sticky-header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 100;
      transition: all 0.3s ease;
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
    }
    
    .sticky-header.scrolled {
      background-color: rgba(255, 255, 255, 0.95);
      box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.1);
    }
    
    /* ハンバーガーメニュー */
    .mobile-menu-btn {
      display: none;
      flex-direction: column;
      justify-content: space-between;
      width: 30px;
      height: 21px;
      cursor: pointer;
      z-index: 200;
    }
    
    .mobile-menu-btn span {
      display: block;
      height: 3px;
      width: 100%;
      background-color: var(--primary-dark);
      border-radius: 3px;
      transition: all 0.3s ease;
    }
    
    .mobile-menu-btn.active span:nth-child(1) {
      transform: translateY(9px) rotate(45deg);
    }
    
    .mobile-menu-btn.active span:nth-child(2) {
      opacity: 0;
    }
    
    .mobile-menu-btn.active span:nth-child(3) {
      transform: translateY(-9px) rotate(-45deg);
    }
    
    .mobile-menu {
      position: fixed;
      top: 0;
      right: -100%;
      width: 250px;
      height: 100vh;
      background-color: white;
      z-index: 150;
      padding: 6rem 2rem 2rem;
      box-shadow: -5px 0 15px rgba(0, 0, 0, 0.1);
      transition: right 0.3s ease;
    }
    
    .mobile-menu.active {
      right: 0;
    }
    
    .mobile-menu a {
      display: block;
      padding: 0.75rem 0;
      border-bottom: 1px solid rgba(3,105,161,0.1);
      font-weight: 500;
      color: var(--primary-dark);
    }
    
    /* スクロールバー装飾 */
    ::-webkit-scrollbar {
      width: 8px;
      height: 8px;
    }
    
    ::-webkit-scrollbar-track {
      background: #f1f5f9;
    }
    
    ::-webkit-scrollbar-thumb {
      background: #94a3b8;
      border-radius: 4px;
    }
    
    ::-webkit-scrollbar-thumb:hover {
      background: #64748b;
    }
    
    /* アニメーション */
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    .animate-fadeInUp {
      animation: fadeInUp 0.8s ease forwards;
    }
    
    .delay-100 { animation-delay: 0.1s; }
    .delay-200 { animation-delay: 0.2s; }
    .delay-300 { animation-delay: 0.3s; }
    .delay-400 { animation-delay: 0.4s; }
    
    /* メディアクエリ */
    @media (max-width: 767px) {
      .desktop-menu {
        display: none;
      }
      
      .mobile-menu-btn {
        display: flex;
      }
    }
    
    @media print {
      body, html { 
        background: #fff !important;
      }
      
      .hero-bg {
        background-blend-mode: normal;
        -webkit-print-color-adjust: exact;
        print-color-adjust: exact;
      }
    }
  </style>
</head>
<body class="antialiased">

<!-- Header -->
<header class="sticky-header py-4 px-6 md:px-10 flex items-center justify-between">
  <div class="flex items-center">
    <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=facearea&w=96&h=96&q=80" alt="KALEIDO Logo" class="w-12 h-12 rounded-full shadow-lg mr-4">
    <div>
      <span class="text-xl md:text-2xl font-bold tracking-tight text-gray-900 font-display">合同会社<span class="text-sky-600">KALEIDO</span></span>
      <p class="text-xs text-gray-500 hidden md:block">生成AI研修のプロフェッショナル</p>
    </div>
  </div>
  
  <nav class="desktop-menu text-gray-800 font-medium flex space-x-8">
    <a href="#about" class="relative group py-2">
      <span>KALEIDOについて</span>
      <span class="absolute bottom-0 left-0 w-0 h-0.5 bg-sky-500 group-hover:w-full transition-all duration-300"></span>
    </a>
    <a href="#services" class="relative group py-2">
      <span>研修内容</span>
      <span class="absolute bottom-0 left-0 w-0 h-0.5 bg-sky-500 group-hover:w-full transition-all duration-300"></span>
    </a>
    <a href="#merit" class="relative group py-2">
      <span>導入のメリット</span>
      <span class="absolute bottom-0 left-0 w-0 h-0.5 bg-sky-500 group-hover:w-full transition-all duration-300"></span>
    </a>
    <a href="#why" class="relative group py-2">
      <span>選ばれる理由</span>
      <span class="absolute bottom-0 left-0 w-0 h-0.5 bg-sky-500 group-hover:w-full transition-all duration-300"></span>
    </a>
    <a href="#contact" class="ml-4 py-2 px-5 bg-sky-600 hover:bg-sky-700 text-white font-medium rounded-full transition duration-300 shadow-md hover:shadow-lg">
      お問い合わせ
    </a>
  </nav>
  
  <!-- モバイルメニューボタン -->
  <div class="mobile-menu-btn">
    <span></span>
    <span></span>
    <span></span>
  </div>
  
  <!-- モバイルメニュー -->
  <div class="mobile-menu">
    <a href="#about">KALEIDOについて</a>
    <a href="#services">研修内容</a>
    <a href="#merit">導入のメリット</a>
    <a href="#why">選ばれる理由</a>
    <a href="#contact">お問い合わせ</a>
  </div>
</header>

<!-- Hero Section -->
<section class="hero-bg min-h-screen flex items-center justify-center relative pt-28 pb-16">
  <div class="container mx-auto hero-content flex flex-col md:flex-row items-center justify-between px-6 md:px-16">
    <div class="max-w-xl z-10" data-aos="fade-right" data-aos-duration="1000">
      <div class="inline-block px-4 py-1 bg-white bg-opacity-20 backdrop-filter backdrop-blur-sm text-white rounded-full mb-4 animate-fadeInUp">
        <i class="fa-solid fa-bolt mr-2"></i> AI研修のプロフェッショナルチーム
      </div>
      <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-6 font-display tracking-tight leading-tight animate-fadeInUp delay-100">
        <span class="text-sky-300 inline-block">生成AI法人研修</span>で<br>
        経費削減<span class="mx-2 text-sky-300">×</span>生産性向上を実現
      </h1>
      <p class="text-lg md:text-xl text-blue-100 mb-8 max-w-lg animate-fadeInUp delay-200">
        生成AIとChatGPTで、中小企業の業務を効率化。<br>
        DX推進の新常識、組織力を最大化する未来型ビジネスへ。
      </p>
      <div class="animate-fadeInUp delay-300">
        <a href="#contact" class="btn-primary">
          <i class="fa-solid fa-paper-plane mr-2"></i> 無料相談はこちら
        </a>
      </div>
      <div class="flex items-center mt-8 text-white animate-fadeInUp delay-400">
        <div class="flex -space-x-2">
          <img src="https://randomuser.me/api/portraits/women/44.jpg" class="w-10 h-10 rounded-full border-2 border-white">
          <img src="https://randomuser.me/api/portraits/men/47.jpg" class="w-10 h-10 rounded-full border-2 border-white">
          <img src="https://randomuser.me/api/portraits/women/63.jpg" class="w-10 h-10 rounded-full border-2 border-white">
        </div>
        <div class="ml-4">
          <div class="text-sm opacity-90">導入企業様からの評価</div>
          <div class="flex text-yellow-300">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <span class="ml-1 text-white font-medium">4.9/5.0</span>
          </div>
        </div>
      </div>
    </div>
    <div class="mt-12 md:mt-0 md:ml-14 max-w-lg w-full" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="300">
      <div class="relative">
        <!-- Main Visual Image (high-impact) with floating elements -->
        <img src="https://images.unsplash.com/photo-1581090700227-1e37b190418e?auto=format&fit=crop&w=600&q=80" alt="生成AIのイメージ" class="rounded-2xl shadow-2xl border-8 border-white w-full object-cover">
        
        <!-- Floating elements -->
        <div class="absolute -top-6 -left-6 bg-white rounded-lg shadow-lg p-4 flex items-center animate-pulse" style="animation-duration: 3s;">
          <i class="fa-solid fa-chart-line text-green-500 text-xl mr-2"></i>
          <div>
            <div class="text-xs text-gray-500">業務効率</div>
            <div class="text-lg font-bold text-green-600">+35%</div>
          </div>
        </div>
        
        <div class="absolute -bottom-6 -right-6 bg-white rounded-lg shadow-lg p-4 flex items-center animate-pulse" style="animation-duration: 4s;">
          <i class="fa-solid fa-sack-dollar text-blue-500 text-xl mr-2"></i>
          <div>
            <div class="text-xs text-gray-500">コスト削減</div>
            <div class="text-lg font-bold text-blue-600">25%</div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="absolute bottom-6 left-1/2 transform -translate-x-1/2 text-white opacity-60 text-xs z-10">
    <i class="fa-solid fa-angle-down animate-bounce"></i> スクロールして詳細を見る
  </div>
</section>

<!-- About & Needs Section -->
<section class="py-20 bg-white px-4 md:px-0" id="about">
  <div class="max-w-4xl mx-auto">
    <div class="text-center mb-16" data-aos="fade-up">
      <h2 class="text-3xl md:text-4xl font-bold font-display mb-5 text-gray-900">
        生成AI研修、<span class="text-sky-600">"必要不可欠"</span>な時代へ
      </h2>
      <div class="h-1 w-24 bg-sky-500 mx-auto rounded-full mb-8"></div>
      <p class="text-lg md:text-xl text-gray-700 max-w-3xl mx-auto">
        世界中でAI活用が加速する今、<span class="font-semibold text-sky-600">中小企業の生成AI導入率はわずか15%※</span>。<br>
        しかし、AIを活用する企業は劇的に業務効率を向上させています。
      </p>
      <p class="text-gray-600 mt-3">
        <span class="font-semibold text-sky-500">2024年調査では、AI導入企業は平均25%以上の経費削減と業務時間短縮を実現</span>しています。
      </p>
      <p class="text-gray-500 text-sm mt-3">※独自調査・総務省情報通信統計等より</p>
    </div>
    
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-10">
      <div class="card card-accent primary p-8" data-aos="fade-up" data-aos-delay="100">
        <div class="feature-icon">
          <i class="fa-solid fa-rocket text-2xl"></i>
        </div>
        <h3 class="font-bold text-xl mb-3 text-sky-700">急速な需要拡大</h3>
        <p class="text-gray-600">
          AIがもたらす競争力強化。専門知識ゼロからでも"現場で使える"実践力へ。非導入企業は急速に競争力を失っています。
        </p>
      </div>
      
      <div class="card card-accent secondary p-8" data-aos="fade-up" data-aos-delay="200">
        <div class="feature-icon">
          <i class="fa-solid fa-chart-line text-2xl"></i>
        </div>
        <h3 class="font-bold text-xl mb-3 text-sky-700">25%超の経費削減※</h3>
        <p class="text-gray-600">
          AI導入企業の<span class="font-semibold">作業効率化・人件費削減</span>は驚くべき効果を発揮。（※2024年 業界平均）数億円規模の投資対効果も。
        </p>
      </div>
      
      <div class="card card-accent accent p-8" data-aos="fade-up" data-aos-delay="300">
        <div class="feature-icon">
          <i class="fa-solid fa-bolt text-2xl"></i>
        </div>
        <h3 class="font-bold text-xl mb-3 text-purple-700">組織変革の第一歩</h3>
        <p class="text-gray-600">
          短期間で"全員がAIを使える"企業に進化。中小企業こそAI活用で大企業と対等に戦える時代です。
        </p>
      </div>
    </div>
  </div>
</section>

<!-- Simple Data Visualization: AI活用での経費削減例 -->
<section class="py-20 px-4 bg-gradient-to-b from-gray-50 to-white" data-aos="fade-up">
  <div class="max-w-5xl mx-auto">
    <div class="text-center mb-12">
      <span class="px-4 py-1 bg-sky-100 text-sky-800 font-medium rounded-full text-sm">費用対効果</span>
      <h2 class="text-3xl font-bold font-display mt-4 mb-5 text-gray-900">
        導入企業での<span class="text-sky-600">経費削減シミュレーション</span>
      </h2>
      <p class="text-gray-600 max-w-2xl mx-auto">
        例えば月50万円の人件費なら、AI活用だけで平均12万円削減。<br>
        3年で<span class="font-semibold text-sky-700">432万円のコストカット</span>も実現可能です。
      </p>
    </div>
    
    <div class="flex flex-col md:flex-row items-center justify-center gap-8">
      <div class="w-full md:w-1/2 bg-white p-8 rounded-2xl shadow-lg">
        <canvas id="costChart" height="300"></canvas>
      </div>
      <div class="w-full md:w-1/2 space-y-6">
        <div class="bg-white rounded-xl p-5 border-l-4 border-sky-500 shadow-md">
          <div class="flex items-center">
            <i class="fa-solid fa-money-bill-wave text-xl text-sky-500 mr-3"></i>
            <h4 class="font-bold text-lg">月間経費削減額</h4>
          </div>
          <div class="ml-9 mt-1">
            <div class="text-3xl font-bold text-sky-600">12万円</div>
            <div class="text-sm text-gray-500">平均削減率 24%</div>
          </div>
        </div>
        
        <div class="bg-white rounded-xl p-5 border-l-4 border-purple-500 shadow-md">
          <div class="flex items-center">
            <i class="fa-solid fa-clock text-xl text-purple-500 mr-3"></i>
            <h4 class="font-bold text-lg">1日あたり時間削減</h4>
          </div>
          <div class="ml-9 mt-1">
            <div class="text-3xl font-bold text-purple-600">1.8時間</div>
            <div class="text-sm text-gray-500">月間 約40時間</div>
          </div>
        </div>
        
        <div class="bg-white rounded-xl p-5 border-l-4 border-green-500 shadow-md">
          <div class="flex items-center">
            <i class="fa-solid fa-calculator text-xl text-green-500 mr-3"></i>
            <h4 class="font-bold text-lg">3年間の投資対効果</h4>
          </div>
          <div class="ml-9 mt-1">
            <div class="text-3xl font-bold text-green-600">432万円</div>
            <div class="text-sm text-gray-500">ROI 350%超</div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <script>
    const ctx = document.getElementById('costChart').getContext('2d');
    new Chart(ctx, {
      type: 'bar',
      data: {
        labels: ['導入前', 'AI導入後'],
        datasets: [{
          label: function(tooltipItem) {
                return tooltipItem.dataset.label + ': ' + tooltipItem.raw + '万円';
              }
            }
          }
        },
        scales: {
          y: {
            min: 0,
            max: 60,
            ticks: {
              callback: v => v + '万'
            },
            grid: { color: 'rgba(0,0,0,0.05)' }
          },
          x: {
            grid: { display: false }
          }
        },
        responsive: true,
        maintainAspectRatio: false
      }
    });
  </script>
</section>

<!-- Training Services -->
<section class="py-20 bg-white px-4 md:px-0" id="services">
  <div class="max-w-6xl mx-auto">
    <div class="text-center mb-14" data-aos="fade-up">
      <span class="px-4 py-1 bg-purple-100 text-purple-800 font-medium rounded-full text-sm">研修プログラム</span>
      <h2 class="text-3xl md:text-4xl font-bold font-display mt-4 mb-5">
        トッププロの<span class="text-sky-600">生成AI・ChatGPT研修</span>ラインアップ
      </h2>
      <p class="text-gray-600 max-w-3xl mx-auto">
        経験豊富な講師陣が、最新のAI技術を実践的なスキルとして定着させる研修プログラムをご用意しています。
      </p>
    </div>
    
    <div class="relative">
      <!-- 装飾用の背景要素 -->
      <div class="absolute inset-0 bg-gradient-to-r from-sky-50 via-transparent to-purple-50 rounded-3xl -z-10 transform rotate-1"></div>
      
      <!-- 研修カード -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- 1 -->
        <div class="card p-1 group" data-aos="fade-up" data-aos-delay="100">
          <div class="bg-gradient-to-br from-sky-50 to-white p-7 rounded-2xl h-full">
            <div class="flex items-start">
              <div class="rounded-xl bg-sky-100 p-3 text-sky-600 mr-4 group-hover:bg-sky-600 group-hover:text-white transition-colors duration-300">
                <i class="fa-solid fa-brain text-2xl"></i>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-3 text-sky-700">生成AIリテラシー研修（基礎編）</h3>
                <p class="text-gray-600 mb-4">
                  すべての社員に必要なAIの基礎知識から法的リスクまで短時間で効率的に学ぶ入門コースです。
                </p>
                <ul class="space-y-2 mb-5">
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-sky-500 mr-2"></i>
                    AI/ChatGPT・画像生成AIの入門から法律・リスクまで網羅
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-sky-500 mr-2"></i>
                    全社員対象・初心者OK、短時間で要点を習得
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-sky-500 mr-2"></i>
                    講義メイン、グループワークなしだから効率的
                  </li>
                </ul>
                <div class="flex items-center mt-auto text-sm text-sky-600 font-medium">
                  <i class="fa-solid fa-clock mr-2"></i>3時間/半日コース
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <!-- 2 -->
        <div class="card p-1 group" data-aos="fade-up" data-aos-delay="200">
          <div class="bg-gradient-to-br from-cyan-50 to-white p-7 rounded-2xl h-full">
            <div class="flex items-start">
              <div class="rounded-xl bg-cyan-100 p-3 text-cyan-600 mr-4 group-hover:bg-cyan-600 group-hover:text-white transition-colors duration-300">
                <i class="fa-solid fa-comments text-2xl"></i>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-3 text-cyan-700">ChatGPTビジネス活用講座（1日集中）</h3>
                <p class="text-gray-600 mb-4">
                  実際の業務へのAI導入を重視した、より実践的な応用研修です。
                </p>
                <ul class="space-y-2 mb-5">
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-cyan-500 mr-2"></i>
                    経営層/管理職/実務者向け、業務組込の応用スキル
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-cyan-500 mr-2"></i>
                    実例やユースケースの演習・ディスカッション主体
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-cyan-500 mr-2"></i>
                    課題発見→現場改善へ即応用できるカリキュラム
                  </li>
                </ul>
                <div class="flex items-center mt-auto text-sm text-cyan-600 font-medium">
                  <i class="fa-solid fa-clock mr-2"></i>1日コース（6～7時間）
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <!-- 3 -->
        <div class="card p-1 group" data-aos="fade-up" data-aos-delay="300">
          <div class="bg-gradient-to-br from-fuchsia-50 to-white p-7 rounded-2xl h-full relative">
            <div class="absolute -top-3 -right-3 bg-gradient-to-r from-pink-500 to-fuchsia-500 text-white text-xs px-4 py-1.5 rounded-full shadow-lg font-bold">
              <i class="fa-solid fa-trophy mr-1"></i> 助成金対象
            </div>
            <div class="flex items-start">
              <div class="rounded-xl bg-fuchsia-100 p-3 text-fuchsia-600 mr-4 group-hover:bg-fuchsia-600 group-hover:text-white transition-colors duration-300">
                <i class="fa-solid fa-flask-vial text-2xl"></i>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-3 text-fuchsia-700">生成AI総合研修（2日間）</h3>
                <p class="text-gray-600 mb-4">
                  AI導入リーダーを育成するための総合的な研修プログラムです。
                </p>
                <ul class="space-y-2 mb-5">
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-fuchsia-500 mr-2"></i>
                    AI導入リーダー/DX推進層向けの総合コース
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-fuchsia-500 mr-2"></i>
                    ChatGPT応用/Claudeや他モデルも解説
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-fuchsia-500 mr-2"></i>
                    ワークショップ形式で課題洗い出し＆プロジェクト策定
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-fuchsia-500 mr-2"></i>
                    人材開発支援助成金＜リスキリング支援＞利用可能
                  </li>
                </ul>
                <div class="flex items-center mt-auto text-sm text-fuchsia-600 font-medium">
                  <i class="fa-solid fa-clock mr-2"></i>2日（計10-12時間）
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <!-- 4 -->
        <div class="card p-1 group" data-aos="fade-up" data-aos-delay="400">
          <div class="bg-gradient-to-br from-blue-50 to-white p-7 rounded-2xl h-full relative">
            <div class="absolute -top-3 -right-3 bg-gradient-to-r from-indigo-500 to-blue-500 text-white text-xs px-4 py-1.5 rounded-full shadow-lg font-bold">
              <i class="fa-solid fa-trophy mr-1"></i> 助成金対象
            </div>
            <div class="flex items-start">
              <div class="rounded-xl bg-blue-100 p-3 text-blue-600 mr-4 group-hover:bg-blue-600 group-hover:text-white transition-colors duration-300">
                <i class="fa-solid fa-handshake text-2xl"></i>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-3 text-blue-700">生成AI導入コンサル＋研修パッケージ</h3>
                <p class="text-gray-600 mb-4">
                  御社の業務に合わせたカスタマイズ型の総合支援プログラムです。
                </p>
                <ul class="space-y-2 mb-5">
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-blue-500 mr-2"></i>
                    現場ヒアリング＆カスタマイズ型研修＋現場導入コンサル
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-blue-500 mr-2"></i>
                    AI基礎～現場課題抽出→社内プロジェクト化
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-blue-500 mr-2"></i>
                    アフターフォロー1ヶ月付、申請サポートも充実
                  </li>
                  <li class="flex items-center text-gray-700">
                    <i class="fa-solid fa-check text-blue-500 mr-2"></i>
                    人材開発支援助成金＜リスキリング支援＞利用可能
                  </li>
                </ul>
                <div class="flex items-center mt-auto text-sm text-blue-600 font-medium">
                  <i class="fa-solid fa-clock mr-2"></i>5h×4日（計15-20時間相当）
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- 導入のメリット -->
<section class="py-20 px-4 bg-gradient-to-b from-white to-sky-50" id="merit">
  <div class="max-w-5xl mx-auto">
    <div class="text-center mb-14" data-aos="fade-up">
      <span class="px-4 py-1 bg-sky-100 text-sky-800 font-medium rounded-full text-sm">ビジネスメリット</span>
      <h2 class="text-3xl md:text-4xl font-bold font-display mt-4 mb-5">
        生成AI導入の<span class="text-sky-600">ビジネスインパクト</span>
      </h2>
      <p class="text-gray-600 max-w-3xl mx-auto">
        AIを戦略的に活用することで、業務効率化だけでなく、組織全体のポテンシャルを最大化します。
      </p>
    </div>
    
    <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
      <div class="relative group" data-aos="fade-up" data-aos-delay="100">
        <!-- 背景装飾 -->
        <div class="absolute inset-0 bg-gradient-to-r from-sky-400 to-cyan-400 rounded-2xl transform group-hover:translate-y-2 transition-transform duration-300 opacity-80"></div>
        
        <!-- カード内容 -->
        <div class="card bg-white p-8 relative z-10 h-full flex flex-col items-center text-center">
          <div class="w-16 h-16 rounded-full bg-sky-100 flex items-center justify-center mb-6">
            <i class="fa-solid fa-laptop-code text-2xl text-sky-600"></i>
          </div>
          <h3 class="text-xl font-bold mb-4 text-sky-700">業務効率化</h3>
          <p class="text-gray-600 flex-grow">
            日常のルーティン業務が自動化され、従業員の負担を軽減。<br>
            <span class="font-medium">残業時間や手作業を最大40%削減</span>し、本来注力すべき創造的な業務に時間を活用できます。
          </p>
          <a href="#contact" class="mt-6 inline-flex items-center text-sky-600 font-medium hover:text-sky-800">
            詳細を相談する <i class="fa-solid fa-arrow-right ml-2"></i>
          </a>
        </div>
      </div>
      
      <div class="relative group" data-aos="fade-up" data-aos-delay="200">
        <!-- 背景装飾 -->
        <div class="absolute inset-0 bg-gradient-to-r from-cyan-400 to-teal-400 rounded-2xl transform group-hover:translate-y-2 transition-transform duration-300 opacity-80"></div>
        
        <!-- カード内容 -->
        <div class="card bg-white p-8 relative z-10 h-full flex flex-col items-center text-center">
          <div class="w-16 h-16 rounded-full bg-cyan-100 flex items-center justify-center mb-6">
            <i class="fa-solid fa-user-shield text-2xl text-cyan-600"></i>
          </div>
          <h3 class="text-xl font-bold mb-4 text-cyan-700">リスク低減</h3>
          <p class="text-gray-600 flex-grow">
            人的ミスやヒューマンエラーを大幅に軽減し、品質向上を実現。<br>
            <span class="font-medium">法的リスクの回避策や適切な活用法</span>についても研修で詳しく解説します。
          </p>
          <a href="#contact" class="mt-6 inline-flex items-center text-cyan-600 font-medium hover:text-cyan-800">
            詳細を相談する <i class="fa-solid fa-arrow-right ml-2"></i>
          </a>
        </div>
      </div>
      
      <div class="relative group" data-aos="fade-up" data-aos-delay="300">
        <!-- 背景装飾 -->
        <div class="absolute inset-0 bg-gradient-to-r from-fuchsia-400 to-purple-400 rounded-2xl transform group-hover:translate-y-2 transition-transform duration-300 opacity-80"></div>
        
        <!-- カード内容 -->
        <div class="card bg-white p-8 relative z-10 h-full flex flex-col items-center text-center">
          <div class="w-16 h-16 rounded-full bg-fuchsia-100 flex items-center justify-center mb-6">
            <i class="fa-solid fa-landmark text-2xl text-fuchsia-600"></i>
          </div>
          <h3 class="text-xl font-bold mb-4 text-fuchsia-700">企業力の底上げ</h3>
          <p class="text-gray-600 flex-grow">
            IT・AIに強い組織文化を醸成し、<span class="font-medium">人材採用力やブランドイメージの向上</span>にも直結。<br>
            時代の最先端を行く企業として差別化できます。
          </p>
          <a href="#contact" class="mt-6 inline-flex items-center text-fuchsia-600 font-medium hover:text-fuchsia-800">
            詳細を相談する <i class="fa-solid fa-arrow-right ml-2"></i>
          </a>
        </div>
      </div>
    </div>
    
    <!-- 追加メリット -->
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mt-10" data-aos="fade-up" data-aos-delay="400">
      <div class="bg-white rounded-xl p-5 shadow flex items-center">
        <div class="rounded-full bg-green-100 p-3 text-green-600 mr-3">
          <i class="fa-solid fa-bolt"></i>
        </div>
        <div>
          <h4 class="font-bold text-gray-800">業務スピード向上</h4>
          <p class="text-sm text-gray-600">作業時間を最大60%短縮</p>
        </div>
      </div>
      
      <div class="bg-white rounded-xl p-5 shadow flex items-center">
        <div class="rounded-full bg-blue-100 p-3 text-blue-600 mr-3">
          <i class="fa-solid fa-lightbulb"></i>
        </div>
        <div>
          <h4 class="font-bold text-gray-800">創造性の向上</h4>
          <p class="text-sm text-gray-600">新しいアイデア創出の活性化</p>
        </div>
      </div>
      
      <div class="bg-white rounded-xl p-5 shadow flex items-center">
        <div class="rounded-full bg-amber-100 p-3 text-amber-600 mr-3">
          <i class="fa-solid fa-users"></i>
        </div>
        <div>
          <h4 class="font-bold text-gray-800">チーム連携強化</h4>
          <p class="text-sm text-gray-600">情報共有と協業の効率化</p>
        </div>
      </div>
      
      <div class="bg-white rounded-xl p-5 shadow flex items-center">
        <div class="rounded-full bg-purple-100 p-3 text-purple-600 mr-3">
          <i class="fa-solid fa-circle-dollar-to-slot"></i>
        </div>
        <div>
          <h4 class="font-bold text-gray-800">コスト削減</h4>
          <p class="text-sm text-gray-600">長期的な経費削減効果</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Why Choose Us -->
<section class="py-20 px-4 bg-white" id="why">
  <div class="max-w-5xl mx-auto">
    <div class="text-center mb-14" data-aos="fade-up">
      <span class="px-4 py-1 bg-indigo-100 text-indigo-800 font-medium rounded-full text-sm">選ばれる理由</span>
      <h2 class="text-3xl md:text-4xl font-bold font-display mt-4 mb-5">
        <span class="text-sky-600">KALEIDO</span>が選ばれる理由
      </h2>
      <p class="text-gray-600 max-w-3xl mx-auto">
        豊富な実績と確かな専門知識で、御社のAI導入を強力にサポートします。
      </p>
    </div>
    
    <div class="grid grid-cols-1 md:grid-cols-2 gap-x-10 gap-y-12">
      <div class="flex items-start" data-aos="fade-right" data-aos-delay="100">
        <div class="rounded-xl bg-yellow-100 p-4 text-yellow-600 mr-5 transform -rotate-3">
          <i class="fa-solid fa-medal text-3xl"></i>
        </div>
        <div>
          <h3 class="font-bold text-xl mb-3 text-gray-800">官民・中小企業で豊富な実績</h3>
          <p class="text-gray-600">
            製造、卸売、小売、サービス、士業ほか多様な業界でAI研修・DXサポート実績あり。現場状況に寄り添う丁寧なヒアリング＆提案が特徴です。
          </p>
          <div class="mt-4 flex flex-wrap gap-2">
            <span class="bg-yellow-50 text-yellow-700 text-xs px-3 py-1 rounded-full">製造業</span>
            <span class="bg-yellow-50 text-yellow-700 text-xs px-3 py-1 rounded-full">小売業</span>
            <span class="bg-yellow-50 text-yellow-700 text-xs px-3 py-1 rounded-full">サービス業</span>
            <span class="bg-yellow-50 text-yellow-700 text-xs px-3 py-1 rounded-full">IT企業</span>
          </div>
        </div>
      </div>
      
      <div class="flex items-start" data-aos="fade-left" data-aos-delay="200">
        <div class="rounded-xl bg-sky-100 p-4 text-sky-600 mr-5 transform -rotate-3">
          <i class="fa-solid fa-chalkboard-user text-3xl"></i>
        </div>
        <div>
          <h3 class="font-bold text-xl mb-3 text-gray-800">現場で"実際に使える"に特化</h3>
          <p class="text-gray-600">
            理論だけでなく、現場業務・課題に直結するカリキュラム。1社1社オーダーメイド型の研修設計と、実用的なコンサルティングを提供します。
          </p>
          <div class="mt-4 flex items-center">
            <div class="flex">
              <div class="w-10 h-10 rounded-full overflow-hidden border-2 border-white shadow">
                <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="顧客" class="w-full h-full object-cover">
              </div>
              <div class="w-10 h-10 rounded-full overflow-hidden border-2 border-white shadow -ml-2">
                <img src="https://randomuser.me/api/portraits/men/54.jpg" alt="顧客" class="w-full h-full object-cover">
              </div>
            </div>
            <div class="ml-2 text-sm text-gray-500 italic">
              "非常に実践的な内容で、すぐに業務に活かせました"
            </div>
          </div>
        </div>
      </div>
      
      <div class="flex items-start" data-aos="fade-right" data-aos-delay="300">
        <div class="rounded-xl bg-green-100 p-4 text-green-600 mr-5 transform -rotate-3">
          <i class="fa-solid fa-comments-dollar text-3xl"></i>
        </div>
        <div>
          <h3 class="font-bold text-xl mb-3 text-gray-800">助成金対応・申請サポート</h3>
          <p class="text-gray-600">
            人材開発支援助成金（リスキリング支援等）を多数取り扱い。面倒な申請手続きもサポートし、導入コストの最小化をお手伝いします。
          </p>
          <div class="mt-4 bg-green-50 rounded-lg p-3">
            <div class="flex items-center font-medium text-green-700">
              <i class="fa-solid fa-circle-info mr-2"></i>
              <span>最大受給額: 研修費用の75%（条件による）</span>
            </div>
          </div>
        </div>
      </div>
      
      <div class="flex items-start" data-aos="fade-left" data-aos-delay="400">
        <div class="rounded-xl bg-fuchsia-100 p-4 text-fuchsia-600 mr-5 transform -rotate-3">
          <i class="fa-solid fa-award text-3xl"></i>
        </div>
        <div>
          <h3 class="font-bold text-xl mb-3 text-gray-800">圧倒的な顧客満足度</h3>
          <p class="text-gray-600">
            「想像以上に実務で使える」「現実的アドバイスで迷いが消えた」等、企業様から高評価の声を多数いただいています。
          </p>
          <div class="mt-4">
            <div class="flex text-yellow-400">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <span class="ml-2 text-gray-600">4.9/5.0（顧客評価平均）</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- CTA: 成功事例 -->
    <div class="mt-16 bg-gradient-to-r from-sky-100 to-indigo-100 rounded-2xl p-8 shadow-lg" data-aos="fade-up">
      <div class="flex flex-col md:flex-row items-center">
        <div class="md:w-2/3 mb-6 md:mb-0 md:pr-8">
          <h3 class="text-2xl font-bold font-display text-gray-800 mb-3">成功事例を詳しく知りたい方へ</h3>
          <p class="text-gray-600 mb-4">
            中小企業様向けの具体的な導入事例集をご用意しています。<br>
            御社に近い業種の事例も多数ございますので、ぜひご覧ください。
          </p>
          <a href="#contact" class="btn-primary inline-flex">
            <i class="fa-solid fa-file-pdf mr-2"></i> 事例資料を請求する
          </a>
        </div>
        <div class="md:w-1/3">
          <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?auto=format&fit=crop&w=350&q=80" alt="チーム" class="rounded-xl shadow-lg">
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section class="py-20 px-4 bg-gradient-to-b from-sky-50 to-white" id="contact">
  <div class="max-w-5xl mx-auto">
    <div class="text-center mb-14" data-aos="fade-up">
      <span class="px-4 py-1 bg-cyan-100 text-cyan-800 font-medium rounded-full text-sm">お問い合わせ</span>
      <h2 class="text-3xl md:text-4xl font-bold font-display mt-4 mb-5">
        お気軽に<span class="text-sky-600">ご相談</span>ください
      </h2>
      <p class="text-gray-600 max-w-3xl mx-auto">
        ご相談・お見積りは無料です。御社の状況に合わせた最適なプランをご提案いたします。
      </p>
    </div>
    
    <div class="bg-white rounded-2xl shadow-xl overflow-hidden" data-aos="fade-up">
      <div class="flex flex-col md:flex-row">
        <!-- お問い合わせフォーム -->
        <div class="md:w-3/5 p-8 md:p-10">
          <h3 class="text-2xl font-bold mb-6 text-gray-800">お問い合わせ・無料ご相談</h3>
          <form class="space-y-5" action="mailto:info@kaleido.co.jp" method="POST" enctype="text/plain">
            <div>
              <label for="name" class="block text-sm font-medium text-gray-700 mb-1">お名前<span class="text-red-500">*</span></label>
              <input type="text" id="name" name="名前" required placeholder="例: 山田 太郎"
                class="w-full px-4 py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-2 focus:ring-sky-300 focus:border-sky-500 outline-none transition" />
            </div>
            
            <div>
              <label for="email" class="block text-sm font-medium text-gray-700 mb-1">メールアドレス<span class="text-red-500">*</span></label>
              <input type="email" id="email" name="メール" required placeholder="例: yamada@example.com"
                class="w-full px-4 py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-2 focus:ring-sky-300 focus:border-sky-500 outline-none transition" />
            </div>
            
            <div>
              <label for="company" class="block text-sm font-medium text-gray-700 mb-1">会社名</label>
              <input type="text" id="company" name="会社名" placeholder="例: 株式会社◯◯"
                class="w-full px-4 py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-2 focus:ring-sky-300 focus:border-sky-500 outline-none transition" />
            </div>
            
            <div>
              <label for="message" class="block text-sm font-medium text-gray-700 mb-1">お問い合わせ内容<span class="text-red-500">*</span></label>
              <textarea id="message" name="メッセージ" required rows="4" placeholder="お問い合わせ内容をご記入ください"
                class="w-full px-4 py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-2 focus:ring-sky-300 focus:border-sky-500 outline-none transition"></textarea>
            </div>
            
            <div class="flex items-start">
              <input type="checkbox" id="privacy" name="privacy" required class="mt-1 mr-2">
              <label for="privacy" class="text-sm text-gray-600">
                <a href="#" class="text-sky-600 hover:text-sky-800">プライバシーポリシー</a>に同意します<span class="text-red-500">*</span>
              </label>
            </div>
            
            <button type="submit"
              class="w-full bg-gradient-to-r from-sky-500 to-sky-700 text-white py-4 rounded-lg font-bold text-lg shadow hover:shadow-lg hover:translate-y-0.5 transform transition-all duration-300">
              <i class="fa-solid fa-paper-plane mr-2"></i> 送信する
            </button>
          </form>
        </div>
        
        <!-- お問い合わせ情報 -->
        <div class="md:w-2/5 bg-gradient-to-br from-sky-500 to-sky-700 p-8 md:p-10 text-white">
          <h3 class="text-2xl font-bold mb-6">お気軽にお問い合わせください</h3>
          
          <div class="space-y-6">
            <div class="flex items-start">
              <div class="bg-white bg-opacity-20 rounded-full p-3 mr-4">
                <i class="fa-solid fa-envelope text-xl"></i>
              </div>
              <div>
                <h4 class="font-bold mb-1">Eメール</h4>
                <a href="mailto:info@kaleido.co.jp" class="text-blue-100 hover:text-white transition">info@kaleido.co.jp</a>
              </div>
            </div>
            
            <div class="flex items-start">
              <div class="bg-white bg-opacity-20 rounded-full p-3 mr-4">
                <i class="fa-solid fa-phone text-xl"></i>
              </div>
              <div>
                <h4 class="font-bold mb-1">お電話</h4>
                <a href="tel:03-1234-5678" class="text-blue-100 hover:text-white transition">03-1234-5678</a>
                <div class="text-sm opacity-80">平日 9:00-18:00</div>
              </div>
            </div>
            
            <div class="flex items-start">
              <div class="bg-white bg-opacity-20 rounded-full p-3 mr-4">
                <i class="fa-solid fa-location-dot text-xl"></i>
              </div>
              <div>
                <h4 class="font-bold mb-1">所在地</h4>
                <address class="not-italic text-blue-100">
                  〒123-4567<br>
                  東京都◯◯区◯◯1-2-3<br>
                  ◯◯ビル4F
                </address>
              </div>
            </div>
            
            <div class="mt-8 pt-6 border-t border-white border-opacity-20">
              <h4 class="font-bold mb-3">フォロー</h4>
              <div class="flex space-x-4">
                <a href="#" class="bg-white bg-opacity-20 w-10 h-10 rounded-full flex items-center justify-center hover:bg-opacity-30 transition">
                  <i class="fab fa-twitter"></i>
                </a>
                <a href="#" class="bg-white bg-opacity-20 w-10 h-10 rounded-full flex items-center justify-center hover:bg-opacity-30 transition">
                  <i class="fab fa-facebook-f"></i>
                </a>
                <a href="#" class="bg-white bg-opacity-20 w-10 h-10 rounded-full flex items-center justify-center hover:bg-opacity-30 transition">
                  <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="#" class="bg-white bg-opacity-20 w-10 h-10 rounded-full flex items-center justify-center hover:bg-opacity-30 transition">
                  <i class="fab fa-instagram"></i>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FAQ Section -->
<section class="py-16 px-4 bg-white">
  <div class="max-w-4xl mx-auto">
    <div class="text-center mb-12" data-aos="fade-up">
      <span class="px-4 py-1 bg-gray-100 text-gray-800 font-medium rounded-full text-sm">よくある質問</span>
      <h2 class="text-2xl md:text-3xl font-bold font-display mt-4 mb-3">
        ご不明点について
      </h2>
      <p class="text-gray-600">
        お客様からよくいただくご質問と回答をまとめています
      </p>
    </div>
    
    <div class="space-y-4" data-aos="fade-up" data-aos-delay="100">
      <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm">
        <button class="flex justify-between items-center w-full p-5 text-left bg-white hover:bg-gray-50 transition focus:outline-none">
          <span class="font-semibold text-gray-800">研修は何名から受けられますか？</span>
          <i class="fas fa-chevron-down text-gray-400"></i>
        </button>
        <div class="p-5 bg-gray-50 border-t border-gray-200">
          <p class="text-gray-600">
            少人数から大規模まで対応可能です。10名以下の少人数制研修では、より実践的な演習や個別フィードバックが可能です。20名以上の場合はグループワーク形式など、人数に合わせて最適な研修スタイルをご提案いたします。
          </p>
        </div>
      </div>
      
      <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm">
        <button class="flex justify-between items-center w-full p-5 text-left bg-white hover:bg-gray-50 transition focus:outline-none">
          <span class="font-semibold text-gray-800">オンラインでも受講できますか？</span>
          <i class="fas fa-chevron-down text-gray-400"></i>
        </button>
        <div class="p-5 bg-gray-50 border-t border-gray-200">
          <p class="text-gray-600">
            はい、対面・オンラインどちらの形式でも対応しております。Zoom、Microsoft Teamsなど、御社でご利用のオンラインツールに合わせて実施可能です。ハイブリッド形式（一部対面、一部オンライン）のご要望にもお応えします。
          </p>
        </div>
      </div>
      
      <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm">
        <button class="flex justify-between items-center w-full p-5 text-left bg-white hover:bg-gray-50 transition focus:outline-none">
          <span class="font-semibold text-gray-800">助成金はどのように申請すればよいですか？</span>
          <i class="fas fa-chevron-down text-gray-400"></i>
        </button>
        <div class="p-5 bg-gray-50 border-t border-gray-200">
          <p class="text-gray-600">
            人材開発支援助成金など、各種助成金の申請サポートを承っております。必要書類の作成から申請手続きまで、専門スタッフがサポートいたしますので、初めての方でもご安心ください。詳細は個別にご相談ください。
          </p>
        </div>
      </div>
      
      <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm">
        <button class="flex justify-between items-center w-full p-5 text-left bg-white hover:bg-gray-50 transition focus:outline-none">
          <span class="font-semibold text-gray-800">パソコンやAIの知識がない従業員でも大丈夫ですか？</span>
          <i class="fas fa-chevron-down text-gray-400"></i>
        </button>
        <div class="p-5 bg-gray-50 border-t border-gray-200">
          <p class="text-gray-600">
            はい、全く問題ありません。当社の研修は、AIやITの知識がない方でも理解できるよう設計されています。基礎的な内容から段階的に学べるカリキュラムで、実際に手を動かしながら体験していただきますので、安心してご参加いただけます。
          </p>
        </div>
      </div>
    </div>
    
    <div class="text-center mt-8" data-aos="fade-up" data-aos-delay="200">
      <a href="#contact" class="inline-flex items-center text-sky-600 font-medium hover:text-sky-800">
        その他のご質問はこちら <i class="fa-solid fa-arrow-right ml-2"></i>
      </a>
    </div>
  </div>
</section>

<!-- CTA Section -->
<section class="py-20 px-4 bg-gradient-to-r from-sky-500 to-indigo-600 text-white">
  <div class="max-w-5xl mx-auto text-center" data-aos="fade-up">
    <h2 class="text-3xl md:text-4xl font-bold font-display mb-6">
      AI導入で、<span class="text-yellow-300">御社の未来</span>を変えませんか？
    </h2>
    <p class="text-xl text-blue-100 mb-10 max-w-3xl mx-auto">
      今なら初回相談無料。AI活用による業務効率化の可能性を探ってみましょう。
    </p>
    <div class="flex flex-col sm:flex-row justify-center gap-4">
      <a href="#contact" class="btn-primary bg-white text-sky-700 hover:bg-blue-50 shadow-lg">
        <i class="fa-solid fa-calendar-check mr-2"></i> 無料相談を予約する
      </a>
      <a href="#services" class="btn-primary bg-transparent border-2 border-white hover:bg-white hover:text-sky-700">
        <i class="fa-solid fa-list-check mr-2"></i> 研修内容を確認する
      </a>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="bg-gray-900 text-gray-400 pt-16 pb-8">
  <div class="max-w-6xl mx-auto px-4">
    <div class="grid grid-cols-1 md:grid-cols-4 gap-10 pb-10">
      <div>
        <div class="flex items-center mb-5">
          <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=facearea&w=48&h=48&q=80" alt="KALEIDO" class="w-10 h-10 rounded-full mr-3">
          <span class="font-bold font-display text-xl text-white">KALEIDO</span>
        </div>
        <p class="text-sm mb-6">
          中小企業向け生成AI法人研修を提供する合同会社KALEIDO。<br>
          最先端のAI技術で、組織の可能性を最大限に引き出します。
        </p>
        <div class="flex space-x-4">
          <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-twitter"></i></a>
          <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-facebook-f"></i></a>
          <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-linkedin-in"></i></a>
          <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-instagram"></i></a>
        </div>
      </div>
      
      <div>
        <h4 class="text-white font-bold mb-5">サービス</h4>
        <ul class="space-y-2">
          <li><a href="#services" class="hover:text-white transition">生成AIリテラシー研修</a></li>
          <li><a href="#services" class="hover:text-white transition">ChatGPTビジネス活用講座</a></li>
          <li><a href="#services" class="hover:text-white transition">生成AI総合研修</a></li>
          <li><a href="#services" class="hover:text-white transition">AI導入コンサルティング</a></li>
          <li><a href="#services" class="hover:text-white transition">助成金サポート</a></li>
        </ul>
      </div>
      
      <div>
        <h4 class="text-white font-bold mb-5">会社情報</h4>
        <ul class="space-y-2">
          <li><a href="#about" class="hover:text-white transition">KALEIDOについて</a></li>
          <li><a href="#" class="hover:text-white transition">企業理念</a></li>
          <li><a href="#why" class="hover:text-white transition">選ばれる理由</a></li>
          <li><a href="#" class="hover:text-white transition">プライバシーポリシー</a></li>
          <li><a href="#" class="hover:text-white transition">利用規約</a></li>
        </ul>
      </div>
      
      <div>
        <h4 class="text-white font-bold mb-5">お問い合わせ</h4>
        <ul class="space-y-4">
          <li class="flex items-start">
            <i class="fa-solid fa-envelope mt-1.5 mr-3 text-sky-400"></i>
            <a href="mailto:info@kaleido.co.jp" class="hover:text-white transition">info@kaleido.co.jp</a>
          </li>
          <li class="flex items-start">
            <i class="fa-solid fa-phone mt-1.5 mr-3 text-sky-400"></i>
            <a href="tel:03-1234-5678" class="hover:text-white transition">03-1234-5678</a>
          </li>
          <li class="flex items-start">
            <i class="fa-solid fa-location-dot mt-1.5 mr-3 text-sky-400"></i>
            <address class="not-italic">
              〒123-4567<br>
              東京都◯◯区◯◯1-2-3<br>
              ◯◯ビル4F
            </address>
          </li>
        </ul>
      </div>
    </div>
    
    <div class="pt-8 border-t border-gray-800 flex flex-col md:flex-row justify-between items-center">
      <div class="text-sm mb-4 md:mb-0">
        &copy; 2025 合同会社KALEIDO All Rights Reserved.
      </div>
      <div class="text-xs">
        本ページに掲載の画像はイメージです（Unsplash使用）
      </div>
    </div>
  </div>
</footer>

<!-- Back to top button -->
<button id="backToTop" class="fixed bottom-6 right-6 w-12 h-12 bg-sky-600 text-white rounded-full shadow-lg flex items-center justify-center opacity-0 invisible transition-all duration-300 hover:bg-sky-700 focus:outline-none">
  <i class="fa-solid fa-chevron-up"></i>
</button>

<!-- JavaScript -->
<script>
  // AOS初期化
  document.addEventListener('DOMContentLoaded', function() {
    AOS.init({
      duration: 800,
      once: true,
      offset: 100
    });
    
    // ヘッダースクロール挙動
    const header = document.querySelector('.sticky-header');
    window.addEventListener('scroll', function() {
      if (window.scrollY > 50) {
        header.classList.add('scrolled');
      } else {
        header.classList.remove('scrolled');
      }
    });
    
    // モバイルメニュー
    const menuBtn = document.querySelector('.mobile-menu-btn');
    const mobileMenu = document.querySelector('.mobile-menu');
    
    if (menuBtn && mobileMenu) {
      menuBtn.addEventListener('click', function() {
        menuBtn.classList.toggle('active');
        mobileMenu.classList.toggle('active');
      });
    }
    
    // FAQアコーディオン
    const faqButtons = document.querySelectorAll('.border.border-gray-200 button');
    
    faqButtons.forEach(button => {
      button.addEventListener('click', function() {
        const content = this.nextElementSibling;
        const icon = this.querySelector('.fa-chevron-down');
        
        // コンテンツの表示/非表示を切り替え
        if (content.style.maxHeight) {
          content.style.maxHeight = null;
          icon.style.transform = 'rotate(0deg)';
        } else {
          content.style.maxHeight = content.scrollHeight + 'px';
          icon.style.transform = 'rotate(180deg)';
        }
      });
    });
    
    // トップに戻るボタン
    const backToTopBtn = document.getElementById('backToTop');
    
    window.addEventListener('scroll', function() {
      if (window.scrollY > 300) {
        backToTopBtn.classList.add('opacity-100');
        backToTopBtn.classList.remove('opacity-0', 'invisible');
      } else {
        backToTopBtn.classList.remove('opacity-100');
        backToTopBtn.classList.add('opacity-0', 'invisible');
      }
    });
    
    backToTopBtn.addEventListener('click', function() {
      window.scrollTo({
        top: 0,
        behavior: 'smooth'
      });
    });
    
    // スムーズスクロール
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        
        const targetId = this.getAttribute('href');
        if (targetId === '#') return;
        
        const targetElement = document.querySelector(targetId);
        if (targetElement) {
          targetElement.scrollIntoView({
            behavior: 'smooth'
          });
          
          // モバイルメニューが開いている場合は閉じる
          if (mobileMenu && mobileMenu.classList.contains('active')) {
            menuBtn.classList.remove('active');
            mobileMenu.classList.remove('active');
          }
        }
      });
    });
  });
</script>

</body>
</html> '月次人件費（万円）',
          data: [50, 38],
          backgroundColor: ['#0ea5e9', '#a855f7'],
          borderRadius: 8,
        }]
      },
      options: {
        plugins: {
          legend: { display: false },
          tooltip: {
            callbacks: {
              label:
