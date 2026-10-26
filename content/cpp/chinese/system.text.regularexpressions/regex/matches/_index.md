---
title: Matches()
second_title: Aspose.Slides for C++ API 参考
description: 通过重复匹配，在给定字符串中获取正则表达式的所有匹配项。
type: docs
weight: 79
url: /zh/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) 方法

在给定字符串中通过重复匹配获取正则表达式的所有匹配项。

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| startat | int | 开始匹配的索引。 |

### 返回值

找到的所有匹配项的集合。

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) 方法

获取字符串与模式之间的所有匹配。

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | 正则表达式模式。 |
| options | [RegexOptions](../../regexoptions/) | 匹配选项。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 超时。 |
| startat | int | [Match](../../match/) 起始位置。 |
| length | int | 要查看的字符数 (0 表示不限制)。 |

### 返回值

通过重复匹配找到的所有匹配项。

## 另见

* 枚举 [RegexOptions](../../regexoptions/)
* 类型定义 [MatchCollectionPtr](../../matchcollectionptr/)
* 类 [String](../../../system/string/)
* 类 [Regex](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Text::RegularExpressions](../../)
* 库 [Aspose.Slides](../../../)