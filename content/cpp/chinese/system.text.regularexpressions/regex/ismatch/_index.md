---
title: IsMatch()
second_title: Aspose.Slides for C++ API 参考
description: 将正则表达式匹配到字符串。
type: docs
weight: 53
url: /zh/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) 方法

匹配正则表达式与字符串。

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 目标字符串。 |
| startat | int | 起始索引。 |

### 返回值

如果字符串匹配正则表达式则返回 true，否则返回 false。

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) 方法

检查字符串是否匹配模式。

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | 正则表达式模式。 |
| options | [RegexOptions](../../regexoptions/) | 匹配选项。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 超时。 |
| startat | int | [Match](../../match/) 起始位置。 |

### 返回值

如果找到匹配则返回 true，否则返回 false。

## 另见

* Enum [RegexOptions](../../regexoptions/)
* 类 [String](../../../system/string/)
* 类 [Regex](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)