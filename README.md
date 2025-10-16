
<!DOCTYPE html>

<html lang="pt-BR">
<head>
<meta content="default-src 'self' 'unsafe-inline' 'unsafe-eval' data: blob: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://code.jquery.com https://unpkg.com https://d3js.org https://threejs.org https://cdn.plot.ly https://stackpath.bootstrapcdn.com https://maps.googleapis.com https://cdn.tailwindcss.com https://ajax.googleapis.com https://kit.fontawesome.com https://cdn.datatables.net https://maxcdn.bootstrapcdn.com https://code.highcharts.com https://tako-static-assets-production.s3.amazonaws.com https://www.youtube.com https://fonts.googleapis.com https://fonts.gstatic.com https://pfst.cf2.poecdn.net https://puc.poecdn.net https://i.imgur.com https://wikimedia.org https://*.icons8.com https://*.giphy.com https://picsum.photos https://images.unsplash.com; frame-src 'self' https://www.youtube.com https://trytako.com; child-src 'self'; manifest-src 'self'; worker-src 'self'; upgrade-insecure-requests; block-all-mixed-content;" http-equiv="Content-Security-Policy"/>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Brazo Bank Premium</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet"/>
<style>
    :root {
        --purple-darkest: #0f0019;
        --purple-dark: #1a002e;
        --purple-medium: #2d0052;
        --purple-light: #4b0082;
        --purple-bright: #7c3aed;
        --purple-neon: #a855f7;
        --purple-glow: #c084fc;
        --white-fade: #ffffff66;
        --glass-bg: rgba(255, 255, 255, 0.1);
        --glass-border: rgba(255, 255, 255, 0.2);
        --shadow-purple: rgba(139, 92, 246, 0.4);
        --success: #22c55e;
        --danger: #ef4444;
        --warning: #f59e0b;
        --info: #3b82f6;
        --text-color: #fff;
        --body-bg: linear-gradient(135deg, var(--purple-darkest) 0%, var(--purple-dark) 25%, var(--purple-medium) 50%, var(--purple-dark) 75%, var(--purple-darkest) 100%);
        --card-bg: var(--glass-bg);
        --input-bg: rgba(255, 255, 255, 0.1);
        --input-border: transparent;
        --input-focus-border: var(--purple-neon);
        --chat-bg: rgba(0, 0, 0, 0.3);
    }


    * { 
        margin: 0; 
        padding: 0; 
        box-sizing: border-box; 
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }


    body {
        background: var(--body-bg);
        background-size: 400% 400%;
        animation: gradientShift 15s ease infinite;
        color: var(--text-color);
        display: flex;
        justify-content: center;
        align-items: flex-start;
        min-height: 100vh;
        padding: 20px;
        position: relative;
        overflow-x: hidden;
    }


    @keyframes gradientShift { 
        0% { background-position: 0% 50%; } 
        50% { background-position: 100% 50%; } 
        100% { background-position: 0% 50%; } 
    }


    body::before {
        content: '';
        position: fixed;
        inset: 0;
        background-image:
            radial-gradient(circle at 20% 50%, rgba(168, 85, 247, 0.1) 0%, transparent 50%),
            radial-gradient(circle at 80% 20%, rgba(139, 92, 246, 0.1) 0%, transparent 50%),
            radial-gradient(circle at 40% 80%, rgba(192, 132, 252, 0.1) 0%, transparent 50%);
        animation: float 20s ease-in-out infinite;
        pointer-events: none;
        z-index: -1;
    }


    @keyframes float { 
        0%, 100% { transform: translateY(0px) rotate(0deg); } 
        33% { transform: translateY(-20px) rotate(120deg); } 
        66% { transform: translateY(10px) rotate(240deg); } 
    }


    .container { 
        width: 100%; 
        max-width: 1200px; 
        position: relative; 
        z-index: 1;
    }


    .hidden { 
        display: none !important; 
    }


    .glass-effect { 
        background: var(--glass-bg); 
        backdrop-filter: blur(20px);
        border: 1px solid var(--glass-border); 
        box-shadow: 0 8px 32px var(--shadow-purple); 
    }


    .btn {
        background: linear-gradient(135deg, var(--purple-bright), var(--purple-neon));
        padding: 14px 40px;
        border: none;
        border-radius: 20px;
        cursor: pointer;
        font-size: 18px;
        font-weight: 600;
        transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        width: 100%;
        margin-top: 15px;
        text-align: center;
        text-decoration: none;
        color: #fff;
        position: relative;
        overflow: hidden;
        box-shadow: 0 4px 15px rgba(124, 58, 237, 0.4);
        text-transform: uppercase;
        letter-spacing: 1px;
    }


    .btn:disabled { 
        opacity: 0.6;
        cursor: not-allowed; 
    }


    .btn::before {
        content: '';
        position: absolute;
        top: 0; 
        left: -100%; 
        width: 100%; 
        height: 100%;
        background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
        transition: left 0.5s;
    }


    .btn:hover::before { 
        left: 100%; 
    }


    .btn:hover { 
        transform: translateY(-2px) scale(1.02);
        box-shadow: 0 8px 25px rgba(124, 58, 237, 0.6); 
        background: linear-gradient(135deg, var(--purple-neon), var(--purple-glow));
    }


    .btn:active { 
        transform: translateY(0) scale(0.98); 
    }


    .btn-principal {
        background-color: #ffb300;
        color: #1a1a1a;
        font-size: 18px;
        font-weight: bold;
        padding: 14px 28px;
        border: none;
        border-radius: 8px;
        cursor: pointer;
        box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        transition: all 0.2s ease-in-out;
        width: 100%;
        margin-top: 15px;
        text-transform: uppercase;
        letter-spacing: 1px;
    }


    .btn-principal:hover {
        background-color: #ffa000;
        transform: scale(1.05);
        box-shadow: 0 6px 12px rgba(0,0,0,0.4);
    }


    .btn-secondary {
        background: transparent;
        border: 2px solid var(--purple-neon);
        color: var(--purple-glow);
        padding: 12px 30px;
        border-radius: 20px;
        cursor: pointer;
        font-size: 16px;
        font-weight: 600;
        transition: all 0.3s ease;
        width: 100%;
        margin-top: 10px;
        text-transform: uppercase;
        letter-spacing: 1px;
    }


    .btn-secondary:hover {
        background: var(--purple-neon);
        color: #fff;
        transform: translateY(-2px);
        box-shadow: 0 6px 20px rgba(168, 85, 247, 0.4);
    }


    .card {
        background: var(--card-bg);
        backdrop-filter: blur(20px);
        border: 1px solid var(--glass-border);
        padding: 30px;
        border-radius: 20px;
        box-shadow: 0 12px 40px var(--shadow-purple);
        max-width: 500px;
        margin: 20px auto;
        width: 100%;
        position: relative;
        animation: slideInUp 0.6s ease-out;
    }


    .card-wide {
        max-width: 800px;
    }


    @keyframes slideInUp { 
        from { opacity: 0; transform: translateY(30px); } 
        to { opacity: 1; transform: translateY(0); } 
    }


    input, select, textarea {
        width: 100%;
        padding: 15px;
        margin: 10px 0;
        background: var(--input-bg);
        color: var(--text-color);
        border: 2px solid var(--input-border);
        border-radius: 12px;
        font-size: 16px;
        transition: all 0.3s ease;
        backdrop-filter: blur(10px);
    }


    input::placeholder, textarea::placeholder { 
        color: var(--white-fade);
    }


    input:focus, textarea:focus, select:focus {
        border: 2px solid var(--input-focus-border);
        outline: none;
        background: rgba(255, 255, 255, 0.15);
        box-shadow: 0 0 20px rgba(168, 85, 247, 0.3);
        transform: scale(1.02);
    }


    .input-group {
        position: relative;
        width: 100%;
    }


    .toggle-password {
        position: absolute;
        right: 15px;
        top: 50%;
        transform: translateY(-50%);
        color: var(--purple-glow);
        cursor: pointer;
        font-size: 18px;
        transition: all 0.3s ease;
    }


    .toggle-password:hover {
        color: #ffffff;
        transform: translateY(-50%) scale(1.1);
    }


    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
        gap: 20px;
        margin-top: 25px;
    }


    .card-menu {
        background: linear-gradient(135deg, var(--purple-medium), var(--purple-light));
        border-radius: 20px;
        padding: 25px;
        text-align: center;
        cursor: pointer;
        transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        box-shadow: 0 6px 20px rgba(75, 0, 130, 0.4);
        border: 1px solid var(--glass-border);
        position: relative;
        overflow: hidden;
        min-height: 120px;
        display: flex;
        flex-direction: column; 
        justify-content: center; 
        align-items: center;
    }


    .card-menu::before {
        content: '';
        position: absolute; 
        inset: 0;
        background: linear-gradient(135deg, var(--purple-bright), var(--purple-neon));
        opacity: 0; 
        transition: opacity 0.3s ease; 
        z-index: -1;
    }


    .card-menu:hover::before { 
        opacity: 1; 
    }


    .card-menu:hover { 
        transform: translateY(-8px) scale(1.05);
        box-shadow: 0 15px 35px rgba(124, 58, 237, 0.6); 
    }


    .card-menu i { 
        font-size: 42px; 
        margin-bottom: 12px;
        display: block; 
        filter: drop-shadow(0 0 10px rgba(255, 255, 255, 0.3)); 
    }


    .card-menu span { 
        font-weight: 600;
        font-size: 14px; 
        text-transform: uppercase; 
        letter-spacing: 0.5px; 
    }


    .back {
        cursor: pointer;
        margin-bottom: 15px;
        color: var(--purple-glow);
        font-size: 16px;
        display: inline-flex;
        align-items: center;
        gap: 8px;
        padding: 8px 15px;
        border-radius: 10px;
        transition: all 0.3s ease;
        background: rgba(192, 132, 252, 0.1);
        border: 1px solid var(--glass-border);
    }


    .back:hover { 
        background: rgba(192, 132, 252, 0.2); 
        transform: translateX(-5px);
    }


    .center-content { 
        display: flex; 
        flex-direction: column; 
        align-items: center; 
        justify-content: center; 
        text-align: center; 
        min-height: 80vh;
    }


    .logo { 
        height: 160px; 
        margin-bottom: 30px; 
        animation: logoFloat 3s ease-in-out infinite;
        filter: drop-shadow(0 0 30px rgba(168, 85, 247, 0.5)); 
    }


    @keyframes logoFloat { 
        0%, 100% { transform: translateY(0px) scale(1); } 
        50% { transform: translateY(-10px) scale(1.05); } 
    }


    .saldo {
        text-align: center;
        background: linear-gradient(135deg, var(--purple-medium), var(--purple-light));
        padding: 25px;
        border-radius: 20px;
        margin-bottom: 25px;
        border: 1px solid var(--glass-border);
        box-shadow: 0 8px 25px var(--shadow-purple);
        position: relative; 
        overflow: hidden;
    }


    .saldo::before {
        content: '';
        position: absolute; 
        top: -50%; 
        left: -50%; 
        width: 200%; 
        height: 200%;
        background: conic-gradient(from 0deg, transparent, rgba(168, 85, 247, 0.1), transparent);
        animation: rotate 4s linear infinite; 
        z-index: -1;
    }


    @keyframes rotate { 
        100% { transform: rotate(360deg); } 
    }


    .saldo h3 { 
        margin: 0 0 10px 0; 
        font-size: 18px; 
        color: rgba(255, 255, 255, 0.9);
        text-transform: uppercase; 
        letter-spacing: 1px; 
    }


    .saldo p { 
        font-size: 32px; 
        font-weight: 800; 
        background: linear-gradient(135deg, var(--purple-glow), #ffffff);
        -webkit-background-clip: text; 
        -webkit-text-fill-color: transparent; 
        background-clip: text; 
    }


    h1, h2, h3 {
        background: linear-gradient(135deg, var(--purple-glow), #ffffff);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent; 
        background-clip: text;
        margin-bottom: 20px; 
        font-weight: 700; 
        text-align: center;
    }


    .tela:not(.hidden) { 
        animation: fadeInScale 0.5s ease-out;
    }


    @keyframes fadeInScale { 
        from { opacity: 0; transform: scale(0.95); } 
        to { opacity: 1; transform: scale(1); } 
    }


    .dashboard-summary {
        background: var(--card-bg);
        padding: 20px;
        border-radius: 15px;
        margin-top: 25px;
        border: 1px solid var(--glass-border);
        box-shadow: 0 6px 20px var(--shadow-purple);
    }


    .dashboard-summary h4 {
        text-align: left;
        color: var(--purple-glow);
        margin-bottom: 15px;
        font-size: 1.1rem;
        -webkit-text-fill-color: initial;
        background: none;
    }


    .last-transaction {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 12px 0;
        border-bottom: 1px solid rgba(255,255,255,0.1);
    }


    .msg {
        padding: 15px 20px;
        margin: 15px 0;
        border-radius: 12px;
        text-align: center;
        font-weight: 600;
        backdrop-filter: blur(10px);
        border: 1px solid;
        animation: slideInDown 0.5s ease-out;
    }


    @keyframes slideInDown {
        from { opacity: 0; transform: translateY(-20px); }
        to { opacity: 1; transform: translateY(0); }
    }


    .msg.sucesso {
        background: rgba(34, 197, 94, 0.2);
        border-color: rgba(34, 197, 94, 0.5);
        color: #4ade80;
    }


    .msg.erro {
        background: rgba(239, 68, 68, 0.2);
        border-color: rgba(239, 68, 68, 0.5);
        color: #f87171;
    }
    
    .msg.info {
        background: rgba(59, 130, 246, 0.2);
        border-color: rgba(59, 130, 246, 0.5);
        color: #60a5fa;
    }


    .profile-info {
        text-align: left;
        margin: 20px 0;
    }


    .profile-info label {
        display: block;
        margin-bottom: 5px;
        color: var(--purple-glow);
        font-weight: 600;
        font-size: 14px;
        text-transform: uppercase;
        letter-spacing: 0.5px;
    }


    .profile-info p {
        background: var(--input-bg);
        padding: 12px 15px;
        border-radius: 8px;
        margin-bottom: 15px;
        border: 1px solid var(--glass-border);
    }


    .transaction-item {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 15px;
        background: var(--input-bg);
        border-radius: 12px;
        margin-bottom: 10px;
        border: 1px solid var(--glass-border);
        transition: all 0.3s ease;
    }


    .transaction-item:hover {
        background: rgba(255, 255, 255, 0.15);
        transform: translateX(5px);
    }


    .transaction-icon {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-right: 15px;
        font-size: 16px;
    }


    .transaction-icon.entrada {
        background: rgba(34, 197, 94, 0.2);
        color: var(--success);
    }


    .transaction-icon.saida {
        background: rgba(239, 68, 68, 0.2);
        color: var(--danger);
    }


    .cartao {
        background: linear-gradient(135deg, var(--purple-bright), var(--purple-neon));
        border-radius: 15px;
        padding: 25px;
        margin: 15px 0;
        color: white;
        position: relative;
        overflow: hidden;
        box-shadow: 0 8px 25px rgba(124, 58, 237, 0.4);
    }


    .cartao::before {
        content: '';
        position: absolute;
        top: -50%;
        right: -50%;
        width: 100px;
        height: 100px;
        background: rgba(255, 255, 255, 0.1);
        border-radius: 50%;
    }


    .cartao-numero {
        font-size: 18px;
        letter-spacing: 3px;
        margin: 15px 0;
        font-family: 'Courier New', monospace;
    }


    .tab-buttons {
        display: flex;
        border-bottom: 1px solid var(--glass-border);
        margin-bottom: 20px;
        gap: 0;
    }


    .tab-btn {
        flex: 1;
        padding: 12px 20px;
        background: transparent;
        border: none;
        color: var(--white-fade);
        cursor: pointer;
        transition: all 0.3s ease;
        border-bottom: 2px solid transparent;
    }


    .tab-btn.active {
        color: var(--purple-glow);
        border-bottom-color: var(--purple-glow);
        background: rgba(168, 85, 247, 0.1);
    }


    .tab-content {
        display: none;
        animation: fadeInUp 0.5s ease-out;
    }


    .tab-content.active {
        display: block;
    }


    @keyframes fadeInUp {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }


    .chat-container {
        height: 400px;
        display: flex;
        flex-direction: column;
        background: var(--chat-bg);
        border-radius: 15px;
        overflow: hidden;
        border: 1px solid var(--glass-border);
    }


    .chat-messages {
        flex: 1;
        padding: 20px;
        overflow-y: auto;
        display: flex;
        flex-direction: column;
        gap: 15px;
    }


    .chat-messages::-webkit-scrollbar {
        width: 6px;
    }


    .chat-messages::-webkit-scrollbar-track {
        background: rgba(255, 255, 255, 0.1);
        border-radius: 3px;
    }


    .chat-messages::-webkit-scrollbar-thumb {
        background: var(--purple-bright);
        border-radius: 3px;
    }


    .message {
        display: flex;
        flex-direction: column;
        animation: messageSlide 0.3s ease-out;
    }


    @keyframes messageSlide {
        from { opacity: 0; transform: translateY(10px); }
        to { opacity: 1; transform: translateY(0); }
    }


    .message .text {
        padding: 12px 18px;
        border-radius: 20px;
        word-wrap: break-word;
        max-width: 85%;
        backdrop-filter: blur(10px);
        border: 1px solid rgba(255, 255, 255, 0.1);
    }


    .message.user .text {
        background: linear-gradient(135deg, var(--purple-bright), var(--purple-neon));
        align-self: flex-end;
        box-shadow: 0 4px 15px rgba(124, 58, 237, 0.3);
    }


    .message.support .text {
        background: rgba(255, 255, 255, 0.1);
        align-self: flex-start;
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    }


    .message .time {
        font-size: 12px;
        margin-top: 5px;
        opacity: 0.7;
    }


    .message.user .time {
        align-self: flex-end;
    }


    .chat-input {
        padding: 15px;
        border-top: 1px solid var(--glass-border);
        display: flex;
        gap: 10px;
    }


    .chat-input input {
        flex: 1;
        margin: 0;
    }


    .chat-input button {
        margin: 0;
        width: auto;
        padding: 15px 20px;
    }
    
    .modal-overlay {
        position: fixed;
        inset: 0;
        background: rgba(0, 0, 0, 0.7);
        backdrop-filter: blur(10px);
        display: flex;
        justify-content: center;
        align-items: center;
        z-index: 1000;
        animation: fadeIn 0.3s ease-out;
    }
    
    @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
    }

    .modal-content {
        max-width: 500px;
        width: 90%;
        animation: fadeInScale 0.3s ease-out;
    }

    .modal-close {
        position: absolute;
        top: 15px;
        right: 20px;
        font-size: 2rem;
        cursor: pointer;
        color: var(--white-fade);
        transition: color 0.3s;
        line-height: 1;
    }

    .modal-close:hover {
        color: #fff;
    }

    .boleto-visual {
        text-align: center;
        margin: 20px 0;
        background: rgba(255, 255, 255, 0.1);
        padding: 20px;
        border-radius: 15px;
    }

    .boleto-visual svg {
        display: block;
        margin: 20px auto;
        background: white;
        padding: 10px;
        border-radius: 8px;
    }

    #qrcode {
        width: 180px;
        height: 180px;
    }

    #barcode {
        width: 100%;
        max-width: 320px;
        height: 80px;
        padding: 0;
    }

    .codigo-numerico {
        font-family: 'Courier New', monospace;
        letter-spacing: 1px;
        margin-top: 20px;
        word-break: break-all;
        color: var(--purple-glow);
        font-weight: bold;
        background: var(--purple-dark);
        padding: 10px;
        border-radius: 8px;
    }


    @media (max-width: 768px) {
        .grid { 
            grid-template-columns: repeat(2, 1fr);
            gap: 15px; 
        }
        .card { 
            padding: 20px; 
            margin: 15px auto;
        }
        .card-menu { 
            padding: 20px; 
            min-height: 100px;
        }
        .card-menu i { 
            font-size: 36px; 
            margin-bottom: 8px;
        }
        .saldo p { 
            font-size: 28px;
        }
        .logo { 
            height: 130px;
        }
        .tab-buttons {
            flex-wrap: wrap;
        }
        .tab-btn {
            flex: none;
            min-width: 120px;
        }
    }


    @media (max-width: 480px) {
        .grid { 
            grid-template-columns: 1fr;
        }
        .card-menu { 
            padding: 25px;
        }
    }
</style>
</head>
<body class="theme-dark">
<div class="container" role="main">
<div aria-live="polite" class="tela center-content" id="tela-inicial">
<div style="max-width: 420px; width: 100%;">
<svg class="logo" viewbox="0 0 800 600" xmlns="http://www.w3.org/2000/svg">
<defs>
<lineargradient id="buildingGradient" x1="0%" x2="100%" y1="0%" y2="100%">
<stop offset="0%" style="stop-color:#E8D5B7"></stop>
<stop offset="100%" style="stop-color:#D4C4A0"></stop>
</lineargradient>
<lineargradient id="textGradient" x1="0%" x2="100%" y1="0%" y2="0%">
<stop offset="0%" style="stop-color:#E8D5B7"></stop>
<stop offset="100%" style="stop-color:#F5F0E8"></stop>
</lineargradient>
</defs>
<rect fill="url(#buildingGradient)" height="50" opacity="0.9" width="400" x="80" y="350"></rect>
<rect fill="url(#buildingGradient)" height="150" opacity="0.8" width="360" x="100" y="200"></rect>
<polygon fill="url(#buildingGradient)" opacity="0.9" points="80,200 280,120 480,200"></polygon>
<rect fill="url(#buildingGradient)" height="150" width="20" x="140" y="200"></rect>
<rect fill="url(#buildingGradient)" height="150" width="20" x="190" y="200"></rect>
<rect fill="url(#buildingGradient)" height="150" width="20" x="240" y="200"></rect>
<rect fill="url(#buildingGradient)" height="150" width="20" x="290" y="200"></rect>
<rect fill="url(#buildingGradient)" height="150" width="20" x="340" y="200"></rect>
<rect fill="url(#buildingGradient)" height="150" width="20" x="390" y="200"></rect>
<rect fill="url(#buildingGradient)" height="15" width="30" x="135" y="190"></rect>
<rect fill="url(#buildingGradient)" height="15" width="30" x="185" y="190"></rect>
<rect fill="url(#buildingGradient)" height="15" width="30" x="235" y="190"></rect>
<rect fill="url(#buildingGradient)" height="15" width="30" x="285" y="190"></rect>
<rect fill="url(#buildingGradient)" height="15" width="30" x="335" y="190"></rect>
<rect fill="url(#buildingGradient)" height="15" width="30" x="385" y="190"></rect>
<circle cx="280" cy="160" fill="none" r="25" stroke="url(#buildingGradient)" stroke-width="3"></circle>
<text fill="url(#buildingGradient)" font-size="20" font-weight="bold" text-anchor="middle" x="280" y="168">$</text>
<text fill="url(#textGradient)" font-family="serif" font-size="72" font-weight="bold" x="480" y="280">BRAZO</text>
<text fill="url(#textGradient)" font-family="serif" font-size="72" font-weight="bold" x="480" y="350">BANK</text>
</svg>
<h1 style="font-size: 2.2rem; margin-bottom: 16px;">Brazo Bank Premium</h1>
<p style="font-size: 1.05rem; margin-bottom: 26px; color: rgba(255, 255, 255, 0.85);">Sua experiência bancária do futuro</p>
<button class="btn-principal" onclick="mostrarLogin()">Entrar</button>
<button class="btn-secondary" onclick="mostrarCadastro()">Criar Conta</button>
</div>
</div>
<div class="tela hidden" id="tela-login">
<div class="card">
<div class="back" onclick="voltarTelaInicial()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Entrar na Conta</h2>
<div id="msg-login"></div>
<form onsubmit="return fazerLogin(event)">
<input id="login-email" placeholder="Email" required="" type="email"/>
<div class="input-group">
<input id="login-senha" placeholder="Senha" required="" type="password"/>
<i class="fas fa-eye toggle-password" onclick="togglePassword('login-senha')"></i>
</div>
<button class="btn" type="submit">
<i class="fas fa-sign-in-alt"></i> Entrar
                </button>
</form>
<p style="text-align: center; margin-top: 20px; color: var(--white-fade);">
                Não tem uma conta? 
                <span onclick="mostrarCadastro()" style="color: var(--purple-glow); cursor: pointer; text-decoration: underline;">
                    Criar conta
                </span>
</p>
</div>
</div>
<div class="tela hidden" id="tela-cadastro">
<div class="card">
<div class="back" onclick="voltarTelaInicial()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Criar Nova Conta</h2>
<div id="msg-cadastro"></div>
<form onsubmit="return fazerCadastro(event)">
<input id="cadastro-nome" placeholder="Nome Completo" required="" type="text"/>
<input id="cadastro-email" placeholder="Email" required="" type="email"/>
<input id="cadastro-telefone" placeholder="Telefone (11) 99999-9999" required="" type="tel"/>
<input id="cadastro-cpf" placeholder="CPF" required="" type="text"/>
<input id="cadastro-nascimento" placeholder="Data de Nascimento" required="" type="date"/>
<div class="input-group">
<input id="cadastro-senha" placeholder="Senha" required="" type="password"/>
<i class="fas fa-eye toggle-password" onclick="togglePassword('cadastro-senha')"></i>
</div>
<div class="input-group">
<input id="cadastro-confirmar-senha" placeholder="Confirmar Senha" required="" type="password"/>
<i class="fas fa-eye toggle-password" onclick="togglePassword('cadastro-confirmar-senha')"></i>
</div>
<button class="btn" type="submit">
<i class="fas fa-user-plus"></i> Criar Conta
                </button>
</form>
<p style="text-align: center; margin-top: 20px; color: var(--white-fade);">
                Já tem uma conta? 
                <span onclick="mostrarLogin()" style="color: var(--purple-glow); cursor: pointer; text-decoration: underline;">
                    Fazer login
                </span>
</p>
</div>
</div>
<div class="tela hidden" id="menu-principal">
<div class="card">
<div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
<div class="back" onclick="logout()">
<i class="fas fa-sign-out-alt"></i> Sair
                </div>
<div style="color: var(--purple-glow);">
<i class="fas fa-user-circle"></i> <span id="nome-usuario"></span>
</div>
</div>
<h2>Painel Principal</h2>
<div class="saldo">
<h3>Saldo Atual</h3>
<p id="saldo-valor"></p>
</div>
<div class="grid">
<div class="card-menu" onclick="mostrarPerfil()">
<i class="fas fa-user"></i>
<span>Perfil</span>
</div>
<div class="card-menu" onclick="mostrarTransferencias()">
<i class="fas fa-exchange-alt"></i>
<span>Transferências</span>
</div>
<div class="card-menu" onclick="mostrarExtrato()">
<i class="fas fa-file-alt"></i>
<span>Extrato</span>
</div>
<div class="card-menu" onclick="mostrarConfiguracao()">
<i class="fas fa-cog"></i>
<span>Configurações</span>
</div>
<div class="card-menu" onclick="mostrarCartoes()">
<i class="fas fa-credit-card"></i>
<span>Cartões</span>
</div>
<div class="card-menu" onclick="mostrarEmprestimo()">
<i class="fas fa-hand-holding-usd"></i>
<span>Empréstimo</span>
</div>
<div class="card-menu" onclick="mostrarBoleto()">
<i class="fas fa-barcode"></i>
<span>Boleto</span>
</div>
<div class="card-menu" onclick="mostrarRecarga()">
<i class="fas fa-mobile-alt"></i>
<span>Recarga</span>
</div>
</div>
<div class="dashboard-summary">
<h4><i class="fas fa-chart-line"></i> Resumo da Conta</h4>
<div class="last-transaction">
<span>Última transação:</span>
<span style="color: var(--success);">+ R$ 2.500,00</span>
</div>
<div class="last-transaction">
<span>Gastos este mês:</span>
<span style="color: var(--danger);">- R$ 3.240,50</span>
</div>
<div class="last-transaction" style="border-bottom: none;">
<span>Cartão de crédito:</span>
<span>R$ 1.200,00 / R$ 5.000,00</span>
</div>
</div>
</div>
</div>
<div class="tela hidden" id="tela-perfil">
<div class="card">
<div class="back" onclick="voltarMenuPrincipal()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Meu Perfil</h2>
<div style="text-align: center; margin-bottom: 30px;">
<div style="width: 120px; height: 120px; background: linear-gradient(135deg, var(--purple-light), var(--purple-bright)); border-radius: 50%; margin: 0 auto 20px; display: flex; align-items: center; justify-content: center; border: 4px solid var(--purple-glow);">
<i class="fas fa-user" style="font-size: 48px; color: white;"></i>
</div>
<h3 id="view-perfil-nome" style="margin-bottom: 5px;"></h3>
<input class="hidden" id="edit-perfil-nome" style="text-align: center; font-size: 1.5rem; font-weight: bold; margin-bottom: 5px;" type="text"/>
<p style="color: rgba(255, 255, 255, 0.7);">Cliente Premium</p>
</div>
<div id="msg-perfil"></div>
<div class="profile-info">
<label>Email:</label>
<p id="view-perfil-email"></p>
<input class="hidden" id="edit-perfil-email" type="email"/>
<label>CPF:</label>
<p id="view-perfil-cpf"></p>
<input class="hidden" id="edit-perfil-cpf" type="text"/>
<label>Telefone:</label>
<p id="view-perfil-telefone"></p>
<input class="hidden" id="edit-perfil-telefone" type="tel"/>
<label>Data de Nascimento:</label>
<p id="view-perfil-nascimento"></p>
<input class="hidden" id="edit-perfil-nascimento" type="date"/>
<label>Conta:</label>
<p id="perfil-conta">12345-6</p>
<label>Agência:</label>
<p id="perfil-agencia">0001</p>
</div>
<button class="btn" id="btn-editar-perfil" onclick="editarPerfil()">
<i class="fas fa-edit"></i> Editar Perfil
            </button>
<button class="btn hidden" id="btn-salvar-perfil" onclick="salvarPerfil()">
<i class="fas fa-save"></i> Salvar Alterações
            </button>
</div>
</div>
<div class="tela hidden" id="tela-transferencias">
<div class="card">
<div class="back" onclick="voltarMenuPrincipal()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Transferências</h2>
<div id="msg-transferencia"></div>
<form onsubmit="return realizarTransferencia(event)">
<select id="tipo-transferencia" required="">
<option value="">Selecione o tipo</option>
<option value="ted">TED</option>
<option value="doc">DOC</option>
<option value="pix">PIX</option>
</select>
<input id="conta-destino" placeholder="Conta de destino" required="" type="text"/>
<input id="agencia-destino" placeholder="Agência" required="" type="text"/>
<input id="nome-favorecido" placeholder="Nome do favorecido" required="" type="text"/>
<input id="valor-transferencia" placeholder="Valor (R$)" required="" step="0.01" type="number"/>
<textarea id="descricao-transferencia" placeholder="Descrição (opcional)" rows="3"></textarea>
<button class="btn" type="submit">
<i class="fas fa-paper-plane"></i> Transferir
                </button>
</form>
<div style="margin-top: 30px;">
<h4 style="color: var(--purple-glow); margin-bottom: 15px;">
<i class="fas fa-history"></i> Últimas Transferências
                </h4>
<div id="historico-transferencias">
<div class="transaction-item">
<div style="display: flex; align-items: center;">
<div class="transaction-icon saida">
<i class="fas fa-arrow-up"></i>
</div>
<div>
<strong>TED para Maria Santos</strong><br/>
<small style="color: var(--white-fade);">Hoje, 14:30</small>
</div>
</div>
<div style="color: var(--danger); font-weight: bold;">
                            - R$ 500,00
                        </div>
</div>
<div class="transaction-item">
<div style="display: flex; align-items: center;">
<div class="transaction-icon saida">
<i class="fas fa-arrow-up"></i>
</div>
<div>
<strong>PIX para João Costa</strong><br/>
<small style="color: var(--white-fade);">Ontem, 09:15</small>
</div>
</div>
<div style="color: var(--danger); font-weight: bold;">
                            - R$ 150,00
                        </div>
</div>
</div>
</div>
</div>
</div>
<div class="tela hidden" id="tela-extrato">
<div class="card card-wide">
<div class="back" onclick="voltarMenuPrincipal()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Extrato da Conta</h2>
<div style="margin-bottom: 20px;">
<input id="filtro-mes" style="width: auto; display: inline-block; margin-right: 10px;" type="month"/>
<button class="btn" onclick="filtrarExtrato()" style="width: auto; display: inline-block; margin: 0; padding: 10px 20px;">
<i class="fas fa-filter"></i> Filtrar
                </button>
</div>
<div id="extrato-lista">
<div class="transaction-item">
<div style="display: flex; align-items: center;">
<div class="transaction-icon entrada">
<i class="fas fa-arrow-down"></i>
</div>
<div>
<strong>Depósito</strong><br/>
<small style="color: var(--white-fade);">15/08/2025 - 10:30</small>
</div>
</div>
<div style="color: var(--success); font-weight: bold;">
                        + R$ 2.500,00
                    </div>
</div>
<div class="transaction-item">
<div style="display: flex; align-items: center;">
<div class="transaction-icon saida">
<i class="fas fa-shopping-cart"></i>
</div>
<div>
<strong>Compra Supermercado XYZ</strong><br/>
<small style="color: var(--white-fade);">14/08/2025 - 18:45</small>
</div>
</div>
<div style="color: var(--danger); font-weight: bold;">
                        - R$ 234,50
                    </div>
</div>
<div class="transaction-item">
<div style="display: flex; align-items: center;">
<div class="transaction-icon saida">
<i class="fas fa-gas-pump"></i>
</div>
<div>
<strong>Posto de Gasolina</strong><br/>
<small style="color: var(--white-fade);">13/08/2025 - 16:20</small>
</div>
</div>
<div style="color: var(--danger); font-weight: bold;">
                        - R$ 120,00
                    </div>
</div>
<div class="transaction-item">
<div style="display: flex; align-items: center;">
<div class="transaction-icon entrada">
<i class="fas fa-building"></i>
</div>
<div>
<strong>Salário - Empresa ABC</strong><br/>
<small style="color: var(--white-fade);">01/08/2025 - 08:00</small>
</div>
</div>
<div style="color: var(--success); font-weight: bold;">
                        + R$ 5.000,00
                    </div>
</div>
<div class="transaction-item">
<div style="display: flex; align-items: center;">
<div class="transaction-icon saida">
<i class="fas fa-home"></i>
</div>
<div>
<strong>Aluguel</strong><br/>
<small style="color: var(--white-fade);">31/07/2025 - 10:00</small>
</div>
</div>
<div style="color: var(--danger); font-weight: bold;">
                        - R$ 1.200,00
                    </div>
</div>
</div>
</div>
</div>
<div class="tela hidden" id="tela-configuracao">
<div class="card">
<div class="back" onclick="voltarMenuPrincipal()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Configurações</h2>
<div class="tab-buttons">
<button class="tab-btn active" onclick="showTab('senha')">Senha</button>
<button class="tab-btn" onclick="showTab('notificacoes')">Notificações</button>
<button class="tab-btn" onclick="showTab('seguranca')">Segurança</button>
<button class="tab-btn" onclick="showTab('privacidade')">Privacidade</button>
<button class="tab-btn" onclick="showTab('suporte')">Suporte</button>
</div>
<div class="tab-content active" id="tab-senha">
<h3 style="color: var(--purple-glow); margin-bottom: 20px;">Alterar Senha</h3>
<form onsubmit="return alterarSenha(event)">
<div class="input-group">
<input id="senha-atual" placeholder="Senha atual" required="" type="password"/>
<i class="fas fa-eye toggle-password" onclick="togglePassword('senha-atual')"></i>
</div>
<div class="input-group">
<input id="nova-senha" placeholder="Nova senha" required="" type="password"/>
<i class="fas fa-eye toggle-password" onclick="togglePassword('nova-senha')"></i>
</div>
<div class="input-group">
<input id="confirmar-nova-senha" placeholder="Confirmar nova senha" required="" type="password"/>
<i class="fas fa-eye toggle-password" onclick="togglePassword('confirmar-nova-senha')"></i>
</div>
<button class="btn" type="submit">
<i class="fas fa-key"></i> Alterar Senha
                    </button>
</form>
</div>
<div class="tab-content" id="tab-notificacoes">
<h3 style="color: var(--purple-glow); margin-bottom: 20px;">Notificações</h3>
<div style="margin-bottom: 20px;">
<label style="display: flex; align-items: center; justify-content: space-between; padding: 15px; background: var(--input-bg); border-radius: 10px; cursor: pointer;">
<span>Notificações por Email</span>
<input checked="" style="width: auto;" type="checkbox"/>
</label>
</div>
<div style="margin-bottom: 20px;">
<label style="display: flex; align-items: center; justify-content: space-between; padding: 15px; background: var(--input-bg); border-radius: 10px; cursor: pointer;">
<span>Notificações por SMS</span>
<input checked="" style="width: auto;" type="checkbox"/>
</label>
</div>
<div style="margin-bottom: 20px;">
<label style="display: flex; align-items: center; justify-content: space-between; padding: 15px; background: var(--input-bg); border-radius: 10px; cursor: pointer;">
<span>Alertas de Transações</span>
<input checked="" style="width: auto;" type="checkbox"/>
</label>
</div>
<button class="btn" onclick="salvarNotificacoes()">
<i class="fas fa-save"></i> Salvar Preferências
                </button>
</div>
<div class="tab-content" id="tab-seguranca">
<h3 style="color: var(--purple-glow); margin-bottom: 20px;">Segurança</h3>
<div style="margin-bottom: 20px;">
<label style="display: flex; align-items: center; justify-content: space-between; padding: 15px; background: var(--input-bg); border-radius: 10px; cursor: pointer;">
<span>Autenticação de Dois Fatores</span>
<input style="width: auto;" type="checkbox"/>
</label>
</div>
<div style="margin-bottom: 20px;">
<label style="display: flex; align-items: center; justify-content: space-between; padding: 15px; background: var(--input-bg); border-radius: 10px; cursor: pointer;">
<span>Login por Biometria</span>
<input style="width: auto;" type="checkbox"/>
</label>
</div>
<button class="btn" onclick="configurarSeguranca()">
<i class="fas fa-shield-alt"></i> Salvar Configurações
                </button>
</div>
<div class="tab-content" id="tab-privacidade">
<h3 style="color: var(--purple-glow); margin-bottom: 20px;">Privacidade</h3>
<div style="margin-bottom: 20px;">
<label style="display: flex; align-items: center; justify-content: space-between; padding: 15px; background: var(--input-bg); border-radius: 10px; cursor: pointer;">
<span>Compartilhar dados para ofertas</span>
<input style="width: auto;" type="checkbox"/>
</label>
</div>
<div style="margin-bottom: 20px;">
<label style="display: flex; align-items: center; justify-content: space-between; padding: 15px; background: var(--input-bg); border-radius: 10px; cursor: pointer;">
<span>Receber ofertas por email</span>
<input style="width: auto;" type="checkbox"/>
</label>
</div>
<button class="btn" onclick="salvarPrivacidade()">
<i class="fas fa-user-shield"></i> Salvar Privacidade
                </button>
</div>
<div class="tab-content" id="tab-suporte">
<h3 style="color: var(--purple-glow); margin-bottom: 20px;">Suporte</h3>
<div class="tab-buttons">
<button class="tab-btn active" onclick="showSupportTab('chat')">Chat</button>
<button class="tab-btn" onclick="showSupportTab('telefone')">Telefone</button>
<button class="tab-btn" onclick="showSupportTab('email')">Email</button>
</div>
<div class="tab-content active" id="support-tab-chat">
<div class="chat-container">
<div class="chat-messages" id="chat-messages"></div>
<div class="chat-input">
<input id="chat-input" placeholder="Digite sua mensagem..." type="text"/>
<button class="btn" onclick="enviarMensagem()">Enviar</button>
</div>
</div>
</div>
<div class="tab-content" id="support-tab-telefone">
<p>Entre em contato pelo nosso telefone:</p>
<button class="btn" onclick="ligar()"><i class="fas fa-phone"></i> Ligar</button>
<button class="btn" onclick="whatsapp()"><i class="fab fa-whatsapp"></i> WhatsApp</button>
</div>
<div class="tab-content" id="support-tab-email">
<p>Entre em contato pelo email:</p>
<button class="btn" onclick="enviarEmail()"><i class="fas fa-envelope"></i> Enviar Email</button>
</div>
</div>
</div>
</div>
<div class="tela hidden" id="tela-cartoes">
<div class="card">
<div class="back" onclick="voltarMenuPrincipal()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Meus Cartões</h2>
<div class="cartao" id="cartao-roxo" style="background: linear-gradient(135deg, var(--purple-bright), var(--purple-neon));">
<div style="display: flex; justify-content: space-between; align-items: center;">
<h4>Brazo Roxo</h4>
<i class="fab fa-cc-visa" style="font-size: 32px;"></i>
</div>
<div class="cartao-numero">•••• •••• •••• 4321</div>
<div style="display: flex; justify-content: space-between;">
<span id="cartao-roxo-nome"></span>
<span>12/28</span>
</div>
<div style="margin-top:10px;">
<button class="btn" id="btn-bloquear-roxo" onclick="bloquearCartao('roxo')">
<i class="fas fa-lock"></i> Bloquear
                    </button>
<button class="btn hidden" id="btn-desbloquear-roxo" onclick="desbloquearCartao('roxo')">
<i class="fas fa-unlock"></i> Desbloquear
                    </button>
</div>
<div class="cartao-descricao">💳 Limite inicial: R$ 5.000 | Benefícios: Programa de pontos, cashback em compras online. Uso: Cartão para o dia a dia, sem anuidade.</div></div>
<div class="cartao" id="cartao-black" style="background: linear-gradient(135deg, #232526, #414345);">
<div style="display: flex; justify-content: space-between; align-items: center;">
<h4>Brazo Black</h4>
<i class="fab fa-cc-mastercard" style="font-size: 32px;"></i>
</div>
<div class="cartao-numero">•••• •••• •••• 9876</div>
<div style="display: flex; justify-content: space-between;">
<span id="cartao-black-nome"></span>
<span>08/29</span>
</div>
<div style="margin-top:10px;">
<button class="btn" id="btn-bloquear-black" onclick="bloquearCartao('black')">
<i class="fas fa-lock"></i> Bloquear
                    </button>
<button class="btn hidden" id="btn-desbloquear-black" onclick="desbloquearCartao('black')">
<i class="fas fa-unlock"></i> Desbloquear
                    </button>
</div>
<div class="cartao-descricao">💳 Limite inicial: R$ 20.000 | Benefícios: Sala VIP em aeroportos, seguro viagem, cashback em todas as compras. Uso: Cartão premium para clientes que buscam exclusividade.</div></div>
</div>
</div>
<div class="tela hidden" id="tela-emprestimo">
<div class="card">
<div class="back" onclick="voltarMenuPrincipal()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Empréstimo</h2>
<p>Simule ou solicite seu empréstimo aqui.</p>
<form onsubmit="return simularEmprestimo(event)">
<input id="valor-emprestimo" placeholder="Valor do Empréstimo (R$)" required="" type="number"/>
<input id="prazo-emprestimo" placeholder="Prazo (meses)" required="" type="number"/>
<input id="juros-emprestimo" placeholder="Taxa de Juros (% ao mês)" required="" type="number"/>
<button class="btn" type="submit">
<i class="fas fa-calculator"></i> Simular
                </button>
</form>
<div id="resultado-emprestimo" style="margin-top:20px;"></div>
</div>
</div>
<div class="tela hidden" id="tela-boleto">
<div class="card">
<div class="back" onclick="voltarMenuPrincipal()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Boleto</h2>
<p>Pague ou gere boletos facilmente.</p>
<button class="btn" onclick="gerarBoleto()"><i class="fas fa-barcode"></i> Gerar Boleto</button>
<button class="btn" onclick="pagarBoleto()"><i class="fas fa-money-check-alt"></i> Pagar Boleto</button>
</div>
</div>
<div class="tela hidden" id="tela-recarga">
<div class="card">
<div class="back" onclick="voltarMenuPrincipal()">
<i class="fas fa-arrow-left"></i> Voltar
            </div>
<h2>Recarga</h2>
<p>Faça recarga de celular ou serviços.</p>
<form onsubmit="return realizarRecarga(event)">
<input id="numero-recarga" placeholder="Número do celular ou Bilhete Único" required="" type="tel"/>
<input id="valor-recarga" placeholder="Valor da Recarga (R$)" required="" type="number"/>
<select id="servico-recarga" required="">
<option value="">Selecione o serviço</option>
<option value="Celular (Cartão Roxo)">Celular (Cartão Roxo)</option>
<option value="Celular (Cartão Black)">Celular (Cartão Black)</option>
<option value="Bilhete Unico">Bilhete Único</option>
</select>
<button class="btn" type="submit">
<i class="fas fa-bolt"></i> Recarregar
                </button>
</form>
<div id="msg-recarga" style="margin-top:20px;"></div>
</div>
</div>
</div>
<div class="modal-overlay hidden" id="modal-boleto">
<div class="modal-content card">
<span class="modal-close" onclick="fecharModalBoleto()">×</span>
<h2>Pagamento de Boleto</h2>
<p style="text-align: center; color: var(--white-fade);">Use o QR Code ou o código de barras abaixo.</p>
<div class="boleto-visual">
<svg id="qrcode" viewbox="0 0 256 256" xmlns="http://www.w3.org/2000/svg"><path d="m140 140h-28v-28h28zm-84 56h28v-28h-28zm56 28h-28v28h28zm-28-28h-28v28h28zm-28-28h28v-28h-28zm56-28h28v28h-28zm-28 0h-28v-28h28zm-28-28h28v-28h-28zm56 0h28v-28h-28zm56 112h28v-28h-28zm-28-28h28v-28h-28zm28 0h28v-28h-28zm-28-28h28v-28h-28zm28-28h28v-28h-28zm-56-28h28v-28h-28zm28 0h28v-28h-28zm-84-56h28v-28h-28zm28 0h28v-28h-28zm28 0h28v-28h-28zm-84-56h28v-28h-28zm28 0h28v-28h-28z" fill-rule="evenodd"></path></svg>
<svg id="barcode" viewbox="0 0 200 100" xmlns="http://www.w3.org/2000/svg"><path d="M1 0h2v100H1zm3 0h1v100H4zm3 0h2v100H7zm2 0h1v100H9zm3 0h2v100h-2zm1 0h1v100h-1zm3 0h3v100h-3zm2 0h1v100h-1zm1 0h1v100h-1zm3 0h2v100h-2zm3 0h1v100h-1zm1 0h2v100h-2zm3 0h3v100h-3zm1 0h1v100h-1zm3 0h1v100h-1zm2 0h1v100h-1zm3 0h2v100h-2zm1 0h1v100h-1zm3 0h3v100h-3zm2 0h1v100h-1zm1 0h1v100h-1zm3 0h2v100h-2zm3 0h1v100h-1zm1 0h2v100h-2zm3 0h3v100h-3zm1 0h1v100h-1zm3 0h1v100h-1zm2 0h1v100h-1zm3 0h2v100h-2zm1 0h1v100h-1zm3 0h3v100h-3zm2 0h1v100h-1zm1 0h1v100h-1zm3 0h2v100h-2zm3 0h1v100h-1zm1 0h2v100h-2zm3 0h3v100h-3zm1 0h1v100h-1zm3 0h1v100h-1zm2 0h1v100h-1zm3 0h2v100h-2zm1 0h1v100h-1zm3 0h3v100h-3zm2 0h1v100h-1zm1 0h1v100h-1zm3 0h2v100h-2zm3 0h1v100h-1zm1 0h2v100h-2zm3 0h3v100h-3zm1 0h1v100h-1z" fill="#000"></path></svg>
<p class="codigo-numerico" id="codigo-boleto">84610000000 8 12340123456 0 12340123456 7 12340123456 3</p>
</div>
<button class="btn" onclick="copiarCodigo()"><i class="fas fa-copy"></i> Copiar Código</button>
</div>
</div>
<script>
    // === DADOS DA CONTA ===
    let usuarioCadastrado = null;
    let saldoAtual = 15750.00;
    let cartoesEstado = { roxo: false, black: false }; // false = desbloqueado, true = bloqueado
    const profileFields = ['nome', 'email', 'cpf', 'telefone', 'nascimento'];
    
    // === FUNÇÕES DE NAVEGAÇÃO E UI ===
    
    function formatarMoeda(valor) {
        return valor.toLocaleString('pt-BR', { style: 'currency', currency: 'BRL' });
    }
    
    function atualizarSaldoUI() {
        const saldoElement = document.getElementById('saldo-valor');
        if (saldoElement) {
            saldoElement.textContent = formatarMoeda(saldoAtual);
        }
    }

    function mostrarTela(telaId) {
        const telas = document.querySelectorAll('.tela');
        telas.forEach(tela => tela.classList.add('hidden'));
        document.getElementById(telaId).classList.remove('hidden');
    }

    function atualizarDadosUI() {
        if (usuarioCadastrado) {
            document.getElementById('nome-usuario').textContent = usuarioCadastrado.nome;
            profileFields.forEach(field => {
                const viewElement = document.getElementById(`view-perfil-${field}`);
                if (viewElement) {
                    viewElement.textContent = usuarioCadastrado[field] || '';
                }
            });
            document.getElementById('cartao-roxo-nome').textContent = usuarioCadastrado.nome.toUpperCase();
            document.getElementById('cartao-black-nome').textContent = usuarioCadastrado.nome.toUpperCase();
        }
    }

    function mostrarLogin() { mostrarTela('tela-login'); }
    function mostrarCadastro() { mostrarTela('tela-cadastro'); }
    function voltarTelaInicial() { mostrarTela('tela-inicial'); }
    function mostrarMenuPrincipal() {
        if (usuarioCadastrado) {
            atualizarDadosUI();
        }
        atualizarSaldoUI();
        mostrarTela('menu-principal');
    }
    function mostrarEmprestimo() { mostrarTela('tela-emprestimo'); }
    function mostrarBoleto() { mostrarTela('tela-boleto'); }
    function mostrarRecarga() { mostrarTela('tela-recarga'); }
    function voltarMenuPrincipal() { mostrarTela('menu-principal'); }
    function mostrarPerfil() {
        if(usuarioCadastrado) {
            atualizarDadosUI();
            setProfileEditMode(false);
        }
        mostrarTela('tela-perfil'); 
    }
    function mostrarTransferencias() { mostrarTela('tela-transferencias'); }
    function mostrarExtrato() { mostrarTela('tela-extrato'); }
    function mostrarConfiguracao() { mostrarTela('tela-configuracao'); }
    function mostrarCartoes() { mostrarTela('tela-cartoes'); }


    // === FUNÇÕES DE LÓGICA DO APP ===

    function fazerLogin(event) {
        event.preventDefault();
        const emailInput = document.getElementById('login-email').value;
        const senhaInput = document.getElementById('login-senha').value;
        const msgLogin = document.getElementById('msg-login');
        
        if (usuarioCadastrado && usuarioCadastrado.email === emailInput && usuarioCadastrado.senha === senhaInput) {
            msgLogin.innerHTML = `<div class="msg sucesso">Login bem-sucedido! Redirecionando...</div>`;
            setTimeout(() => {
                mostrarMenuPrincipal();
                msgLogin.innerHTML = '';
            }, 1000);
        } else {
            msgLogin.innerHTML = `<div class="msg erro">Email ou senha incorretos.</div>`;
        }
        return false;
    }

    function fazerCadastro(event) {
        event.preventDefault();
        const nome = document.getElementById('cadastro-nome').value;
        const email = document.getElementById('cadastro-email').value;
        const telefone = document.getElementById('cadastro-telefone').value;
        const cpf = document.getElementById('cadastro-cpf').value;
        const nascimento = document.getElementById('cadastro-nascimento').value;
        const senha = document.getElementById('cadastro-senha').value;
        const confirmarSenha = document.getElementById('cadastro-confirmar-senha').value;
        const msgCadastro = document.getElementById('msg-cadastro');

        if (senha !== confirmarSenha) {
            msgCadastro.innerHTML = `<div class="msg erro">As senhas não coincidem.</div>`;
            return false;
        }
        
        usuarioCadastrado = {
            nome: nome,
            email: email,
            telefone: telefone,
            cpf: cpf,
            nascimento: nascimento,
            senha: senha
        };
        salvarUsuario();

        msgCadastro.innerHTML = `<div class="msg sucesso">Cadastro realizado com sucesso! Redirecionando...</div>`;
        setTimeout(() => {
            mostrarMenuPrincipal();
            msgCadastro.innerHTML = '';
        }, 1500);

        return false;
    }

    function logout() {
        voltarTelaInicial();
    }

    function togglePassword(inputId) {
        const input = document.getElementById(inputId);
        const icon = input.nextElementSibling;
        if (input.type === 'password') {
            input.type = 'text';
            icon.classList.remove('fa-eye');
            icon.classList.add('fa-eye-slash');
        } else {
            input.type = 'password';
            icon.classList.remove('fa-eye-slash');
            icon.classList.add('fa-eye');
        }
    }

    function realizarTransferencia(event) {
        event.preventDefault();
        const valorTransferenciaInput = document.getElementById('valor-transferencia');
        const msgTransferencia = document.getElementById('msg-transferencia');

        const valor = parseFloat(valorTransferenciaInput.value);

        if (isNaN(valor) || valor <= 0) {
            msgTransferencia.innerHTML = `<div class="msg erro">Por favor, insira um valor de transferência válido.</div>`;
            return false;
        }

        if (valor > saldoAtual) {
            msgTransferencia.innerHTML = `<div class="msg erro">Saldo insuficiente para realizar a transferência.</div>`;
            return false;
        }

        saldoAtual -= valor;
        atualizarSaldoUI();

        msgTransferencia.innerHTML = `<div class="msg sucesso">Transferência de ${formatarMoeda(valor)} realizada com sucesso!</div>`;

        setTimeout(() => {
            msgTransferencia.innerHTML = '';
        }, 3000);
        
        event.target.reset(); // Limpa o formulário

        return false;
    }

    // Funções das abas de Configurações
    function showTab(tabName) {
        const tabs = document.querySelectorAll('#tela-configuracao > .card > .tab-content');
        tabs.forEach(tab => tab.classList.remove('active'));
        document.getElementById(`tab-${tabName}`).classList.add('active');

        const tabBtns = document.querySelectorAll('#tela-configuracao > .card > .tab-buttons .tab-btn');
        tabBtns.forEach(btn => btn.classList.remove('active'));
        document.querySelector(`.tab-btn[onclick="showTab('${tabName}')"]`).classList.add('active');
    }

    function showSupportTab(tabName) {
        const tabs = document.querySelectorAll('#tab-suporte .tab-content');
        tabs.forEach(tab => tab.classList.remove('active'));
        document.getElementById(`support-tab-${tabName}`).classList.add('active');

        const tabBtns = document.querySelectorAll('#tab-suporte .tab-buttons .tab-btn');
        tabBtns.forEach(btn => btn.classList.remove('active'));
        
        const activeButton = document.querySelector(`#tab-suporte .tab-btn[onclick="showSupportTab('${tabName}')"]`);
        if (activeButton) {
            activeButton.classList.add('active');
        }
    }

    // Funções de edição de perfil
    function setProfileEditMode(isEditing) {
        profileFields.forEach(field => {
            const viewElement = document.getElementById(`view-perfil-${field}`);
            const editElement = document.getElementById(`edit-perfil-${field}`);

            if (viewElement && editElement) {
                if (isEditing) {
                    editElement.value = viewElement.textContent;
                    viewElement.classList.add('hidden');
                    editElement.classList.remove('hidden');
                } else {
                    viewElement.classList.remove('hidden');
                    editElement.classList.add('hidden');
                }
            }
        });

        document.getElementById('btn-editar-perfil').classList.toggle('hidden', isEditing);
        document.getElementById('btn-salvar-perfil').classList.toggle('hidden', !isEditing);
    }

    function editarPerfil() {
        setProfileEditMode(true);
    }

    function salvarPerfil() {
        const msgPerfil = document.getElementById('msg-perfil');
        msgPerfil.innerHTML = '';

        const novoCpf = document.getElementById('edit-perfil-cpf').value;
        const novoTelefone = document.getElementById('edit-perfil-telefone').value;
        const novoNascimento = document.getElementById('edit-perfil-nascimento').value;

        if (!validarCPF(novoCpf)) {
            msgPerfil.innerHTML = `<div class="msg erro">CPF deve conter exatamente 11 dígitos numéricos.</div>`;
            return;
        }
        if (!validarTelefone(novoTelefone)) {
            msgPerfil.innerHTML = `<div class="msg erro">Telefone inválido. Use o formato (XX) XXXXX-XXXX.</div>`;
            return;
        }
        if (!validarNascimento(novoNascimento)) {
            msgPerfil.innerHTML = `<div class="msg erro">Ano de nascimento deve estar entre 1900 e 2020.</div>`;
            return;
        }

        if (usuarioCadastrado) {
            profileFields.forEach(field => {
                const editElement = document.getElementById(`edit-perfil-${field}`);
                if (editElement) {
                    usuarioCadastrado[field] = editElement.value;
                }
            });
            salvarUsuario();
            atualizarDadosUI();
        }
        setProfileEditMode(false);
        
        msgPerfil.innerHTML = `<div class="msg sucesso">Perfil atualizado com sucesso!</div>`;
        setTimeout(() => { msgPerfil.innerHTML = ''; }, 3000);
    }

    // Funções de demonstração
    function salvarNotificacoes() { alert('Preferências de notificação salvas.'); }
    function configurarSeguranca() { alert('Configurações de segurança salvas.'); }
    function salvarPrivacidade() { alert('Configurações de privacidade salvas.'); }
    
    function ligar() { alert('Chamando...'); }
    function enviarEmail() { alert('Abrindo cliente de email...'); }
    function whatsapp() { alert('Abrindo WhatsApp...'); }


    function simularEmprestimo(event) {
        event.preventDefault();
        const valor = parseFloat(document.getElementById('valor-emprestimo').value);
        const prazo = parseInt(document.getElementById('prazo-emprestimo').value);
        const juros = parseFloat(document.getElementById('juros-emprestimo').value) / 100;

        if (valor > 0 && prazo > 0 && juros >= 0) {
            const parcela = (valor * juros) / (1 - Math.pow(1 + juros, -prazo));
            document.getElementById('resultado-emprestimo').innerHTML = 
                `<div class="msg sucesso">Valor da Parcela: ${formatarMoeda(parcela)} (${prazo}x)</div>`;
        } else {
            document.getElementById('resultado-emprestimo').innerHTML = 
                `<div class="msg erro">Preencha todos os campos corretamente.</div>`;
        }
        return false;
    }

    // Cartão bloquear/desbloquear
    function bloquearCartao(tipo) {
        cartoesEstado[tipo] = true;
        document.getElementById(`btn-bloquear-${tipo}`).classList.add('hidden');
        document.getElementById(`btn-desbloquear-${tipo}`).classList.remove('hidden');
        document.getElementById(`cartao-${tipo}`).style.opacity = '0.5';
        alert(`Cartão Brazo ${tipo === 'roxo' ? 'Roxo' : 'Black'} bloqueado.`);
    }
    function desbloquearCartao(tipo) {
        cartoesEstado[tipo] = false;
        document.getElementById(`btn-bloquear-${tipo}`).classList.remove('hidden');
        document.getElementById(`btn-desbloquear-${tipo}`).classList.add('hidden');
        document.getElementById(`cartao-${tipo}`).style.opacity = '1';
        alert(`Cartão Brazo ${tipo === 'roxo' ? 'Roxo' : 'Black'} desbloqueado.`);
    }

    // Validações extras
    function validarCPF(cpf) {
        return /^\d{11}$/.test(cpf.replace(/\D/g, ''));
    }

    function validarTelefone(tel) {
        return /^\d{10,11}$/.test(tel.replace(/\D/g, ''));
    }

    function validarSenha(senha) {
        return /^(?=.*[A-Za-z])(?=.*[0-9])(?=.*[^A-Za-z0-9]).{4,6}$/.test(senha);
    }

    function validarNascimento(data) {
        const ano = new Date(data).getFullYear();
        return ano >= 1900 && ano <= 2020;
    }

    // Sobrescrevendo cadastro com validações
    const _fazerCadastroOriginal = fazerCadastro;
    fazerCadastro = function(event) {
        event.preventDefault();
        const cpf = document.getElementById('cadastro-cpf').value;
        const telefone = document.getElementById('cadastro-telefone').value;
        const nascimento = document.getElementById('cadastro-nascimento').value;
        const senha = document.getElementById('cadastro-senha').value;
        const confirmarSenha = document.getElementById('cadastro-confirmar-senha').value;
        const msgCadastro = document.getElementById('msg-cadastro');

        if (!validarCPF(cpf)) {
            msgCadastro.innerHTML = `<div class="msg erro">CPF deve conter exatamente 11 dígitos numéricos.</div>`;
            return false;
        }
        if (!validarTelefone(telefone)) {
            msgCadastro.innerHTML = `<div class="msg erro">Telefone inválido. Use o formato (XX) XXXXX-XXXX.</div>`;
            return false;
        }
        if (!validarNascimento(nascimento)) {
            msgCadastro.innerHTML = `<div class="msg erro">Ano de nascimento deve estar entre 1900 e 2020.</div>`;
            return false;
        }
        if (!validarSenha(senha)) {
            msgCadastro.innerHTML = `<div class="msg erro">Senha deve ter entre 4 e 6 caracteres, incluindo letra, número e caractere especial.</div>`;
            return false;
        }
        if (senha !== confirmarSenha) {
            msgCadastro.innerHTML = `<div class="msg erro">As senhas não coincidem.</div>`;
            return false;
        }
        return _fazerCadastroOriginal(event);
    };

    // ===== Persistência de conta =====
    window.addEventListener("load", () => {
        const userData = localStorage.getItem("usuarioCadastrado");
        if (userData) {
            usuarioCadastrado = JSON.parse(userData);
        }
    });

    function salvarUsuario() {
        if (usuarioCadastrado) {
            localStorage.setItem("usuarioCadastrado", JSON.stringify(usuarioCadastrado));
        }
    }

    // Atualizar cadastro para salvar no localStorage
    const _fazerCadastroPersist = fazerCadastro;
    fazerCadastro = function(event) {
        const result = _fazerCadastroPersist(event);
        if(usuarioCadastrado) salvarUsuario();
        return result;
    };

    // ===== Alterar Senha =====
    function alterarSenha(event) {
        event.preventDefault();
        const atual = document.getElementById('senha-atual').value;
        const nova = document.getElementById('nova-senha').value;
        const confirmar = document.getElementById('confirmar-nova-senha').value;
        if (!usuarioCadastrado || usuarioCadastrado.senha !== atual) {
            alert("Senha atual incorreta.");
            return false;
        }
        if (nova !== confirmar) {
            alert("A nova senha e a confirmação não coincidem.");
            return false;
        }
        if (!validarSenha(nova)) {
            alert("A senha deve ter entre 4 e 6 caracteres, incluir letra, número e caractere especial.");
            return false;
        }
        usuarioCadastrado.senha = nova;
        salvarUsuario();
        alert("Senha alterada com sucesso.");
        document.getElementById('senha-atual').value = '';
        document.getElementById('nova-senha').value = '';
        document.getElementById('confirmar-nova-senha').value = '';
        return false;
    }

    // ===== NOVA IA DO SUPORTE =====
    function obterRespostaIA(mensagem) {
        const msg = mensagem.toLowerCase();

        if (msg.includes('saldo') || msg.includes('ver meu dinheiro')) {
            return `O seu saldo atual é de ${formatarMoeda(saldoAtual)}. Você pode ver mais detalhes na seção "Extrato".`;
        }
        if (msg.includes('pix') || msg.includes('transferir') || msg.includes('transferência')) {
            return 'Para realizar uma transferência ou PIX, vá ao Menu Principal e clique na opção "Transferências".';
        }
        if (msg.includes('bloquear') && msg.includes('cartão')) {
            return 'Você pode bloquear seus cartões na seção "Cartões". Se precisar de ajuda, digite "falar com atendente".';
        }
        if (msg.includes('fatura') || msg.includes('cartão de crédito')) {
            return 'A fatura do seu cartão de crédito pode ser consultada na seção "Cartões". Lá você encontrará todos os detalhes de suas compras.';
        }
        if (msg.includes('empréstimo')) {
            return 'Para simular ou solicitar um empréstimo, acesse a opção "Empréstimo" no menu principal.';
        }
        if (msg.includes('atendente') || msg.includes('humano') || msg.includes('ajuda')) {
            return 'Um de nossos atendentes entrará em contato em breve. Por favor, aguarde.';
        }
        if (msg.includes('oi') || msg.includes('olá') || msg.includes('bom dia')) {
            return 'Olá! Como posso te ajudar hoje?';
        }

        return 'Não entendi sua pergunta. Poderia tentar reformular? Você pode pedir ajuda para ver o "saldo", fazer "pix", "bloquear cartão" ou "falar com atendente".';
    }

    // ===== Suporte - com IA integrada =====
    function enviarMensagem() {
        const input = document.querySelector('#tab-suporte #chat-input');
        const chatMessages = document.querySelector('#tab-suporte #chat-messages');

        if (input && input.value.trim() !== '') {
            const userMessage = input.value;
            const messageDiv = document.createElement('div');
            messageDiv.classList.add('message', 'user');
            messageDiv.innerHTML = `<div class="text">${userMessage}</div><div class="time">Agora</div>`;
            chatMessages.appendChild(messageDiv);

            const respostaIA = obterRespostaIA(userMessage);

            setTimeout(() => {
                const supportDiv = document.createElement('div');
                supportDiv.classList.add('message', 'support');
                supportDiv.innerHTML = `<div class="text">${respostaIA}</div><div class="time">Agora</div>`;
                chatMessages.appendChild(supportDiv);
                chatMessages.scrollTop = chatMessages.scrollHeight;
            }, 1000);

            chatMessages.scrollTop = chatMessages.scrollHeight;
            input.value = '';
        }
    }


    // ===== Recarga com opções de cartão =====
    function realizarRecarga(event) {
        event.preventDefault();
        const numero = document.getElementById('numero-recarga').value;
        const valor = parseFloat(document.getElementById('valor-recarga').value);
        const servico = document.getElementById('servico-recarga').value;
        const msgRecarga = document.getElementById('msg-recarga');

        if (!servico) {
            msgRecarga.innerHTML = `<div class="msg erro">Selecione um serviço para efetuar a recarga.</div>`;
            return false;
        }
        if (isNaN(valor) || valor < 1 || valor > 500) {
            msgRecarga.innerHTML = `<div class="msg erro">O valor da recarga deve ser entre R$ 1 e R$ 500.</div>`;
            return false;
        }

        let mensagemSucesso = '';
        if (servico === 'Bilhete Unico') {
            mensagemSucesso = `Recarga de ${formatarMoeda(valor)} para o Bilhete Único (${numero}) foi realizada com sucesso!`;
        } else {
            mensagemSucesso = `Recarga de ${formatarMoeda(valor)} para o número ${numero} (${servico}) foi realizada com sucesso!`;
        }
        
        msgRecarga.innerHTML = `<div class="msg sucesso">${mensagemSucesso}</div>`;
        return false;
    };

    // ===== Filtro de extrato (FUNÇÃO CORRIGIDA) =====
    function filtrarExtrato() {
        const mesSelecionado = document.getElementById('filtro-mes').value;
        if (!mesSelecionado) {
            alert("Por favor, selecione um mês para filtrar.");
            return;
        }
        const transacoes = document.querySelectorAll('#extrato-lista .transaction-item');
        let transacoesEncontradas = 0;
        const msgSemResultados = document.getElementById('msg-sem-resultados');
        if (msgSemResultados) {
            msgSemResultados.remove();
        }

        transacoes.forEach(transacao => {
            const dataElemento = transacao.querySelector('small');
            if (dataElemento) {
                const dataTexto = dataElemento.textContent.split(' - ')[0];
                const partesData = dataTexto.split('/');
                const anoMesTransacao = `${partesData[2]}-${partesData[1]}`;

                if (anoMesTransacao === mesSelecionado) {
                    transacao.style.display = 'flex';
                    transacoesEncontradas++;
                } else {
                    transacao.style.display = 'none';
                }
            }
        });

        if (transacoesEncontradas === 0) {
            const extratoLista = document.getElementById('extrato-lista');
            const mensagem = document.createElement('div');
            mensagem.id = 'msg-sem-resultados';
            mensagem.className = 'msg info';
            mensagem.textContent = 'Nenhuma transação encontrada para o mês selecionado.';
            extratoLista.appendChild(mensagem);
        }
    }


    // ===== Boleto - complementos =====
    function gerarBoleto() {
        alert("Boleto de cobrança gerado com sucesso. Código de barras: 846100000008123401234560123401234567123401234563");
    }

    function pagarBoleto() {
        document.getElementById('modal-boleto').classList.remove('hidden');
    }

    function fecharModalBoleto() {
        document.getElementById('modal-boleto').classList.add('hidden');
    }

    function copiarCodigo() {
        const codigoElement = document.getElementById('codigo-boleto');
        const codigo = codigoElement.textContent.replace(/\s/g, '');
        
        navigator.clipboard.writeText(codigo).then(() => {
            alert('Código copiado para a área de transferência!');
        }).catch(err => {
            console.error('Erro ao copiar o código: ', err);
            alert('Não foi possível copiar o código.');
        });
    }

</script>
</body>
</html>
