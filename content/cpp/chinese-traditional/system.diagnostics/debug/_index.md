---
title: Debug
second_title: Aspose.Slides for C++ API 參考文件
description: 收集用於將偵錯資訊傳送給已註冊監聽器的偵錯方法。所有輸出函式僅在 Debug 中運作。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。
type: docs
weight: 105
url: /zh-hant/system.diagnostics/debug/
---
## Debug 結構


收集用於將偵錯資訊傳送給已註冊監聽器的偵錯方法。所有輸出函式僅在 [Debug](./) 中工作。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。

```cpp
class Debug
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | 斷言條件並在失敗時傳送資訊。 |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | 斷言條件並在失敗時傳送資訊。 |
| static void [Assert](./assert/)(**bool**, const char *) | 斷言條件並在失敗時傳送資訊。 |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 斷言條件並在失敗時傳送資訊。 |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | 傳送失敗訊息。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | 存取監聽器的靜態清單。 |
| static void [Print](./print/)(const [String](../../system/string/)\&) | 將訊息列印到偵錯介面。 |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | 將訊息列印到偵錯介面。 |
| static void [Write](./write/)(const [String](../../system/string/)\&) | 將字串寫入偵錯介面。 |
| static void [Write](./write/)(const char_t *) | 將字串寫入偵錯介面。 |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | 若條件為真，將字串寫入偵錯介面。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 將行寫入偵錯介面。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 將行寫入偵錯介面。 |
| static void [WriteLine](./writeline/)(const char_t *) | 將行寫入偵錯介面。 |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 將行寫入偵錯介面。 |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | 若條件為真，將行寫入偵錯介面。 |
## 另見

* 命名空間 [System::Diagnostics](../)
* 程式庫 [Aspose.Slides](../../)