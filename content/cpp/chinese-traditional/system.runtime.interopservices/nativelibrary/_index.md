---
title: NativeLibrary
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 40
url: /zh-hant/system.runtime.interopservices/nativelibrary/
---
## NativeLibrary 類別




```cpp
class NativeLibrary
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static void [Free](./free/)(IntPtr) | 卸載動態函式庫。 |
| static IntPtr [GetExport](./getexport/)(IntPtr, const [String](../../system/string/)\&) | 取得給定函式庫項目的位址。 |
| static IntPtr [Load](./load/)(const [String](../../system/string/)\&) | 載入原生動態函式庫。發生錯誤時拋出例外。 |
| static **bool** [TryLoad](./tryload/)(const [String](../../system/string/)\&, IntPtr\&) | 載入原生動態函式庫。 |

## 另請參閱

* 命名空間 [System::Runtime::InteropServices](../)
* 函式庫 [Aspose.Slides](../../)