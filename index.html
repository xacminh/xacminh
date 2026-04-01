<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xác minh Nhiệm vụ - wmoneyX</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@500;600;700&display=swap');
        
        body, html {
            margin: 0; padding: 0;
            width: 100%; height: 100%;
            overflow-x: hidden;
            font-family: 'Quicksand', sans-serif;
            background-color: #fff;
        }

        #canvas-container {
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            z-index: -1;
            background: linear-gradient(135deg, #fff0f5 0%, #f0faff 100%);
        }

        .main-wrapper {
            min-height: 100vh;
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            position: relative;
            z-index: 1;
        }

        /* LOGO WMONEYX VỚI DẢI LED CHẠY BÊN TRONG */
        .logo-header {
            font-size: 3.5rem;
            font-weight: 900;
            letter-spacing: -2px;
            margin-bottom: 10px;
            position: relative;
            display: inline-block;
            background: linear-gradient(90deg, #ff00ff, #00ffff, #ff00ff);
            background-size: 200% auto;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: led-text-flow 3s linear infinite, neonPulse 2s infinite ease-in-out;
            filter: drop-shadow(0 0 10px rgba(255, 0, 255, 0.5));
        }

        @keyframes led-text-flow {
            to { background-position: 200% center; }
        }

        @keyframes neonPulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        /* LOGO CON VẬT ĐÁNG YÊU ĐỘNG */
        .cute-animal-box {
            font-size: 4rem;
            margin-bottom: 10px;
            display: inline-block;
            animation: animalBounce 2s infinite ease-in-out;
        }

        @keyframes animalBounce {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-15px) rotate(5deg); }
        }

        .content-full {
            width: 100%;
            max-width: 800px;
            text-align: center;
            transition: all 0.5s ease;
        }

        .time-badge {
            background: #ff00ff;
            color: white;
            padding: 8px 20px;
            border-radius: 50px;
            font-weight: 700;
            display: inline-block;
            margin-bottom: 20px;
            font-size: 0.85rem;
            box-shadow: 0 5px 15px rgba(255, 0, 255, 0.4);
            border: 2px solid #fff;
        }

        /* Button với Dải LED chạy dưới đáy */
        .btn-action {
            background: white;
            border: 1px solid #ffb3ff;
            border-radius: 20px;
            padding: 18px;
            margin-bottom: 20px;
            font-weight: 700;
            color: #b300b3;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            width: 100%;
            font-size: 1.05rem;
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(255, 0, 255, 0.05);
        }

        .btn-action::before {
            content: '';
            position: absolute;
            bottom: 0;
            left: -100%;
            width: 100%;
            height: 4px;
            background: linear-gradient(90deg, transparent, #ff00ff, #00ffff, #ff00ff, transparent);
            animation: led-bottom-run 3s linear infinite;
        }

        @keyframes led-bottom-run {
            0% { left: -100%; }
            100% { left: 100%; }
        }

        .btn-action:hover {
            transform: translateY(-4px);
            background: #fffafa;
            box-shadow: 0 10px 25px rgba(255, 0, 255, 0.15);
        }

        .btn-primary-custom {
            border: none !important;
            background: #ff00ff !important;
            color: white !important;
        }
        
        .btn-primary-custom::before {
            background: linear-gradient(90deg, transparent, #fff, #00ffff, #fff, transparent);
        }

        .verify-section {
            animation: slideUp 0.6s ease-out;
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .step-card {
            background: #fff;
            border: 1px solid #ffb3ff;
            border-left: 8px solid #ff00ff;
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 15px;
            text-align: left;
            color: #444;
            box-shadow: 0 5px 15px rgba(255, 0, 255, 0.05);
        }

        .input-mega {
            width: 100%;
            padding: 20px;
            border: 3px solid #ffb3ff;
            border-radius: 20px;
            margin: 20px 0;
            outline: none;
            font-size: 1.2rem;
            font-weight: 700;
            color: #ff00ff;
            background: #fff;
            text-align: center;
            transition: 0.3s;
        }

        .input-mega:focus {
            border-color: #ff00ff;
            box-shadow: 0 0 25px rgba(255, 0, 255, 0.2);
        }

        .btn-send-mega {
            background: linear-gradient(90deg, #ff00ff, #d600d6);
            color: white;
            width: 100%;
            padding: 20px;
            border-radius: 20px;
            font-weight: 900;
            font-size: 1.3rem;
            text-transform: uppercase;
            box-shadow: 0 8px 0px #990099;
            cursor: pointer;
            transition: 0.2s;
            position: relative;
            overflow: hidden;
        }
        
        .btn-send-mega::before {
            content: '';
            position: absolute;
            bottom: 0;
            left: -100%;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, transparent, #fff, #00ffff, #fff, transparent);
            animation: led-bottom-run 2s linear infinite;
        }

        .footer-info {
            margin-top: 30px;
            padding: 20px;
            background: white;
            border-radius: 20px;
            border: 2px dashed #ff00ff;
            color: #666;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
        }

        .copyright-text {
            margin-top: 40px;
            font-size: 0.85rem;
            font-weight: 700;
            color: #ff00ff;
            opacity: 0.9;
            letter-spacing: 1px;
            text-shadow: 0 0 10px rgba(255, 0, 255, 0.2);
        }

        .back-link {
            margin-top: 20px;
            font-weight: 700;
            color: #ff00ff;
            cursor: pointer;
            padding: 8px 20px;
            background: white;
            border: 1px solid #ffb3ff;
            border-radius: 50px;
            display: inline-block;
        }
    </style>
</head>
<body>

    <div id="canvas-container"></div>

    <div class="main-wrapper">
        
        <!-- LOGO WEB CHÍNH VỚI DẢI LED CHẠY BÊN TRONG -->
        <div class="logo-header">WMONEYX</div>

        <!-- TRANG CHÍNH -->
        <div id="home-page" class="content-full">
            <div id="datetime" class="time-badge">...</div>
            
            <!-- LOGO CON VẬT ĐÁNG YÊU -->
            <div class="cute-animal-box">🐼</div>
            
            <p class="text-pink-600 font-bold mb-8">
                Bạn đã hoàn thành nhiệm vụ đặc biệt.<br>Vui lòng dán link để Admin xác minh ngay!
            </p>

            <div class="grid grid-cols-1 gap-1 max-w-md mx-auto">
                <button onclick="showVerifyPage('Google Map')" class="btn-action">
                    <img src="https://www.google.com/images/branding/googleg/1x/googleg_standard_color_128dp.png" class="w-6" alt="google">
                    Xác minh Review Google Map
                </button>
                <button onclick="showVerifyPage('Tripadvisor')" class="btn-action">
                    <i class="fa-solid fa-plane-departure text-blue-500 text-xl"></i>
                    Xác minh Review Tripadvisor
                </button>
                <button onclick="showVerifyPage('App')" class="btn-action btn-primary-custom">
                    <i class="fa-solid fa-gift text-xl"></i>
                    Xác minh Tải & Review App
                </button>
            </div>
        </div>

        <!-- TRANG XÁC MINH -->
        <div id="verify-page" class="content-full verify-section" style="display: none;">
            <h2 id="verify-title" class="text-2xl md:text-3xl font-black text-[#ff00ff] mb-6 uppercase italic">HƯỚNG DẪN</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-3 mb-4">
                <div class="step-card">
                    <div class="font-black text-[#ff00ff] text-xl mb-1">BƯỚC 1</div>
                    <div id="step1-text">Vào phần copy trên thiết bị (Bộ nhớ tạm)</div>
                </div>
                <div class="step-card">
                    <div class="font-black text-[#ff00ff] text-xl mb-1">BƯỚC 2</div>
                    <div id="step2-text">Dán link bài đánh giá (Dạng: https://maps.app.goo.gl/...)</div>
                </div>
            </div>

            <div class="max-w-md mx-auto">
                <input type="text" id="task-link" class="input-mega" placeholder="Dán link tại đây...">
                <button onclick="sendToAdmin()" id="btn-send" class="btn-send-mega">GỬI XÁC MINH</button>
            </div>

            <div class="footer-info text-left">
                <p class="mb-2 font-black text-red-500 flex items-center gap-2">
                    <i class="fa-solid fa-clock"></i> THỜI GIAN DUYỆT:
                </p>
                <div class="flex justify-between text-sm py-1 border-b border-pink-100">
                    <span class="font-bold">Duyệt lần 1:</span>
                    <span class="text-[#ff00ff] font-black">24 GIỜ</span>
                </div>
                <div class="flex justify-between text-sm py-1">
                    <span class="font-bold">Duyệt lần 2:</span>
                    <span class="text-[#ff00ff] font-black">10 NGÀY</span>
                </div>
            </div>

            <div class="back-link" onclick="showHomePage()">
                <i class="fa-solid fa-chevron-left"></i> Quay lại
            </div>
        </div>

        <!-- BẢN QUYỀN -->
        <div class="copyright-text">© 2026 Developed by HOANG MAI ANH VU</div>
    </div>

    <script>
        const SUPABASE_URL = 'https://kblrdjxvsagdfjstchwp.supabase.co'; 
        const SUPABASE_KEY = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImtibHJkanh2c2FnZGZqc3RjaHdwIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NzQxODI1OTAsImV4cCI6MjA4OTc1ODU5MH0.SA7S3BmghnpLb2lXgpfU1aZ--1nFUAWEx6Tyr2iOGm4';
        const _supabase = supabase.createClient(SUPABASE_URL, SUPABASE_KEY);

        let scene, camera, renderer, crystals = [], particles;
        let selectedType = "";

        function init3DBg() {
            scene = new THREE.Scene();
            camera = new THREE.PerspectiveCamera(60, window.innerWidth / window.innerHeight, 0.1, 1000);
            camera.position.z = 25;

            renderer = new THREE.WebGLRenderer({ antialias: true, alpha: true });
            renderer.setSize(window.innerWidth, window.innerHeight);
            document.getElementById('canvas-container').appendChild(renderer.domElement);

            const crystalGeo = new THREE.OctahedronGeometry(1, 0);
            const crystalMat = new THREE.MeshPhongMaterial({ 
                color: 0xff00ff, 
                transparent: true, 
                opacity: 0.15,
                wireframe: true 
            });
            
            for(let i=0; i<25; i++) {
                let crystal = new THREE.Mesh(crystalGeo, crystalMat);
                crystal.position.set(Math.random()*60-30, Math.random()*60-30, Math.random()*30-15);
                crystal.rotation.set(Math.random()*Math.PI, Math.random()*Math.PI, Math.random()*Math.PI);
                let scale = Math.random() * 2 + 0.5;
                crystal.scale.set(scale, scale, scale);
                scene.add(crystal);
                crystals.push(crystal);
            }

            const pGeo = new THREE.BufferGeometry();
            let pCoords = [];
            for(let i=0; i<500; i++) {
                pCoords.push(Math.random()*100-50, Math.random()*100-50, Math.random()*100-50);
            }
            pGeo.setAttribute('position', new THREE.Float32BufferAttribute(pCoords, 3));
            const pMat = new THREE.PointsMaterial({ color: 0x00ffff, size: 0.2, transparent: true, opacity: 0.4 });
            particles = new THREE.Points(pGeo, pMat);
            scene.add(particles);

            scene.add(new THREE.AmbientLight(0xffffff, 0.9));
        }

        function animate3D() {
            requestAnimationFrame(animate3D);
            crystals.forEach((c, i) => {
                c.rotation.x += 0.005;
                c.rotation.y += 0.003;
                c.position.y += Math.sin(Date.now() * 0.001 + i) * 0.01;
            });
            particles.rotation.y += 0.0005;
            renderer.render(scene, camera);
        }

        function updateDateTime() {
            const now = new Date();
            document.getElementById('datetime').innerText = now.toLocaleString('vi-VN');
        }

        function showVerifyPage(type) {
            selectedType = type;
            document.getElementById('home-page').style.display = 'none';
            document.getElementById('verify-page').style.display = 'block';
            document.getElementById('verify-title').innerText = "XÁC MINH " + type;
            document.getElementById('task-link').value = '';

            const step2 = document.getElementById('step2-text');
            if(type === 'App') {
                step2.innerHTML = 'Chụp ảnh màn hình (để đối chiếu nếu cần)<br>Copy link App (VD: https://play.google.com/store/apps/...)';
            } else {
                step2.innerHTML = 'Dán link bài đánh giá vừa copy (Dạng: https://maps.app.goo.gl/...)';
            }
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function showHomePage() {
            document.getElementById('verify-page').style.display = 'none';
            document.getElementById('home-page').style.display = 'block';
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        async function sendToAdmin() {
            const link = document.getElementById('task-link').value;
            if(!link || !link.includes('http')) { alert('Vui lòng dán đúng Link!'); return; }
            const btn = document.getElementById('btn-send');
            btn.innerHTML = 'ĐANG GỬI...';
            btn.disabled = true;

            try {
                const { error } = await _supabase.from('tasks').insert([{ 
                    admin_id: "7790668848", 
                    task_type: selectedType, 
                    task_link: link,
                    status: 'pending'
                }]);
                if (error) throw error;
                confetti({ particleCount: 150, spread: 60, colors: ['#ff00ff', '#00ffff', '#ffffff'] });
                btn.innerHTML = 'GỬI THÀNH CÔNG';
                setTimeout(() => { 
                    alert('Đã gửi! Duyệt trong 24h.'); 
                    // Chuyển hướng về web chính sau khi gửi thành công
                    window.location.href = 'https://wmoney-x.vercel.app/'; 
                }, 1000);
            } catch (err) { alert('Lỗi kết nối!'); btn.innerHTML = 'GỬI LẠI'; btn.disabled = false; }
        }

        window.onload = () => { init3DBg(); animate3D(); updateDateTime(); setInterval(updateDateTime, 1000); };
        window.onresize = () => { camera.aspect = window.innerWidth / window.innerHeight; camera.updateProjectionMatrix(); renderer.setSize(window.innerWidth, window.innerHeight); };
    </script>
</body>
</html>
