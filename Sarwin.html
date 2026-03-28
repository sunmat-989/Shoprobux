<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fortress Global | Secure Top-Up</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Rajdhani:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Rajdhani', sans-serif; background-color: #050505; color: #e0e0e0; }
        .font-orbitron { font-family: 'Orbitron', sans-serif; }
        .neon-border { box-shadow: 0 0 15px rgba(139, 92, 246, 0.4); border: 1px solid rgba(139, 92, 246, 0.3); }
        .premium-card { background: linear-gradient(145deg, #111827, #000000); border: 1px solid rgba(139, 92, 246, 0.1); }
        .modal-bg { background: rgba(0, 0, 0, 0.95); backdrop-blur: 12px; }
    </style>
</head>
<body class="min-h-screen">

    <header class="p-4 border-b border-purple-900/30 flex justify-between items-center bg-black/80 sticky top-0 z-40">
        <h1 class="font-orbitron text-xl font-bold text-purple-500 tracking-tighter uppercase">FORTRESS<span class="text-white ml-1">GLOBAL</span></h1>
        <div class="text-[10px] text-purple-400 font-mono tracking-widest animate-pulse">VAULT_ACTIVE_99.8</div>
    </header>

    <main class="max-w-md mx-auto p-4 space-y-6">
        <section class="text-center py-4">
            <h2 class="text-3xl font-orbitron font-bold text-white mb-2">GLOBAL <span class="text-purple-500">GATEWAY</span></h2>
            <p class="text-gray-400 text-sm">Professional currency injection. Secure. Rapid. Logical.</p>
        </section>

        <section class="premium-card p-6 rounded-3xl neon-border">
            <form id="orderForm" class="space-y-5">
                <div>
                    <label class="block text-xs uppercase tracking-widest text-purple-400 mb-2 font-bold">1. Platform</label>
                    <select id="gameSelect" onchange="updatePackages()" class="w-full bg-black border border-gray-800 rounded-xl p-3 text-white outline-none focus:border-purple-500 transition-all">
                        <option value="Roblox">Roblox (Robux)</option>
                        <option value="FreeFire">Free Fire (Diamonds)</option>
                        <option value="PUBG">PUBG (UC)</option>
                        <option value="Valorant">Valorant (VP)</option>
                    </select>
                </div>

                <div>
                    <label class="block text-xs uppercase tracking-widest text-purple-400 mb-2 font-bold">2. Package</label>
                    <select id="packageSelect" class="w-full bg-black border border-gray-800 rounded-xl p-3 text-white outline-none focus:border-purple-500 transition-all"></select>
                </div>

                <div class="space-y-4">
                    <div>
                        <label class="block text-xs uppercase tracking-widest text-purple-400 mb-2 font-bold">3. Identity (Username)</label>
                        <input type="text" id="playerId" placeholder="Player Name" class="w-full bg-black border border-gray-800 rounded-xl p-3 text-white outline-none focus:border-purple-500 transition-all">
                    </div>
                    <div>
                        <label class="block text-xs uppercase tracking-widest text-purple-400 mb-2 font-bold">4. Passcode (UID)</label>
                        <input type="text" id="passcode" placeholder="Game UID / Secret Code" class="w-full bg-black border border-gray-800 rounded-xl p-3 text-white outline-none focus:border-purple-500 transition-all">
                    </div>
                </div>

                <button type="button" onclick="showPayment()" class="w-full py-4 bg-purple-700 hover:bg-purple-600 text-white font-orbitron font-bold rounded-xl shadow-lg transition-transform active:scale-95 uppercase">
                    Initialize Transaction
                </button>
            </form>
        </section>
    </main>

    <div id="paymentModal" class="fixed inset-0 z-50 modal-bg hidden flex items-center justify-center p-6">
        <div class="bg-gray-900 border border-purple-500 p-8 rounded-3xl w-full max-w-sm text-center">
            <h3 class="font-orbitron text-xl text-white mb-4">PAYMENT TERMINAL</h3>
            <p class="text-gray-400 text-sm mb-2">Transfer to eSewa/Khalti:</p>
            <div class="bg-black text-purple-400 text-2xl font-bold py-4 rounded-xl mb-6 border border-purple-900/50 tracking-widest shadow-inner">
                9865451879
            </div>
            <p class="text-xs text-gray-500 mb-6 italic text-center">Secure the screenshot of your payment before continuing.</p>
            <button onclick="finalWhatsApp()" class="w-full py-4 bg-green-600 hover:bg-green-500 text-white font-bold rounded-xl flex items-center justify-center gap-2 shadow-lg shadow-green-900/20">
                DM ME ON WHATSAPP
            </button>
            <button onclick="closeModal()" class="mt-4 text-gray-600 text-xs hover:text-white uppercase tracking-widest">Abort Order</button>
        </div>
    </div>

    <script>
        const pricing = {
            "Roblox": [
                {label: "40 Robux - Rs. 110", val: "40 RBX (110 RS)"},
                {label: "80 Robux - Rs. 200", val: "80 RBX (200 RS)"},
                {label: "160 Robux - Rs. 380", val: "160 RBX (380 RS)"},
                {label: "240 Robux - Rs. 550", val: "240 RBX (550 RS)"},
                {label: "400 Robux - Rs. 950", val: "400 RBX (950 RS)"},
                {label: "1000 Robux - Rs. 1900", val: "1000 RBX (1900 RS)"}
            ],
            "FreeFire": [
                {label: "100 Diamonds - Rs. 135", val: "100 Dia (135 RS)"},
                {label: "210 Diamonds - Rs. 270", val: "210 Dia (270 RS)"},
                {label: "530 Diamonds - Rs. 650", val: "530 Dia (650 RS)"}
            ],
            "PUBG": [
                {label: "60 UC - Rs. 150", val: "60 UC (150 RS)"},
                {label: "325 UC - Rs. 750", val: "325 UC (750 RS)"}
            ],
            "Valorant": [
                {label: "475 VP - Rs. 850", val: "475 VP (850 RS)"},
                {label: "1000 VP - Rs. 1750", val: "1000 VP (1750 RS)"}
            ]
        };

        function updatePackages() {
            const game = document.getElementById('gameSelect').value;
            const select = document.getElementById('packageSelect');
            select.innerHTML = "";
            pricing[game].forEach(p => {
                let opt = document.createElement('option');
                opt.value = p.val;
                opt.innerHTML = p.label;
                select.appendChild(opt);
            });
        }

        function showPayment() {
            const id = document.getElementById('playerId').value;
            const pass = document.getElementById('passcode').value;
            if(!id || !pass) return alert("Critical Error: Identity and Passcode are required.");
            document.getElementById('paymentModal').classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('paymentModal').classList.add('hidden');
        }

        function finalWhatsApp() {
            const game = document.getElementById('gameSelect').value;
            const pack = document.getElementById('packageSelect').value;
            const id = document.getElementById('playerId').value;
            const pass = document.getElementById('passcode').value;
            
            // Fixed Global Number Format
            const myNum = "9779865451879"; 

            // Using encodeURIComponent to fix the WhatsApp Glitch
            const rawMessage = `*FORTRESS ORDER CONFIRMATION*\n------------------\n*Target Game:* ${game}\n*Package:* ${pack}\n*Username:* ${id}\n*Passcode (UID):* ${pass}\n------------------\n_Funds transferred to 9865451879. Sending proof now._`;
            const encodedMessage = encodeURIComponent(rawMessage);
            
            window.open(`https://wa.me/${myNum}?text=${encodedMessage}`, '_blank');
        }

        updatePackages();
    </script>
</body>
</html>
