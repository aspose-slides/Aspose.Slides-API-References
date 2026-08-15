---
title: GetFormat()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得特定類型的格式化器。
type: docs
weight: 14
url: /zh-hant/system.globalization/datetimeformatinfo/getformat/
---
## DateTimeFormatInfo::GetFormat(const TypeInfo\&) 方法

取得特定類型的格式化器。

```cpp
SharedPtr<Object> System::Globalization::DateTimeFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | 要取得的格式化器類型；僅支援 [DateTimeFormatInfo](../) 類型。 |

### 傳回值

格式化器，若不可用則為 null。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [DateTimeFormatInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)