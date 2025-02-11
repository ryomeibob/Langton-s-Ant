<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ラングトンのアリ</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; margin: 0; padding: 0; }
        h1 { margin-top: 20px; }
        canvas { border: 1px solid black; margin-top: 20px; }
        .controls {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 15px;
            margin-top: 10px;
        }
        button { padding: 5px 15px; font-size: 16px; cursor: pointer; }
        #turnCounter {
            font-size: 18px;
            font-weight: bold;
            background: rgba(0, 0, 0, 0.1);
            padding: 5px 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>ラングトンのアリ</h1>
    <div class="controls">
        <button id="startBtn">開始</button>
        <button id="resetBtn">リセット</button>
        <span id="turnCounter">ターン数: 0</span>
    </div>
    <canvas id="canvas"></canvas>

    <script src="script.js"></script>
</body>
</html>
