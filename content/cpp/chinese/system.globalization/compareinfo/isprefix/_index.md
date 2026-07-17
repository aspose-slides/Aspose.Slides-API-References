---
title: IsPrefix()
second_title: Aspose.Slides C++ API 参考
description: 检查指定的字符串是否以指定的前缀开头，并使用指定的比较选项。
type: docs
weight: 105
url: /zh/system.globalization/compareinfo/isprefix/
---
## CompareInfo::IsPrefix(const String\&, const String\&, CompareOptions) const 方法

检查指定的字符串是否以指定的前缀开头，并使用指定的比较选项。

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix, CompareOptions options) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 源字符串。 |
| prefix | const [String](../../../system/string/)\& | 前缀字符串。 |
| options | [CompareOptions](../../compareoptions/) | 比较选项。 |

### 返回值

如果字符串以该前缀开头则返回 true；否则返回 false。

## CompareInfo::IsPrefix(const String\&, const String\&) const 方法

检查指定的字符串是否以指定的前缀开头。

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 源字符串。 |
| prefix | const [String](../../../system/string/)\& | 前缀字符串。 |

### 返回值

如果字符串以该前缀开头则返回 true；否则返回 false。

## 另请参见

* 枚举 [CompareOptions](../../compareoptions/)
* 类 [String](../../../system/string/)
* 类 [CompareInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)