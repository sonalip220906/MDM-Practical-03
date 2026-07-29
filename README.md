<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Invento 2026 - College Tech Fest Invitation</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts (Outfit) -->
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Outfit', 'sans-serif'],
          }
        }
      }
    }
  </script>
  <style>
    .bg-dots {
      background-image: radial-gradient(to left,lavender,blue) 1px, transparent 1px);
      background-size: 20px 20px;
    }
  </style>
</head>
<body class="bg-[#060913] text-slate-100 min-h-screen flex flex-col justify-between bg-dots relative overflow-x-hidden antialiased">
  
  <!-- Backdrop Blur Glow Filters -->
  <div class="absolute top-[-10%] left-[-10%] w-[50%] h-[50%] rounded-full bg-indigo-900/10 blur-[120px] pointer-events-none"></div>
  <div class="absolute bottom-[-10%] right-[-10%] w-[50%] h-[50%] rounded-full bg-cyan-900/10 blur-[120px] pointer-events-none"></div>

  <!-- Main Container -->
  <div id="main-canvas" class="flex-1 flex flex-col justify-between py-16 px-4 sm:px-6 lg:px-8 max-w-5xl mx-auto w-full">
    
    <!-- Hero Header -->
    <header class="text-center mt-8">
      <div id="college-tag" class="inline-block mb-3">
        <span class="text-xs md:text-sm font-bold tracking-widest text-teal-400 uppercase">SB JAIN INSTITUTE OF TECHNOLOGY NAGPUR</span>
      </div>
      
      <div id="fest-title">
        <h1 class="text-5xl md:text-8xl font-black tracking-tight text-transparent bg-clip-text bg-gradient-to-r from-pink-400 via-blue-400 to-pink-400 leading-none">̷̷S̷̷O̷̷N̷̷A̷̷L̷̷I̷ 2026</h1>
      </div>
      
      <div id="fest-tagline" class="mt-4 max-w-xl mx-auto">
        <p class="text-slate-200 font-medium tracking-wide text-sm md:text-base">𝐀𝐧𝐧𝐮𝐚𝐥 𝐍𝐚𝐭𝐢𝐨𝐧𝐚𝐥 𝐋𝐞𝐯𝐞𝐥 𝐓𝐞𝐜𝐡𝐧𝐢𝐜𝐚𝐥 𝐅𝐞𝐬𝐭𝐢𝐯𝐚𝐥</p>
      </div>
    </header>

    <!-- Invitation Message -->
    <section id="invite-desc" class="text-center my-8 max-w-2xl mx-auto">
      <p class="text-base md:text-lg text-teal-300 text-slate-300 text-4xl leading-relaxed">
        𝒲𝑒 𝒸𝑜𝓇𝒹𝒾𝒶𝓁𝓁𝓎 𝒾𝓃𝓋𝒾𝓉𝑒 𝓉𝑒𝒸𝒽 𝑒𝓃𝓉𝒽𝓊𝓈𝒾𝒶𝓈𝓉𝓈, 𝒹𝑒𝓋𝑒𝓁𝑜𝓅𝑒𝓇𝓈, 𝒷𝓊𝒾𝓁𝒹𝑒𝓇𝓈, 𝒶𝓃𝒹 𝒻𝒶𝒸𝓊𝓁𝓉𝓎 𝒻𝓇𝑜𝓂 𝒶𝓁𝓁 𝓈𝓉𝓇𝑒𝒶𝓂𝓈 𝓉𝑜 𝒿𝑜𝒾𝓃 𝓊𝓈 𝒻𝑜𝓇 𝒶 𝓉𝒽𝓇𝑒𝑒-𝒹𝒶𝓎 𝒸𝑒𝓁𝑒𝒷𝓇𝒶𝓉𝒾𝑜𝓃 𝑜𝒻 𝓉𝑒𝒸𝒽𝓃𝑜𝓁𝑜𝑔𝓎, 𝒸𝑜𝓂𝓅𝑒𝓉𝒾𝓉𝒾𝓋𝑒 𝒾𝓃𝓃𝑜𝓋𝒶𝓉𝒾𝑜𝓃, 𝒶𝓃𝒹 𝓉𝑒𝒸𝒽 𝑒𝓍𝒽𝒾𝒷𝒾𝓉𝓈.
        </p>
    </section>

    <!-- Events Grid Layout -->
    <section id="event-grid" class="my-10">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        
        <!-- Card 1 -->
        <div id="card-1" class="event-card bg-gradient-to-r from-blue-400 via-pink-400 to-blue-400 leading-none backdrop-blur-md border border-slate-800/80 rounded-2xl p-6 hover:border-cyan-500/30 transition-all duration-300 shadow-xl hover:shadow-cyan-500/5 hover:-translate-y-1">
          <span class="text-2xl mb-3 block">💻</span>
          <h3 class="text-lg font-bold text-purple-900 mb-4">𝙈𝙚𝙜𝙖 𝙃𝙖𝙘𝙠𝙖𝙩𝙝𝙤𝙣</h3>
          <p class="text-teal-800 text-sm leading-relaxed">24-hour building sprint to solve critical global challenges with hardware & software projects.</p>
        </div>

        <!-- Card 2 -->
        <div id="card-2" class="event-card bg-gradient-to-r from-blue-400 via-pink-400 to-blue-400 leading-none backdrop-blur-md border border-slate-800/80 rounded-2xl p-6 hover:border-cyan-500/30 transition-all duration-300 shadow-xl hover:shadow-cyan-500/5 hover:-translate-y-1">
          <span class="text-2xl mb-3 block">🤖</span>
          <h3 class="text-lg font-bold text-purple-900 mb-2">𝙍𝙤𝙗𝙤 𝙎𝙤𝙘𝙘𝙚𝙧</h3>
          <p class="text-teal-800 text-sm leading-relaxed">Design and calibrate custom bots to compete in our soccer arena tournament.</p>
        </div>

        <!-- Card 3 -->
        <div id="card-3" class="event-card bg-gradient-to-r from-blue-400 via-pink-400 to-blue-400 leading-none backdrop-blur-md border border-slate-800/80 rounded-2xl p-6 hover:border-cyan-500/30 transition-all duration-300 shadow-xl hover:shadow-cyan-500/5 hover:-translate-y-1">
          <span class="text-2xl mb-3 block">⚙️</span>
          <h3 class="text-lg font-bold text-purple-900 mb-2">𝘾𝘼𝘿 𝘿𝙚𝙨𝙞𝙜𝙣 𝘼𝙧𝙚𝙣𝙖</h3>
          <p class="text-teal-800 text-sm leading-relaxed">Showcase your drafting accuracy by styling complex structural assemblies on the spot.</p>
        </div>

      </div>
    </section>

    <!-- Venue Badge Details -->
    <section id="event-venue" class="flex flex-col md:flex-row justify-center items-center gap-6 md:gap-12 my-6 text-center">
      <div class="flex items-center gap-3">
        <span class="flex h-10 w-10 items-center justify-center rounded-xl bg-indigo-500/10 text-indigo-400 border border-indigo-500/20">📅</span>
        <div class="text-left">
          <p class="text-sm font-semibold text-white">August 05-10, 2026</p>
          <p class="text-xs text-slate-400">09:00 AM onwards</p>
        </div>
      </div>
      
      <div class="flex items-center gap-3">
        <span class="flex h-10 w-10 items-center justify-center rounded-xl bg-cyan-500/10 text-cyan-400 border border-cyan-500/20">📍</span>
        <div class="text-left">
          <p class="text-sm font-semibold text-white">Grand Campus Auditorium</p>
          <p class="text-xs text-slate-400">Auditorium CSE Department</p>
        </div>
      </div>
    </section>

    <!-- Call to Actions Buttons -->
    <section id="cta-buttons" class="flex flex-col sm:flex-row justify-center items-center gap-4 mt-6 text-center">
      
      <!-- Primary Register button -->
      <a href="#" id="btn-primary" class="w-full sm:w-auto bg-gradient-to-r from-pink-400 to-teal-500 hover:from-pink-500 hover:to-cyan-600 text-slate-900 font-bold px-8 py-3.5 rounded-xl shadow-lg shadow-teal-500/20 transform hover:-translate-y-0.5 active:translate-y-0 active:scale-95 transition-all duration-200 inline-block font-sans">
        Register Now
      </a>
      
      <!-- Secondary brochure button -->
      <a href="#" id="btn-secondary" class="w-full bg-gradient-to-r from-pink-400 to-teal-500 sm:w-auto border border-slate-700 hover:border-slate-400 text-slate-300 hover:text-white font-medium px-8 py-3.5 rounded-xl hover:bg-slate-800/20 transition-all duration-200 inline-block font-sans">
        Download Brochure
      </a>

    </section>

  </div>

  <!-- Footer Branding -->
  <footer class="py-6 border-t border-slate-900 text-center text-xs text-slate-500 bg-slate-950/40">
    <p>College Technical Festival 2026 Invitation Page</p>
    <p>Contact Us-Sonali Parte (8208814544)</p>
    CS25047
  </footer>

</body>
</html>
