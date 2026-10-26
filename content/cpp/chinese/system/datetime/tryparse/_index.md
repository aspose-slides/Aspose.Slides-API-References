---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的日期和时间值的字符串表示形式转换为等效的 DateTime 对象。
type: docs
weight: 885
url: /zh/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) 方法

转换指定的日期和时间值的字符串表示形式为等效的 [DateTime](../) 对象。

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的日期和时间值的字符串表示形式。 |
| result | [DateTime](../)\& | 如果转换成功，输出参数，其中包含转换结果。 |

### 返回值

如果转换成功，则返回 true；否则返回 false。

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

使用指定的特定文化格式信息和样式，将指定的日期和时间值的字符串表示形式转换为等效的 [DateTime](../) 对象。

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的日期和时间值的字符串表示形式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) 对象，提供特定文化的格式信息。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 一个按位组合的枚举值，提供关于 **s** 的附加信息、关于 **s** 中可能存在的样式元素的附加信息，或关于从 **s** 到 [DateTime](../) 对象的转换的附加信息。 |
| result | [DateTime](../)\& | 如果转换成功，输出参数，其中包含转换结果。 |

### 返回值

如果转换成功，则返回 true；否则返回 false。

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) 方法

```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## 参见

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)