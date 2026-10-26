---
title: ParseExact()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的日期和时间值的字符串表示转换为等效的 DateTime 对象，使用指定的格式和特定于文化的格式信息。字符串表示的格式必须与指定的格式完全匹配。如果转换失败，将抛出异常。
type: docs
weight: 872
url: /zh/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method

将指定的日期和时间值的字符串表示转换为等效的[DateTime](../)对象，使用指定的格式和特定于文化的格式信息。字符串表示的格式必须与指定的格式完全匹配。如果转换失败，将抛出异常。

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的日期和时间值的字符串表示。 |
| format | const [String](../../string/)\& | 字符串格式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定于文化的格式信息的[IFormatProvider](../../iformatprovider/)对象。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 枚举值的按位组合，提供有关 **s** 的附加信息，关于 **s** 中可能出现的样式元素，或关于从 **s** 到 [DateTime](../) 对象的转换。 |

### 返回值

表示由指定字符串表示的日期和时间值等效的[DateTime](../)类的新实例。

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) method

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method

将指定的日期和时间值的字符串表示转换为等效的[DateTime](../)对象，使用指定的格式、特定于文化的格式信息和样式。字符串表示的格式必须完全匹配一个或多个指定的格式。如果转换失败，将抛出异常。

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的日期和时间值的字符串表示。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 字符串格式的数组。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定于文化的格式信息的[IFormatProvider](../../iformatprovider/)对象。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 枚举值的按位组合，提供有关 **s** 的附加信息，关于 **s** 中可能出现的样式元素，或关于从 **s** 到 [DateTime](../) 对象的转换。 |

### 返回值

表示由指定字符串表示的日期和时间值等效的[DateTime](../)类的新实例。

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) method

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## 另请参见

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