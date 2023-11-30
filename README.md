# Example-Solution
110 教育部師培計畫 沉浸式新興科技體驗設計 練習範例與解答  
範例、解答頁數對照至 WebVR.pptx 投影片頁碼  
可參見以下啟動方法  
## 方法一
須關閉瀏覽器安全性設定，如：  
`cd C:\Program Files (x86)\Google\Chrome\Application`  
`chrome.exe --user-data-dir="C:/Chrome dev session" --disable-web-security`
若為 Edge 瀏覽器同理：
`msedge.exe --user-data-dir="C:/Chrome dev session" --disable-web-security`
再以此模式下的 chrome/Edge 啟動
(註：指令中的 C:/Chrome dev session 可替換為任意資料夾，只要有此資料夾即可在對應資料夾內生成必須檔案)
## 方法二
使用網頁伺服器，如：  
`cd C:\myProject`  
`python3 -m http.server`  
再至相對應的 port 中存取
