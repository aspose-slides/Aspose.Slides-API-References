---
title: GetInstance()
second_title: Aspose.Slides for C++ API 參考
description: 取得與格式提供程序關聯的格式化程序。
type: docs
weight: 846
url: /zh-hant/system.globalization/datetimeformatinfo/getinstance/
---
## DateTimeFormatInfo::GetInstance(const IFormatProviderPtr\&) 方法

取得與格式提供程序關聯的格式化程序。

```cpp
static DateTimeFormatInfoPtr System::Globalization::DateTimeFormatInfo::GetInstance(const IFormatProviderPtr &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| provider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 要取得格式的提供程序。 |

### 傳回值

Formatter 與格式提供程序關聯；如果無法取得，則使用目前執行緒的格式。

## 相關參考

* 型別別名 [DateTimeFormatInfoPtr](../../datetimeformatinfoptr/)
* 型別別名 [IFormatProviderPtr](../../../system/iformatproviderptr/)
* 類別 [DateTimeFormatInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)