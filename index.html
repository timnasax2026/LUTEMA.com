<!DOCTYPE html>
<html lang="sw">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUTEMA Jr - Calculator & Pesa</title>
    <style>
        :root {
            --primary-color: #2563eb;
            --secondary-color: #1e293b;
            --accent-color: #10b981;
            --bg-color: #f8fafc;
            --text-color: #334155;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
        }

        header h1 {
            color: var(--secondary-color);
            margin-bottom: 5px;
            font-size: 2.5rem;
        }

        .url-box {
            background: #e2e8f0;
            padding: 10px;
            border-radius: 8px;
            font-size: 0.9rem;
            margin-bottom: 20px;
            border: 1px dashed #94a3b8;
        }

        .main-wrapper {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            max-width: 1000px;
            width: 100%;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
            width: 320px;
            border: 1px solid #f1f5f9;
        }

        h3 {
            margin-top: 0;
            color: var(--secondary-color);
            border-bottom: 2px solid #f1f5f9;
            padding-bottom: 10px;
            text-align: center;
        }

        /* Calculator UI */
        #display {
            width: 100%;
            height: 60px;
            background: #f1f5f9;
            border: none;
            border-radius: 10px;
            margin-bottom: 15px;
            font-size: 28px;
            text-align: right;
            padding: 10px;
            box-sizing: border-box;
            color: var(--secondary-color);
            font-weight: bold;
        }

        .buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 12px;
        }

        button {
            padding: 18px;
            font-size: 18px;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            transition: all 0.2s;
            background: #f8fafc;
            font-weight: 600;
        }

        button:hover {
            background: #e2e8f0;
            transform: translateY(-2px);
        }

        .op-btn { color: var(--primary-color); background: #eff6ff; }
        .clear-btn { color: #ef4444; background: #fef2f2; }
        .equal-btn { 
            background: var(--primary-color); 
            color: white; 
            grid-column: span 2;
        }
        .equal-btn:hover { background: #1d4ed8; color: white; }

        /* Transfer UI */
        .input-group {
            margin-bottom: 15px;
            text-align: left;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-size: 0.85rem;
            font-weight: bold;
        }

        input {
            width: 100%;
            padding: 14px;
            border: 1px solid #cbd5e1;
            border-radius: 10px;
            box-sizing: border-box;
            font-size: 1rem;
        }

        .submit-btn {
            width: 100%;
            background: var(--accent-color);
            color: white;
            padding: 15px;
            margin-top: 10px;
        }
        
        .submit-btn:hover { background: #059669; color: white; }

        footer {
            margin-top: 50px;
            font-size: 0.8rem;
            color: #94a3b8;
        }
    </style>
</head>
<body>

    <header>
        <h1>LUTEMA Jr</h1>
        <div class="url-box" id="siteUrl">🌐 URL: loading...</div>
    </header>

    <div class="main-wrapper">
        <div class="card">
            <h3>Calculator</h3>
            <input type="text" id="display" readonly placeholder="0">
            <div class="buttons">
                <button class="clear-btn" onclick="clearDisplay()">AC</button>
                <button class="op-btn" onclick="deleteLast()">⌫</button>
                <button class="op-btn" onclick="appendToDisplay('/')">÷</button>
                <button class="op-btn" onclick="appendToDisplay('*')">×</button>
                
                <button onclick="appendToDisplay('7')">7</button>
                <button onclick="appendToDisplay('8')">8</button>
                <button onclick="appendToDisplay('9')">9</button>
                <button class="op-btn" onclick="appendToDisplay('-')">−</button>
                
                <button onclick="appendToDisplay('4')">4</button>
                <button onclick="appendToDisplay('5')">5</button>
                <button onclick="appendToDisplay('6')">6</button>
                <button class="op-btn" onclick="appendToDisplay('+')">+</button>
                
                <button onclick="appendToDisplay('1')">1</button>
                <button onclick="appendToDisplay('2')">2</button>
                <button onclick="appendToDisplay('3')">3</button>
                <button class="equal-btn" onclick="calculate()">=</button>
                
                <button onclick="appendToDisplay('0')" style="grid-column: span 2;">0</button>
                <button onclick="appendToDisplay('.')">.</button>
            </div>
        </div>

        <div class="card">
            <h3>Tuma Pesa</h3>
            <div id="step1">
                <div class="input-group">
                    <label>Namba ya Nchi</label>
                    <input type="text" id="countryCode" placeholder="Mfano: +255">
                </div>
                <div class="input-group">
                    <label>Kiasi cha Kutuma</label>
                    <input type="number" id="amount" placeholder="Weka kiasi">
                </div>
                <button class="submit-btn" onclick="nextStep()">Submit</button>
            </div>
            
            <div id="step2" style="display: none;">
                <div style="background: #f0fdf4; padding: 15px; border-radius: 10px; margin-bottom: 15px;">
                    <p id="summaryText" style="margin: 0; font-size: 0.9rem; color: #166534;"></p>
                </div>
                <div class="input-group">
                    <label>Namba ya Mpokeaji</label>
                    <input type="text" id="receiverNumber" value="+255784766591" readonly style="background: #f1f5f9;">
                </div>
                <button class="submit-btn" onclick="finalSubmit()" style="background: var(--primary-color);">Kamilisha Sasa</button>
                <button onclick="location.reload()" style="background:none; color: gray; width:100%; font-size: 0.8rem;">Anza upya</button>
            </div>
        </div>
    </div>

    <footer>
        &copy; 2026 LUTEMA Jr - Haki zote zimehifadhiwa.
    </footer>

    <script>
        // Onyesha URL ya sasa
        document.getElementById('siteUrl').innerText = "🌐 URL: " + window.location.href;

        // --- CALCULATOR LOGIC ---
        const display = document.getElementById('display');

        function appendToDisplay(input) {
            display.value += input;
        }

        function clearDisplay() {
            display.value = "";
        }

        function deleteLast() {
            display.value = display.value.slice(0, -1);
        }

        function calculate() {
            try {
                // Tunatumia Function constructor badala ya eval kwa usalama kidogo zaidi
                display.value = new Function('return ' + display.value)();
            } catch (error) {
                display.value = "Error";
                setTimeout(clearDisplay, 1500);
            }
        }

        // --- TRANSFER LOGIC ---
        function nextStep() {
            const country = document.getElementById('countryCode').value;
            const amount = document.getElementById('amount').value;

            if (!country || !amount) {
                alert("Tafadhali jaza namba ya nchi na kiasi!");
                return;
            }

            document.getElementById('step1').style.display = 'none';
            document.getElementById('step2').style.display = 'block';
            document.getElementById('summaryText').innerHTML = `<b>Maelezo:</b> Unatuma kutoka <b>${country}</b> kiasi cha <b>${amount}</b>.`;
        }

        function finalSubmit() {
            alert("Muamala unafanyiwa kazi kwenda +255784766591. Asante kwa kutumia LUTEMA Jr!");
            location.reload();
        }
    </script>
</body>
</html>
