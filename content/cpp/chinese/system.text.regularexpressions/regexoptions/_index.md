---
title: RegexOptions
second_title: Aspose.Slides for C++ API 参考
description: 正则表达式选项。
type: docs
weight: 118
url: /zh/system.text.regularexpressions/regexoptions/
---
## RegexOptions 枚举

[Regex](../regex/) 选项.
```cpp
enum class RegexOptions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 默认行为. |
| Compiled | 1 | 编译正则表达式以提升性能。默认始终编译. |
| CultureInvariant | 2 | 使用不区分区域性的匹配。已忽略. |
| ECMAScript | 4 | 使用 ECMAScript 语法。已忽略. |
| ExplicitCapture | 8 | 仅显式捕获。已忽略. |
| IgnoreCase | 16 | 匹配时忽略大小写. |
| IgnorePatternWhitespace | 32 | 忽略模式中的空白字符。不受支持. |
| Multiline | 64 | 将 '^' 和 '$' 视为行首和行尾，而非整个字符串的开始和结束. |
| RightToLeft | 128 | 从右到左匹配。不受支持. |
| Singleline | 256 | 使 '.' 匹配任何字符，无例外（通常，换行符不匹配）. |

## 另请参阅

* 命名空间 [System::Text::RegularExpressions](../)
* 库 [Aspose.Slides](../../)