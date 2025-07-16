
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="mobile-web-app-capable" content="yes" />
  <meta name="theme-color" content="#4f46e5" />
  <title>Shiva Institute - Education App</title>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-R3PS365BSB"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-R3PS365BSB');
</script>
  <!-- Favicon -->
  <link rel="icon" href="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f423fae2-b625-48f0-a291-76ba894990bb.png" type="image/png" />

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- ✅ AdMob Script -->
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-app-pub-8906089585648278"
    crossorigin="anonymous"></script>

  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f8fafc;
      padding-bottom: 80px;
    }
    .gradient-bg {
      background: linear-gradient(135deg, #4f46e5 0%, #10b981 100%);
    }
    .fade-in {
      animation: fadeIn 0.5s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .course-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
    }
    #ad-banner {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 60px;
      z-index: 999;
      background: #fff;
    }
  </style>
</head>
<body class="min-h-screen">
  <!-- Loading screen -->
  <div id="loading" class="fixed inset-0 bg-white flex items-center justify-center z-50">
    <div class="text-center">
      <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/aad3e0cd-f189-4e40-83b3-819c9a4d3792.png" alt="Loading" class="w-20 h-20 mb-4 rounded-full" />
      <div class="w-16 h-1 bg-gray-200 mx-auto mt-4">
        <div class="h-full bg-blue-500 animate-pulse" style="width: 40%"></div>
      </div>
    </div>
  </div>

  <!-- Header -->
  <header class="gradient-bg text-white shadow-lg">
    <div class="container mx-auto px-4 py-6 flex justify-between items-center">
      <div class="flex items-center">
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/8d1d314b-d911-4d12-bb6f-cbebbdef6491.png" alt="Logo" class="w-12 h-12 mr-4 rounded-full" />
        <div>
          <h1 class="text-2xl font-bold">Shiva Institute</h1>
          <p class="text-sm opacity-80">ESTD. 2001 • ISO Certified</p>
        </div>
      </div>
      <button id="contact-btn" class="bg-white text-blue-600 px-4 py-2 rounded-lg font-medium">
        <i class="fas fa-phone-alt mr-2"></i> Enquire
      </button>
    </div>
  </header>

  <!-- Main Content -->
  <main class="container mx-auto px-4 py-6">
    <!-- About Section -->
    <section class="mb-10 fade-in">
      <h2 class="text-2xl font-bold mb-4 text-gray-800">About Our Institute</h2>
      <div class="bg-white rounded-xl shadow-md p-6">
        <p class="text-gray-700 mb-4">Shiva Institute is a premier educational institution established in 2001, offering quality courses in computer education, vocational training, and professional development programs.</p>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mt-6">
          <div class="text-center p-3 bg-blue-50 rounded-lg"><i class="fas fa-user-graduate text-3xl text-blue-600 mb-2"></i><p class="font-bold">5000+ Students</p></div>
          <div class="text-center p-3 bg-green-50 rounded-lg"><i class="fas fa-certificate text-3xl text-green-600 mb-2"></i><p class="font-bold">ISO Certified</p></div>
          <div class="text-center p-3 bg-purple-50 rounded-lg"><i class="fas fa-calendar-alt text-3xl text-purple-600 mb-2"></i><p class="font-bold">20+ Years</p></div>
          <div class="text-center p-3 bg-yellow-50 rounded-lg"><i class="fas fa-star text-3xl text-yellow-600 mb-2"></i><p class="font-bold">4.8 Rating</p></div>
        </div>
      </div>
    </section>

    <!-- Courses -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold mb-4 text-gray-800">Our Courses</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Course 1 -->
        <div class="course-card bg-white rounded-xl shadow-md overflow-hidden transition-all duration-300">
          <div class="h-40 bg-blue-100 flex items-center justify-center"><i class="fas fa-laptop-code text-6xl text-blue-600"></i></div>
          <div class="p-6"><h3 class="font-bold text-xl mb-2">Advance Computer</h3><p class="text-gray-600 mb-4">Master computer skills from basics to advanced level.</p><button class="bg-blue-600 text-white px-4 py-2 rounded-lg w-full">Enroll Now</button></div>
        </div>
        <!-- Course 2 -->
        <div class="course-card bg-white rounded-xl shadow-md overflow-hidden transition-all duration-300">
          <div class="h-40 bg-green-100 flex items-center justify-center"><i class="fas fa-cube text-6xl text-green-600"></i></div>
          <div class="p-6"><h3 class="font-bold text-xl mb-2">AutoCAD & 3ds Max</h3><p class="text-gray-600 mb-4">CAD training with practical projects.</p><button class="bg-green-600 text-white px-4 py-2 rounded-lg w-full">Enroll Now</button></div>
        </div>
        <!-- Course 3 -->
        <div class="course-card bg-white rounded-xl shadow-md overflow-hidden transition-all duration-300">
          <div class="h-40 bg-purple-100 flex items-center justify-center"><i class="fas fa-chalkboard-teacher text-6xl text-purple-600"></i></div>
          <div class="p-6"><h3 class="font-bold text-xl mb-2">Nursery Teacher Training</h3><p class="text-gray-600 mb-4">Complete training for aspiring teachers.</p><button class="bg-purple-600 text-white px-4 py-2 rounded-lg w-full">Enroll Now</button></div>
        </div>
      </div>
    </section>

    <!-- Video Section -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold mb-4 text-gray-800">Our Resources</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- NTT Videos -->
        <div class="bg-white rounded-xl shadow-md p-6">
          <h3 class="font-bold text-xl mb-4"><i class="fas fa-video mr-2 text-red-500"></i>NTT Course Videos</h3>
          <a href="https://youtube.com/watch?v=jceDhGB0PHQ" class="block p-3 bg-gray-50 rounded-lg hover:bg-gray-100"><i class="fas fa-play-circle text-red-500 mr-2"></i>File Work in NTT</a>
          <a href="https://youtube.com/shorts/2_B4jDA6Z2Q" class="block p-3 bg-gray-50 rounded-lg hover:bg-gray-100"><i class="fas fa-play-circle text-red-500 mr-2"></i>NTT Short Demo</a>
          <a href="https://youtu.be/OtnNsU67K_k" class="block p-3 bg-gray-50 rounded-lg hover:bg-gray-100"><i class="fas fa-play-circle text-red-500 mr-2"></i>Main NTT Video</a>
        </div>
        <!-- Practical Videos -->
        <div class="bg-white rounded-xl shadow-md p-6">
          <h3 class="font-bold text-xl mb-4"><i class="fas fa-graduation-cap mr-2 text-blue-500"></i>Practical Work</h3>
          <a href="https://youtube.com/watch?v=fXUc5wvM3Co" class="block p-3 bg-gray-50 rounded-lg hover:bg-gray-100"><i class="fas fa-play-circle text-red-500 mr-2"></i>Arkandi Flower</a>
          <a href="https://youtube.com/watch?v=FKu6j4wNybY" class="block p-3 bg-gray-50 rounded-lg hover:bg-gray-100"><i class="fas fa-play-circle text-red-500 mr-2"></i>Folder Making</a>
          <a href="https://youtube.com/watch?v=AMo1PgofxBg" class="block p-3 bg-gray-50 rounded-lg hover:bg-gray-100"><i class="fas fa-play-circle text-red-500 mr-2"></i>Exam Instructions</a>
        </div>
      </div>
    </section>
  </main>

  <!-- Contact -->
  <section class="gradient-bg text-white py-10">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-2xl font-bold mb-6">Contact Us</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-4xl mx-auto">
        <div><i class="fas fa-phone-alt text-2xl"></i><p>9814675255<br>9115749490</p></div>
        <div><i class="fas fa-envelope text-2xl"></i><p>shiva.institute@yahoo.com</p></div>
        <div><i class="fas fa-globe text-2xl"></i><a href="https://www.shivainstitute.co.in/" class="underline">shivainstitute.co.in</a></div>
      </div>
    </div>
  </section>

  <!-- ✅ AdMob Banner Ad -->
  <div id="ad-banner">
    <ins class="adsbygoogle"
         style="display:block;width:100%;height:60px"
         data-ad-client="ca-app-pub-8906089585648278"
         data-ad-slot="7354257084"></ins>
    <script>
      (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
  </div>

  <!-- JS Scripts -->
  <script>
    window.addEventListener('load', () => {
      document.getElementById('loading').style.display = 'none';
    });
    document.getElementById('contact-btn').addEventListener('click', () => {
      document.querySelector('section.gradient-bg').scrollIntoView({ behavior: 'smooth' });
    });
  </script>
</body>
</html>
