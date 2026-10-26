---
title: TryParseExact()
second_title: Aspose.Slides C++ API 參考
description: 嘗試使用指定的格式、格式提供者與格式樣式，將指定的字串轉換為 DateTimeOffset 物件。
type: docs
weight: 742
url: /zh-hant/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) 方法

嘗試使用指定的格式、格式提供者和格式樣式，將指定的字串轉換為 [DateTimeOffset](../) 物件。

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 要轉換的[String](../../string/)。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 格式字串的陣列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供者。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和時間的格式樣式。 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../)，其等同於 **input**。 |

### Return Value

true if the **input** converted successfully, otherwise - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) 方法

嘗試使用指定的格式、格式提供者和格式樣式，將指定的字串轉換為 [DateTimeOffset](../) 物件。

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 要轉換的[String](../../string/)。 |
| format | const [String](../../string/)\& | 格式字串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供者。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和時間的格式樣式。 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../)，其等同於 **input**。 |

### Return Value

true if the **input** converted successfully, otherwise - false.

## 另請參閱

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)