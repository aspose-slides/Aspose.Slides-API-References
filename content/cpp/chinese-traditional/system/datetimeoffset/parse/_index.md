---
title: Parse()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的字串轉換為 DateTimeOffset 等效值。
type: docs
weight: 703
url: /zh-hant/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) 方法

將指定的字串轉換為 [DateTimeOffset](../) 等效值。

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 要轉換的 [String](../../string/)。 |

### 返回值

[DateTimeOffset](../)，其等效於 **input**。

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 方法

使用指定的格式提供程式與格式樣式，將指定的字串轉換為 [DateTimeOffset](../) 物件。

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 要轉換的 [String](../../string/)。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程式。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和時間的格式樣式。 |

### 返回值

[DateTimeOffset](../)，其等效於 **input**。

## 相關參考

* 列舉 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [DateTimeOffset](../)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)