# 📈 Wheel Strategy Calculator (期權輪動策略計算器)

A professional, single-page web application designed for options traders to calculate, track, and analyze the performance of **The Wheel Strategy**.
🔗 **Demo：** https://pony0278.github.io/StockOptions-Wheel-Strategy-Calculate/

這是一個專為期權交易者設計的單頁式 Web 應用程式，用於計算、追蹤並分析 **Wheel Strategy (輪動策略)** 的績效與損益。

## ✨ Features (功能特色)

* **🌓 Dark/Light Mode**: Automatically fits your trading environment.
    * 支援深色/淺色模式切換，符合看盤習慣。
* **🌐 Bilingual Support**: Instant switch between English and Traditional Chinese.
    * 支援繁體中文與英文介面即時切換。
* **💾 Auto-Save**: Your inputs are saved locally in the browser, so you never lose data on refresh.
    * **自動記憶功能**：利用 LocalStorage 自動保存輸入數據，重新整理頁面也不會遺失。
* **📊 Advanced Metrics**:
    * **Breakeven Price & Safety Margin**: Visualize your downside protection.
    * **Annualized Return (APY)**: Calculates efficiency based on days held.
    * **損益平衡點與安全邊際**：計算股價跌幅緩衝保護。
    * **年化報酬率**：根據持有天數精準計算資金效率。
* **⚖️ Benchmark Analysis**: Compares your Wheel performance against a standard **Buy & Hold** strategy.
    * **績效對比分析**：自動計算並比較「輪動策略」與「直接買入持有」的優劣。

## 🚀 Usage (如何使用)

You don't need to install anything. This is a client-side application.

本專案無需安裝，純前端運行。

### Method : 
1. Download the `index.html` file.
2. Open it in any modern browser (Chrome, Edge, Safari).

## 🧠 The Logic (計算邏輯)

This tool calculates the Profit & Loss (PnL) based on the classic Wheel Strategy cycle:
本工具基於經典的 Wheel 策略循環計算損益：

1.  **Sell Cash-Secured Put**: Collect premium.
2.  **Assignment (Optional)**: If assigned, cost basis is calculated.
3.  **Sell Covered Call**: Collect additional premium + potential capital gains from stock.
4.  **Dividends**: Adds any dividends collected during the holding period.

It also calculates the **Opportunity Cost** by comparing the final result with a hypothetical scenario where you bought the stock immediately at the beginning.

同時，它會計算**機會成本**，將您的最終結果與「一開始就直接買入股票」的情境進行對比。

## 🛠 Technologies (使用技術)

* **HTML5**
* **CSS3** (CSS Variables for theming, Flexbox/Grid for layout)
* **JavaScript (Vanilla)** (No frameworks required)

## 🤝 Contributing (貢獻)

Feel free to fork this repository and submit pull requests to improve the calculator!
歡迎 Fork 本專案並提交 Pull Requests 來改進功能！

## 📄 License

This project is licensed under the MIT License.
