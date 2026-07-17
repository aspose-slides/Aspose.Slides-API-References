---
title: TryParseExact()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的格式和格式提供程序将字符串转换为等效的 TimeSpan 对象，并返回转换结果。
type: docs
weight: 573
url: /zh/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) 方法

使用指定的格式和格式提供程序将字符串转换为等效的 [TimeSpan](../) 对象，并返回转换结果。

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 输入字符串。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) 格式字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式信息的格式提供程序。 |
| result | [TimeSpan](../)\& | 与字符串对应的时间间隔。 |

### 返回值

如果字符串成功转换则返回 true；否则返回 false。

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) 方法

使用指定的格式、格式提供程序和样式将字符串转换为等效的 [TimeSpan](../) 对象，并返回转换结果。

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 输入字符串。 |
| format | const [String](../../string/)\& | 标准或自定义格式字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式信息的格式提供程序。 |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | 定义可能出现在输入字符串中的元素。 |
| result | [TimeSpan](../)\& | 与字符串对应的时间间隔。 |

### 返回值

如果字符串成功转换则返回 true；否则返回 false。

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) 方法

使用指定的格式、格式提供程序和样式将字符串转换为等效的 [TimeSpan](../) 对象，并返回转换结果。

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 输入字符串。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) 格式字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式信息的格式提供程序。 |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | 定义可能出现在输入字符串中的元素。 |
| result | [TimeSpan](../)\& | 与字符串对应的时间间隔。 |

### 返回值

如果字符串成功转换则返回 true；否则返回 false。

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) 方法

使用指定的格式和格式提供程序将字符串转换为等效的 [TimeSpan](../) 对象，并返回转换结果。

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 输入字符串。 |
| format | const [String](../../string/)\& | 标准或自定义格式字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式信息的格式提供程序。 |
| result | [TimeSpan](../)\& | 与字符串对应的时间间隔。 |

### 返回值

如果字符串成功转换则返回 true；否则返回 false。

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## 参见

* 枚举 [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [TimeSpan](../)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)