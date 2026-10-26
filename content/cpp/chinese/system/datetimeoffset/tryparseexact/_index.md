---
title: TryParseExact()
second_title: Aspose.Slides for C++ API 参考
description: 尝试使用指定的格式、格式提供程序和格式化样式将指定的字符串转换为 DateTimeOffset 对象。
type: docs
weight: 742
url: /zh/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) 方法

尝试使用指定的格式、格式提供程序和格式化样式将指定的字符串转换为 [DateTimeOffset](../) 对象。

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 用于转换。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 格式字符串数组。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和时间格式化样式。 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) 与 **input** 等价。 |

### 返回值

如果 **input** 成功转换，则为 true；否则为 false。

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) 方法

尝试使用指定的格式、格式提供程序和格式化样式将指定的字符串转换为 [DateTimeOffset](../) 对象。

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 用于转换。 |
| format | const [String](../../string/)\& | 格式字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和时间格式化样式。 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) 与 **input** 等价。 |

### 返回值

如果 **input** 成功转换，则为 true；否则为 false。

## 另见

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)