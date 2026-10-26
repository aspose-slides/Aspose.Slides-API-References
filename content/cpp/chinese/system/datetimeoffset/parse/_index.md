---
title: Parse()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的字符串转换为等价的 DateTimeOffset。
type: docs
weight: 703
url: /zh/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) 方法

将指定的字符串转换为等价的 [DateTimeOffset](../)。

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 用于转换。 |

### 返回值

[DateTimeOffset](../) 等价于 **input**。

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 方法

使用指定的格式提供程序和格式样式，将指定的字符串转换为 [DateTimeOffset](../) 对象。

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 用于转换。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期和时间的格式样式。 |

### 返回值

[DateTimeOffset](../) 等价于 **input**。

## 另见

* 枚举 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [DateTimeOffset](../)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)