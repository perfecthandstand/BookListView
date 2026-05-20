# 圖書管理系統 (Book Library Manager)

## 專案簡介
本專案為一個基於 C# Windows Forms 應用程式開發的圖書管理介面。使用者可以透過直覺的視覺化介面瀏覽書籍，切換不同的檢視模式，並進行模擬的借閱操作。主要應用了 `ListView` 控制項的進階功能與多媒體呈現。

## 功能特色
* **多樣化檢視模式**：支援切換「大圖示」、「小圖示」、「清單」、「詳細資料」與「大圖示加詳細資料(Tile)」五種 ListView 檢視樣式。
* **圖文並茂清單**：使用 `ImageList` 綁定書籍圖片，並在詳細資料模式下顯示書名、作者與分類。
* **雙擊借閱功能**：透過 `ItemActivate` 事件捕捉使用者的雙擊動作，防呆確認後自動將書籍加入至右側的借書清單 (ListBox) 中，並會檢查是否重複借閱。

## 執行說明
1. 確認電腦已安裝 Visual Studio (支援 .NET Framework 4.7.2 或以上)。
2. Clone 此專案至本地端：
   ```bash
   git clone [https://github.com/你的帳號/你的專案名稱.git](https://github.com/你的帳號/你的專案名稱.git)
<img width="679" height="451" alt="image" src="https://github.com/user-attachments/assets/88e13c01-c267-4544-9058-1321da38ca92" />
