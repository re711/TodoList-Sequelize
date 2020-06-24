# Todo-List-Sequelize
使用 Node.js + Express + MySQL 打造的 TodoList 練習作品，。

# 安裝流程
 1. 終端機輸入
 ``` 
  $ git clone https://github.com/re711/TodoList-Sequelize.git
 ```
 2. 安裝套件
 ``` 
  $ npm install
 ```
 3. 設定 .env 檔案 
 ```
  $ touch .env
 ```
 4. 將 API Key 儲存在 .env 檔案中並保存
 ```
  FACEBOOK_ID=你的應用程式編號
  FACEBOOK_SECRET=你的應用程式密鑰
  FACEBOOK_CALLBACK=http://localhost:3000/auth/facebook/callback
  SESSION_SECRET=ThisIsMySecret
  PORT=3000
 ```
 5. 執行
 ``` 
  $ npm run dev
 ```

# 功能
1. 使用Email或Facebook註冊帳號、登入驗證功能
2. Todo CRUD 功能

# 工具
* Node.js
* Express
* Express-handlebars
* Bootstrap
* MySQL
* express-session
* passport