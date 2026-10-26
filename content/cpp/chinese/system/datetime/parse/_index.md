---
title: Parse()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的日期和时间值的字符串表示转换为等效的 DateTime 对象。
type: docs
weight: 859
url: /zh/system/datetime/parse/
---
## DateTime::Parse(const String\&) 方法

将指定的日期和时间值的字符串表示转换为等效的 [DateTime](../) 对象。

```cpp
static DateTime System::DateTime::Parse(const String &s)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的日期和时间值的字符串表示。 |

### 返回值

一个新的 [DateTime](../) 类实例，表示与指定字符串等效的日期和时间值。

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 方法

使用特定文化的格式信息，将指定的日期和时间值的字符串表示转换为等效的 [DateTime](../) 对象。

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的日期和时间值的字符串表示。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式信息的 [IFormatProvider](../../iformatprovider/) 对象。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 提供有关 **s**、可能存在于 **s** 中的样式元素或从 **s** 转换为 [DateTime](../) 对象的附加信息的枚举值的位组合。 |

### 返回值

一个新的 [DateTime](../) 类实例，表示与指定字符串等效的日期和时间值。

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) 方法

```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## 参见

* 枚举 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [DateTime](../)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)