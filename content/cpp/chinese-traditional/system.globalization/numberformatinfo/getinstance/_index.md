---
title: GetInstance()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得與格式提供者關聯的格式化器。
type: docs
weight: 794
url: /zh-hant/system.globalization/numberformatinfo/getinstance/
---
## NumberFormatInfo::GetInstance(const IFormatProviderPtr\&) 方法

取得與格式提供者關聯的格式化器。

```cpp
static NumberFormatInfoPtr System::Globalization::NumberFormatInfo::GetInstance(const IFormatProviderPtr &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| provider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 用於取得格式的提供者。 |

### 返回值

與格式提供者關聯的格式化器，若不可用則為當前執行緒的格式。

## 另請參閱

* 型別別名 [NumberFormatInfoPtr](../../numberformatinfoptr/)
* 型別別名 [IFormatProviderPtr](../../../system/iformatproviderptr/)
* 類別 [NumberFormatInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)