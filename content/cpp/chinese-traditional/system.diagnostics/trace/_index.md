---
title: Trace
second_title: Aspose.Slides for C++ API 參考文件
description: 提供介面以存取除錯追蹤（若有）。僅在 Debug 模式下工作。這是一個靜態類型，沒有實例服務。無論如何都不應該建立其實例。
type: docs
weight: 131
url: /zh-hant/system.diagnostics/trace/
---
## Trace 結構


提供介面以存取除錯追蹤（若有）。僅在 [Debug](../debug/) 模式下工作。這是一個靜態類型，沒有實例服務。無論如何都不應該建立其實例。

```cpp
class Trace
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static void [Flush](./flush/)() | 刷新輸出緩衝區，並導致緩衝資料寫入監聽程式。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 將行寫入除錯追蹤。 |
## 另請參閱

* 命名空間 [System::Diagnostics](../)
* 函式庫 [Aspose.Slides](../../)