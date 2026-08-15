---
title: ParseExact()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的字串依照指定的格式、格式提供者與格式樣式轉換為 DateTimeOffset 物件。
type: docs
weight: 716
url: /zh-hant/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String&, const String&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles) method

將指定的字串依照指定的格式、格式提供者與格式樣式轉換為 [DateTimeOffset](../) 物件。

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)& | [String](../../string/) 以供轉換。 |
| format | const [String](../../string/)& | 格式字串。 |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | 格式提供者。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期與時間的格式樣式。 |

### 返回值

[DateTimeOffset](../) 等同於 **input** 的結果。

## DateTimeOffset::ParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles) method

將指定的字串依照指定的格式集合、格式提供者與格式樣式轉換為 [DateTimeOffset](../) 物件。

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)& | [String](../../string/) 以供轉換。 |
| formats | const [ArrayPtr](../../arrayptr/)<[String](../../string/)>& | [Array](../../array/) 格式字串。 |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | 格式提供者。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期與時間的格式樣式。 |

### 返回值

[DateTimeOffset](../) 等同於 **input** 的結果。

## 參見

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)