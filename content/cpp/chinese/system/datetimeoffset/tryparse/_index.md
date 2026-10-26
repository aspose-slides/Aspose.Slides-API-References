---
title: TryParse()
second_title: Aspose.Slides C++ API 参考
description: 尝试将指定的字符串转换为 DateTimeOffset 对象。
type: docs
weight: 729
url: /zh/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) 方法

尝试将指定的字符串转换为 [DateTimeOffset](../) 对象。

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 用于转换的 [String](../../string/)。 |
| result | [DateTimeOffset](../)\& | 与 **input** 等价的 [DateTimeOffset](../)。 |

### 返回值

如果 **input** 成功转换则返回 true，否则返回 false。

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) 方法

尝试使用指定的格式提供程序和格式样式将指定的字符串转换为 [DateTimeOffset](../) 对象。

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 用于转换的 [String](../../string/)。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和时间格式样式。 |
| result | [DateTimeOffset](../)\& | 与 **input** 等价的 [DateTimeOffset](../)。 |

### 返回值

如果 **input** 成功转换则返回 true，否则返回 false。

## 另请参见

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)