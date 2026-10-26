---
title: ParseExact()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的日期時間值之字串表示轉換為等效的 DateTime 物件，使用指定的格式與特定文化的格式資訊。字串表示的格式必須完全符合指定的格式。若轉換失敗，會拋出例外。
type: docs
weight: 872
url: /zh-hant/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 方法

將指定的日期時間值之字串表示轉換為等效的 [DateTime](../) 物件，使用指定的格式和特定文化的格式資訊。字串表示的格式必須完全符合指定的格式。若轉換失敗，會拋出例外。

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的日期時間值之字串表示。 |
| format | const [String](../../string/)\& | 字串格式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式資訊的 [IFormatProvider](../../iformatprovider/) 物件。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 列舉值的逐位組合，提供有關 **s**、可能存在於 **s** 中的樣式元素，或 **s** 轉換為 [DateTime](../) 物件的其他資訊。 |

### 返回值

新的 [DateTime](../) 類別實例，代表與指定字串所表示的日期時間值等效的值。

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 方法

將指定的日期時間值之字串表示轉換為等效的 [DateTime](../) 物件，使用指定的格式、特定文化的格式資訊與樣式。字串表示的格式必須完全符合一個或多個指定的格式。若轉換失敗，會拋出例外。

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的日期時間值之字串表示。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 字串格式的陣列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式資訊的 [IFormatProvider](../../iformatprovider/) 物件。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 列舉值的逐位組合，提供有關 **s**、可能存在於 **s** 中的樣式元素，或 **s** 轉換為 [DateTime](../) 物件的其他資訊。 |

### 返回值

新的 [DateTime](../) 類別實例，代表與指定字串所表示的日期時間值等效的值。

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## 另見

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)