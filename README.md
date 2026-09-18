<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>微信支付</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; }
        body { background-color: #f2f2f2; display: flex; justify-content: center; align-items: center; min-height: 100vh; }
        .payment-box { background: #fff; width: 90%; max-width: 400px; border-radius: 16px; padding: 40px 25px; text-align: center; box-shadow: 0 4px 12px rgba(0,0,0,0.05); }
        .logo { font-size: 22px; font-weight: bold; color: #07C160; margin-bottom: 30px; display: flex; align-items: center; justify-content: center; }
        .logo-icon { width: 28px; height: 28px; background: #07C160; border-radius: 6px; display: inline-block; margin-right: 10px; position: relative; }
        .logo-icon::after { content: "微"; color: #fff; font-size: 16px; position: absolute; left: 50%; top: 50%; transform: translate(-50%, -50%); }
        .amount { font-size: 48px; font-weight: bold; color: #333; margin-bottom: 15px; letter-spacing: 1px; }
        .desc { color: #999; font-size: 15px; margin-bottom: 40px; }
        .pay-btn { background: #07C160; color: #fff; border: none; width: 100%; padding: 16px; border-radius: 8px; font-size: 18px; font-weight: bold; cursor: pointer; transition: background 0.2s; }
        .pay-btn:active { background: #06AD56; }
        .note { font-size: 12px; color: #ccc; margin-top: 25px; }
    </style>
</head>
<body>
    <div class="payment-box">
        <div class="logo">
            <span class="logo-icon"></span>
            微信支付
        </div>
        <div class="amount">¥ 999,999.00</div>
        <div class="desc">收款方你爸爸</div>
        <button class="pay-btn" onclick="alert('余额不足！请先充值智商。')">立即支付</button>
        <div class="note">注：本页面仅供娱乐，请勿当真</div>
    </div>
</body>
</html>
