# SafeSwitch-Releases

嘻安官（SafeSwitch）的官方 APK 發佈倉庫。此倉庫**只保存公開 APK、SHA-256 校驗與版本資訊**；Android 原始碼、S24 金鑰交換檔、簽署金鑰與 KeePass 資料庫皆不放在這裡。

- 目前版本：**v0.1.12**（Build 13，Android 套件 `com.enter501.cng`）
- 下載：見 [Releases](https://github.com/retne501/SafeSwitch-Releases/releases)
- 更新資訊：[`update.json`](./update.json)
- 更新方式：透過 S24 直接覆蓋安裝相同簽章 APK，**勿先移除舊 App**，避免遺失既有權限／資料。
- 第 5 鍵採 Samsung 原生設定 Key `toggle_adb_wireless` 定位「無線偵錯」，S24 已驗證成功；無障礙慢速半頁滑動為備援。
- APK 上傳與簽署流程由 Windows／MacBook 開發工作站控制，S24 作為加密金鑰交換站。**此檔案只提供下載資訊，不表示 App 已具備自動更新功能**。
