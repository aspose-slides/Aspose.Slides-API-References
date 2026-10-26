---
title: CompareOptions
second_title: Aspose.Slides for C++ API 参考
description: 字符串比较选项。
type: docs
weight: 430
url: /zh/system.globalization/compareoptions/
---
## CompareOptions 枚举

[String](../../system/string/) 比较选项。

```cpp
enum class CompareOptions : int32_t
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 无特殊选项。 |
| IgnoreCase | 1 | 忽略大小写。 |
| IgnoreNonSpace | 2 | 忽略非间距组合字符，例如变音符号。 |
| IgnoreSymbols | 4 | 包括空格、标点符号等。 |
| IgnoreKanaType | 8 | 忽略假名类型（日语）。 |
| IgnoreWidth | 16 | 忽略比较字符串时的字符宽度。 |
| OrdinalIgnoreCase | 268435456 | 序数比较且忽略大小写差异。 |
| StringSort | 536870912 | 使用字符串排序算法比较字符。 |
| Ordinal | 1073741824 | 直接比较 UTF 代码点进行首次比较。 |

## 另请参见

* 命名空间 [System::Globalization](../)
* 库 [Aspose.Slides](../../)