---
title: IsSuffix()
second_title: Aspose.Slides C++ API 参考
description: 检查使用指定的比较选项时，指定的字符串是否以指定的后缀结尾。
type: docs
weight: 118
url: /zh/system.globalization/compareinfo/issuffix/
---
## CompareInfo::IsSuffix(const String\&, const String\&, CompareOptions) const 方法

检查使用指定的比较选项时，指定的字符串是否以指定的后缀结尾。

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix, CompareOptions options) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 源字符串。 |
| suffix | const [String](../../../system/string/)\& | 后缀字符串。 |
| options | [CompareOptions](../../compareoptions/) | 比较选项。 |

### 返回值

如果字符串以后缀结尾则返回 true；否则返回 false。

## CompareInfo::IsSuffix(const String\&, const String\&) const 方法

检查指定的字符串是否以指定的后缀结尾。

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 源字符串。 |
| suffix | const [String](../../../system/string/)\& | 后缀字符串。 |

### 返回值

如果字符串以后缀结尾则返回 true；否则返回 false。

## 参见

* Enum [CompareOptions](../../compareoptions/)
* 类 [String](../../../system/string/)
* 类 [CompareInfo](../)
* 命名空间 [System::Globalization](../../)
* Library [Aspose.Slides](../../../)