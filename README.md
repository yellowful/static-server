# 靜態伺服器

1. 一個單純的靜態伺服器，可以用來伺服靜態檔案，例如 HTML、CSS、JavaScript、圖片等等。
2. 用來做實驗、放檔案、或放SPA專案。
3. git clone下來後，先在專案內建立`static`資料夾
4. `docker-compose up --build -d` 啟動伺服器，預設會監聽 8080 port。
5. 把要靜態伺服的檔案放到 `./static` 資料夾。
