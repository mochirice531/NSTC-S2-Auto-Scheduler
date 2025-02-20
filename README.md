NSTC-S2 Auto Scheduler
======

![license MIT](https://img.shields.io/badge/license-MIT-blue)
![python 3.10.6](https://img.shields.io/badge/python-3.10.6-blue)

> 2023 &copy; alanwu-9852

專案簡介
---
這個專案可以協助[南山高中交通服務隊](https://www.instagram.com/nstc_16th/?utm_source=ig_web_button_share_sheet&igshid=ZDNlZDc0MzIxNw==)中**偉大的總指揮勤務長大人**排班表。大幅縮減每個月排班表所花的時間

使用說明
---

開始使用:

* 匯入符合格式的名單與班表模板
* 設定最大值勤次數，與最大早班次數
* 開始排班
* 匯出班表
* 完成!!


使用範例:

1. 啟動程式。
2. 點擊匯入名單匯入[符合格式的名單](data/members.json)
3. 點擊匯入班表模版匯入:[高一](data/S1_schedule.json)、[高二](data/schedule.json)
4. 設定最大值勤次數，與最大早班次數
5. 點擊 "開始排班" 按鈕，程式將自動完成排班。
6. 匯出班表可以將班表以 csv 格式匯出，可以用 Excel 開啟


功能介紹:

1. 可設定無法值勤的時間~~還有不想值勤的工作~~


其他說明:

1. 目前僅支援特定格式的班表編寫方式
2. 只能高二隊員的班表
3. 無法根據總指揮的設定調整總指揮值勤時間

版本更新
---
* v1.14.514 (2023/10/16): 初版 


待做功能
---
以下是一些待做的功能：

- [ ] 加入編排高一班表的功能
- [ ] 強化防呆功能，~~預防鴨鴨~~
- [ ] 檢查班表功能
- [ ] 最佳化班表功能

如果你有任何建議或問題，請隨時聯繫作者
