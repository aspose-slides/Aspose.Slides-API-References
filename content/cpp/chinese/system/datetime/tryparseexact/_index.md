---
title: TryParseExact()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的格式、特定文化的格式信息和样式，将指定的日期时间值的字符串表示转换为等效的 DateTime 对象。字符串表示的格式必须完全匹配指定的格式。
type: docs
weight: 898
url: /zh/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

使用指定的格式、特定文化的格式信息和样式，将指定的日期时间值的字符串表示转换为等效的 [DateTime](../) 对象。字符串表示的格式必须完全匹配指定的格式。

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的日期时间值的字符串表示。 |
| format | const [String](../../string/)\& | 字符串格式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式信息的 [IFormatProvider](../../iformatprovider/) 对象。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 按位组合的枚举值，为 **s**、可能出现在 **s** 中的样式元素或从 **s** 转换为 [DateTime](../) 对象提供额外信息。 |
| result | [DateTime](../)\& | 输出参数，如果转换成功，则包含转换结果。 |

### 返回值

如果转换成功则返回 true，否则返回 false。

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

使用指定的格式集合、特定文化的格式信息和样式，将指定的日期时间值的字符串表示转换为等效的 [DateTime](../) 对象。字符串表示的格式必须完全匹配一个或多个指定的格式。

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的日期时间值的字符串表示。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 字符串格式数组。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式信息的 [IFormatProvider](../../iformatprovider/) 对象。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 按位组合的枚举值，为 **s**、可能出现在 **s** 中的样式元素或从 **s** 转换为 [DateTime](../) 对象提供额外信息。 |
| result | [DateTime](../)\& | 输出参数，如果转换成功，则包含转换结果。 |

### 返回值

如果转换成功则返回 true，否则返回 false。

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## 另请参见

* 枚举 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [DateTime](../)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)