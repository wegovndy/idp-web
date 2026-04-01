<!DOCTYPE html>
<html lang="zh-HK">
<head>
  <meta charset="UTF-8">
  <title>網上申請國際駕駛許可證（IDP）</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #222;
      line-height: 1.6;
    }
    header {
      background: #004b8d;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.6rem;
    }
    main {
      max-width: 900px;
      margin: 20px auto 40px;
      background: #fff;
      padding: 20px 24px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.06);
      border-radius: 8px;
    }
    h2 {
      margin-top: 24px;
      font-size: 1.3rem;
      border-left: 4px solid #004b8d;
      padding-left: 8px;
    }
    p {
      margin: 8px 0;
    }
    ul {
      padding-left: 20px;
      margin: 8px 0 4px;
    }
    li {
      margin: 4px 0;
    }
    .highlight {
      background: #fff7e0;
      border-left: 4px solid #f0a500;
      padding: 10px 12px;
      margin: 12px 0;
      border-radius: 4px;
    }
    .fee {
      font-size: 1.1rem;
      font-weight: 600;
      color: #b00020;
    }
    .button-area {
      margin: 20px 0;
      text-align: center;
    }
    .btn {
      display: inline-block;
      background: #004b8d;
      color: #fff;
      padding: 12px 20px;
      border-radius: 6px;
      text-decoration: none;
      font-size: 1rem;
      transition: 0.2s;
    }
    .btn:hover {
      background: #003766;
    }
    .form-section {
      margin-top: 30px;
      padding: 20px;
      background: #eef5ff;
      border-radius: 8px;
    }
    label {
      display: block;
      margin-top: 12px;
      font-weight: 600;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 6px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }
    .submit-btn {
      margin-top: 20px;
      width: 100%;
      background: #0072ce;
      color: #fff;
      padding: 12px;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
      cursor: pointer;
    }
    .submit-btn:hover {
      background: #005fa3;
    }
    footer {
      text-align: center;
      font-size: 0.85rem;
      color: #777;
      padding: 16px 0 24px;
    }
  </style>
</head>
<body>
  <header>
    <h1>網上申請國際駕駛許可證（IDP）</h1>
    <p>透過此網上服務，你可申請及查詢國際駕駛許可證</p>
  </header>

  <main>
    <!-- 功能介紹 -->
    <section>
      <h2>可辦理的服務</h2>
      <ul>
        <li>申請國際駕駛許可證（IDP）</li>
        <li>查詢申請狀態</li>
        <li>重新提交補充文件</li>
      </ul>
    </section>

    <!-- 費用 -->
    <section>
      <h2>申請費用</h2>
      <div class="highlight">
        <p class="fee">HK$10,000（由 2026 年 4 月 1 日起生效）</p>
        <p>因應防偽技術升級及跨境資料核實成本增加，費用已作出調整。</p>
      </div>
    </section>

    <!-- 按鈕 -->
    <div class="button-area">
      <a href="#applyForm" class="btn">立即申請</a>
    </div>

    <!-- 申請資格 -->
    <section>
      <h2>誰可申請？</h2>
      <ul>
        <li>持有有效香港身份證</li>
        <li>持有有效或過期不超過 3 年的香港正式駕駛執照</li>
        <li>能提供最近 3 個月內的住址證明</li>
      </ul>
    </section>

    <!-- 所需文件 -->
    <section>
      <h2>申請所需文件</h2>
      <ul>
        <li>已啟用「智方便+」帳戶</li>
        <li>近照 JPG（不超過 5MB）</li>
        <li>住址證明</li>
        <li>信用卡（Visa / Master / JCB）或轉數快</li>
      </ul>
    </section>

    <!-- 表單 -->
    <section id="applyForm" class="form-section">
      <h2>申請表格（示範）</h2>

      <label>中文姓名</label>
      <input type="text" placeholder="請輸入你的中文姓名">

      <label>英文姓名（與身份證相同）</label>
      <input type="text" placeholder="請輸入英文姓名">

      <label>香港身份證號碼</label>
      <input type="text" placeholder="例如：A123456(7)">

      <label>駕駛執照號碼</label>
      <input type="text" placeholder="請輸入駕駛執照號碼">

      <label>上載近照（JPG，不超過 5MB）</label>
      <input type="file" accept="image/jpeg">

      <label>上載住址證明</label>
      <input type="file">

      <label>付款方式</label>
      <select>
        <option>信用卡（Visa / Master / JCB）</option>
        <option>轉數快 FPS</option>
      </select>

      <button class="submit-btn">提交申請</button>
    </section>

    <!-- 查詢 -->
    <section>
      <h2>查詢</h2>
      <p>如 6 星期後仍未收到許可證，可致電 <strong>2804 2600</strong> 查詢。</p>
    </section>
  </main>

  <footer>
    <p>本頁面內容僅供示範用途。</p>
  </footer>
</body>
</html>
