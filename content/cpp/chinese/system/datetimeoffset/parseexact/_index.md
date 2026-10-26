---
title: ParseExact()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的格式、格式提供程序和格式化样式，将指定的字符串转换为 DateTimeOffset 对象。
type: docs
weight: 716
url: /zh/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 方法

使用指定的格式、格式提供程序和格式化样式，将指定的字符串转换为 [DateTimeOffset](../) 对象。

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 用于转换。 |
| format | const [String](../../string/)\& | 格式字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和时间格式化样式。 |

### 返回值

[DateTimeOffset](../) 等价于 **input**。

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 方法

使用指定的格式集合、格式提供程序和格式化样式，将指定的字符串转换为 [DateTimeOffset](../) 对象。

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 用于转换。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) 格式字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和时间格式化样式。 |

### 返回值

[DateTimeOffset](../) 等价于 **input**。

## 另请参阅

* 枚举 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [DateTimeOffset](../)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)