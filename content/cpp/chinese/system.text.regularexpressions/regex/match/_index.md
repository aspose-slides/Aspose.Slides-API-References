---
title: Match()
second_title: Aspose.Slides for C++ API 参考
description: 将正则表达式匹配到字符串。
type: docs
weight: 66
url: /zh/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) 方法


匹配正则表达式与字符串。

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 目标字符串。 |

### 返回值

[Match](../../match/) 包含匹配状态和子匹配的值。

## Regex::Match(const String\&, int, int) 方法


匹配正则表达式与字符串。

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 目标字符串。 |
| startat | int | 起始索引。 |
| length | int | 要遍历的字符数（0 表示遍历整个字符串）。 |

### 返回值

[Match](../../match/) 包含匹配状态和子匹配的值。

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) 方法


匹配字符串和模式。

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | 正则表达式模式。 |
| options | [RegexOptions](../../regexoptions/) | 匹配选项。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 超时。 |
| startat | int | [Match](../../match/) 起始位置。 |
| length | int | 要遍历的字符数（0 表示无限制）。 |

### 返回值

找到的第一个匹配。

## 另请参见

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)