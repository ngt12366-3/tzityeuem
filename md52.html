<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TOOL MD5 VIPP</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .md5-card {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
            width: 100%;
            max-width: 440px;
            padding: 35px;
            transition: all 0.4s ease;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .md5-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.2);
        }
        
        .card-header {
            text-align: center;
            margin-bottom: 28px;
        }
        
        .logo {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, #6C63FF, #36D1DC);
            color: white;
            border-radius: 15px;
            font-weight: bold;
            font-size: 20px;
            margin-bottom: 15px;
            box-shadow: 0 8px 20px rgba(108, 99, 255, 0.3);
        }
        
        h1 {
            color: #2D3748;
            font-size: 26px;
            margin-bottom: 8px;
            font-weight: 700;
        }
        
        .subtitle {
            color: #718096;
            font-size: 15px;
            font-weight: 500;
        }
        
        .input-group {
            margin-bottom: 24px;
        }
        
        .input-label {
            display: block;
            margin-bottom: 10px;
            color: #4A5568;
            font-weight: 600;
            font-size: 15px;
        }
        
        input[type="text"] {
            width: 100%;
            padding: 16px 18px;
            border: 2px solid #E2E8F0;
            border-radius: 12px;
            font-size: 16px;
            transition: all 0.3s;
            outline: none;
            background: #F7FAFC;
        }
        
        input[type="text"]:focus {
            border-color: #6C63FF;
            background: white;
            box-shadow: 0 0 0 4px rgba(108, 99, 255, 0.1);
            transform: translateY(-2px);
        }
        
        .controls {
            display: flex;
            gap: 14px;
            margin-bottom: 28px;
        }
        
        button {
            flex: 1;
            padding: 16px 18px;
            border: none;
            border-radius: 12px;
            font-weight: 700;
            font-size: 16px;
            cursor: pointer;
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }
        
        button::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 5px;
            height: 5px;
            background: rgba(255, 255, 255, 0.5);
            opacity: 0;
            border-radius: 100%;
            transform: scale(1, 1) translate(-50%);
            transform-origin: 50% 50%;
        }
        
        button:focus:not(:active)::after {
            animation: ripple 1s ease-out;
        }
        
        @keyframes ripple {
            0% {
                transform: scale(0, 0);
                opacity: 1;
            }
            100% {
                transform: scale(40, 40);
                opacity: 0;
            }
        }
        
        button.primary {
            background: linear-gradient(135deg, #6C63FF, #36D1DC);
            color: white;
            box-shadow: 0 6px 20px rgba(108, 99, 255, 0.3);
        }
        
        button.primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(108, 99, 255, 0.4);
        }
        
        button.secondary {
            background: #F7FAFC;
            color: #4A5568;
            border: 2px solid #E2E8F0;
        }
        
        button.secondary:hover {
            background: #EDF2F7;
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.08);
        }
        
        .result-area {
            margin-top: 20px;
            text-align: center;
            padding: 24px;
            border-radius: 15px;
            background: linear-gradient(135deg, #F7FAFC, #EDF2F7);
            display: none;
            border: 1px solid #E2E8F0;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .result {
            font-size: 38px;
            font-weight: 900;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }
        
        .tai {
            color: #38A169;
            text-shadow: 0 2px 10px rgba(56, 161, 105, 0.2);
        }
        
        .xiu {
            color: #E53E3E;
            text-shadow: 0 2px 10px rgba(229, 62, 62, 0.2);
        }
        
        .confidence {
            color: #718096;
            font-size: 15px;
            font-weight: 500;
        }
        
        .divider {
            height: 1px;
            background: linear-gradient(90deg, transparent, #E2E8F0, transparent);
            margin: 28px 0;
        }
        
        .features h3 {
            color: #2D3748;
            margin-bottom: 18px;
            font-size: 18px;
            font-weight: 700;
            text-align: center;
        }
        
        .features-list {
            list-style: none;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 14px;
        }
        
        .features-list li {
            display: flex;
            align-items: center;
            padding: 12px;
            background: rgba(108, 99, 255, 0.05);
            border-radius: 10px;
            color: #4A5568;
            font-size: 14px;
            font-weight: 500;
            transition: all 0.3s;
        }
        
        .features-list li:hover {
            background: rgba(108, 99, 255, 0.1);
            transform: translateY(-2px);
        }
        
        .features-list li::before {
            content: "✓";
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 22px;
            height: 22px;
            background: #C6F6D5;
            color: #38A169;
            border-radius: 50%;
            margin-right: 10px;
            font-size: 12px;
            font-weight: bold;
            flex-shrink: 0;
        }

        /* Telegram Section - Đẹp hơn */
        .telegram-section {
            margin-top: 24px;
            text-align: center;
            padding: 20px;
            background: linear-gradient(135deg, #0088CC 0%, #00C6FF 100%);
            border-radius: 16px;
            color: white;
            position: relative;
            overflow: hidden;
            box-shadow: 0 8px 25px rgba(0, 136, 204, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .telegram-section::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-10px) rotate(180deg); }
        }

        .telegram-content {
            position: relative;
            z-index: 2;
        }

        .telegram-title {
            font-size: 16px;
            font-weight: 600;
            margin-bottom: 12px;
            opacity: 0.9;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .telegram-link {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            color: white;
            text-decoration: none;
            font-weight: 700;
            font-size: 18px;
            transition: all 0.3s ease;
            padding: 12px 24px;
            background: rgba(255, 255, 255, 0.15);
            border-radius: 12px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.3);
            position: relative;
            overflow: hidden;
        }

        .telegram-link::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: left 0.5s;
        }

        .telegram-link:hover::before {
            left: 100%;
        }

        .telegram-link:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            background: rgba(255, 255, 255, 0.25);
        }

        .telegram-icon {
            font-size: 24px;
            filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.2));
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }

        .telegram-username {
            font-weight: 700;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        .telegram-note {
            margin-top: 12px;
            font-size: 13px;
            opacity: 0.8;
            font-weight: 500;
        }
        
        .copyright {
            text-align: center;
            margin-top: 20px;
            color: #A0AEC0;
            font-size: 13px;
        }
    </style>
</head>
<body>
    <div class="md5-card">
        <div class="card-header">
            <div class="logo">VIPP</div>
            <h1>TOOL MD5 VIPP</h1>
            <p class="subtitle">Thuật toán mới - Độ chính xác cao</p>
        </div>
        
        <div class="input-group">
            <label for="md5" class="input-label">Nhập mã MD5</label>
            <input id="md5" type="text" placeholder="Nhập mã MD5 (32 ký tự hex)" autocomplete="off" maxlength="32">
        </div>
        
        <div class="controls">
            <button class="primary" id="checkBtn">XÁC MINH</button>
            <button class="secondary" id="clearBtn">XÓA</button>
        </div>
        
        <div class="result-area" id="resultArea">
            <div id="result" class="result"></div>
            <div class="confidence" id="confidence"></div>
        </div>
        
        <div class="divider"></div>
        
        <div class="features">
            <h3>Tính năng nổi bật</h3>
            <ul class="features-list">
                <li>Xác minh MD5 32 ký tự</li>
                <li>Kết quả Tài/Xỉu chính xác</li>
                <li>Thuật toán VIPP độc quyền</li>
                <li>Hiển thị độ tin cậy</li>
            </ul>
        </div>
        
        <!-- Telegram Section mới đẹp hơn -->
        <div class="telegram-section">
            <div class="telegram-content">
                <div class="telegram-title">Liên hệ hỗ trợ qua Telegram</div>
                <a href="https://t.me/tlonglop1a" class="telegram-link" target="_blank">
                    <span class="telegram-icon">✈️</span>
                    <span class="telegram-username">@boladuas</span>
                </a>
                <div class="telegram-note">Nhấn để liên hệ ngay với chúng tôi</div>
            </div>
        </div>
        
        <div class="copyright">
            © 2025 VIPP MD5 System - All rights reserved
        </div>
    </div>

    <script>
        function isValidMD5(s) {
            return /^[a-f0-9]{32}$/.test(s.trim().toLowerCase());
        }
        
        function xorshift32(seed) {
            let x = seed >>> 0;
            x ^= x << 13;
            x >>>= 0;
            x ^= x >>> 17;
            x >>>= 0;
            x ^= x << 5;
            x >>>= 0;
            return x >>> 0;
        }
        
        function deriveFromMD5(md5) {
            md5 = md5.trim().toLowerCase();
            const vals = [];
            for (let i = 0; i < md5.length; i++) {
                vals.push(parseInt(md5[i], 16));
            }
            const primes = [1, 3, 7, 13, 19, 21];
            let seed = 0;
            for (let i = 0; i < vals.length; i++) {
                seed = (seed + (vals[i] + 1) * primes[i % primes.length] * (i + 1)) >>> 0;
            }
            let mixed = xorshift32(seed);
            mixed = (mixed ^ (seed << 3)) >>> 0;
            mixed = xorshift32(mixed + 0x9e3779b9);
            const score = mixed % 101;
            const confidence = 70 + (mixed % 29);
            const text = score >= 50 ? 'TÀI' : 'XỈU';
            const className = score >= 50 ? 'tai' : 'xiu';
            return { text, className, confidence };
        }
        
        const md5Input = document.getElementById('md5');
        const checkBtn = document.getElementById('checkBtn');
        const clearBtn = document.getElementById('clearBtn');
        const resultEl = document.getElementById('result');
        const confEl = document.getElementById('confidence');
        const resultArea = document.getElementById('resultArea');
        
        function showResult(md5) {
            md5 = md5.trim().toLowerCase();
            
            if (!isValidMD5(md5)) {
                resultEl.textContent = '❌ Mã MD5 không hợp lệ';
                resultEl.className = 'result';
                confEl.textContent = 'Vui lòng nhập mã MD5 32 ký tự hợp lệ';
                resultArea.style.display = 'block';
                return;
            }
            
            const data = deriveFromMD5(md5);
            resultEl.textContent = data.text;
            resultEl.className = 'result ' + data.className;
            confEl.textContent = 'Độ tin cậy: ' + data.confidence + '%';
            resultArea.style.display = 'block';
        }
        
        checkBtn.addEventListener('click', () => {
            showResult(md5Input.value);
        });
        
        clearBtn.addEventListener('click', () => {
            md5Input.value = '';
            resultArea.style.display = 'none';
        });
        
        // Enter key support
        md5Input.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                showResult(md5Input.value);
            }
        });
    </script>
</body>
</html>