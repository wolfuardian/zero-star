⚠ 注意：專案為早期開發版本。

# zero-star


# Coding Guideline

主要是對於git指令與程式碼管理的基本常識與規範，非強制性，可遵守也可不遵守。

## Commit Message

類別以最粗淺的方式描述了本次更新所做的事情，您僅應當使用如下關鍵字作為 Commit 標題的類別：

* **功能（feat）：** 實現了一個新功能，但不包含構建腳本和自動化測試；
* **修復（fix）：**修復了一處功能異常，但不包含構建腳本和自動化測試；
* **文檔（docs）：**任何文檔的新增、刪除與修改；
* **風格（style）：**不對程式碼實際內容產生影響的程式碼風格調整工作，如刪除或補全分號、縮進調整；
* **重構（refactor）：**對已有的程式碼進行重構。包含對變數的重新命名；
* **測試（test）：**增加新的測試，修改已有測試，重構測試，不涉及業務邏輯程式碼變化；
* **雜物（chore）：**依賴升級等不適用上述關鍵字的內容，且不涉及主要程式碼變動；
* **內容（pub）：**適用於靜態倉庫以及內容程式碼混在一起的孽障倉庫，增加或修改了內容都應當使用此關鍵字。
