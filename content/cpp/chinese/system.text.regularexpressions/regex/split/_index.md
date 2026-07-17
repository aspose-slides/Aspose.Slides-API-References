---
title: Split()
second_title: Aspose.Slides for C++ API 参考
description: 按正则表达式匹配拆分字符串。
type: docs
weight: 105
url: /zh/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) method

按正则表达式匹配拆分字符串。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于拆分。 |

### 返回值

[Array](../../../system/array/) 的子字符串（在匹配之间）。

## Regex::Split(const String\&, int) method

按正则表达式匹配拆分字符串。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于拆分。 |
| count | int | 子字符串数量限制。 |

### 返回值

[Array](../../../system/array/) 的子字符串（在匹配之间）。

## Regex::Split(const String\&, int, int) method

将输入字符串在由 [Regex](../) 构造函数指定的正则表达式定义的位置，最多拆分指定次数，生成子字符串数组。正则表达式模式的搜索从输入字符串的指定字符位置开始。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 要拆分的字符串。 |
| count | int | 拆分可以发生的最大次数。 |
| startat | int | 在输入字符串中开始搜索的字符位置。 |

### 返回值

字符串数组。

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) method

按正则表达式拆分字符串。

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | 正则表达式模式。 |
| options | [RegexOptions](../../regexoptions/) | 匹配选项。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 超时。 |

### 返回值

[Array](../../../system/array/) 的字符串（在匹配之间）。

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) method

按正则表达式拆分字符串。

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | 正则表达式模式。 |
| count | int | [Match](../../match/) 数量限制。 |
| options | [RegexOptions](../../regexoptions/) | 匹配选项。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 超时。 |

### 返回值

[Array](../../../system/array/) 的字符串（在匹配之间）。

## 另请参见

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)