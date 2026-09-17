# 0919 招待須知網頁

給婚禮當天 6 位招待看的簡易網頁,只有一個檔案 `index.html`,不需要安裝、不需要加入主畫面,用手機瀏覽器打開連結就能看。

內容:
- 招待注意事項(集合時間、流程、職責、找人窗口)
- 可搜尋的桌次總表(輸入賓客姓名查詢在哪一桌)

## 上傳到 GitHub(網頁操作,不需要用電腦/指令)

1. 到 GitHub 建一個新的 repo(跟總召時間軸那個分開,例如叫 `wedding-0919-usher`),設為 Public
2. 進到這個新 repo 的頁面,點畫面上的 **Add file** → **Upload files**
   - 在 iPad/手機 Safari 上,是點檔案清單上方、「Go to file」搜尋框旁邊那個小小的 **+** 圖示,選單裡有「Upload files」
3. 點「choose your files」,選擇 `index.html` 這一個檔案上傳
4. 上傳完成後,最下面點綠色的 **Commit changes**
5. 到 repo 的 **Settings → Pages**,Source 選 `main` branch、`/ (root)`,存檔
6. 幾分鐘後網址會是:`https://<你的帳號>.github.io/wedding-0919-usher/`
7. 把這個網址傳給 6 位招待(LINE 傳連結即可,不需要加入主畫面,打開直接看)

## 之後要修改內容怎麼辦?

因為只有一個檔案,之後如果招待名單或桌次有變動,把新的 `index.html` 直接重新上傳蓋掉舊的就可以了(GitHub 網頁上傳同名檔案會自動詢問是否取代,選是即可)。
