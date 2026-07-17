---
title: Replace()
second_title: Aspose.Slides for C++ API 参考
description: 将字符串中正则表达式的所有匹配项替换为替换字符串。
type: docs
weight: 92
url: /zh/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) 方法


将字符串中所有正则匹配项替换为替换字符串。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| replacement | const [String](../../../system/string/)\& | 替换字符串。 |

### 返回值

返回所有正则匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const char_t *) 方法


将字符串中所有正则匹配项替换为替换字符串。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| replacement | const char_t * | 替换字符串。 |

### 返回值

返回所有正则匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const MatchEvaluator\&) 方法


将字符串中所有匹配项替换为委托生成的替换字符串。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 根据匹配项生成替换字符串的委托。 |

### 返回值

返回所有匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const MatchEvaluator\&, int) 方法


将字符串中所有匹配项替换为委托生成的替换字符串。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 根据匹配项生成替换字符串的委托。 |
| count | int | 替换次数上限。 |

### 返回值

返回所有匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) 方法


将字符串中所有匹配项替换为委托生成的替换字符串。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 根据匹配项生成替换字符串的委托。 |
| count | int | 替换次数上限。 |
| startat | int | 在输入字符串中开始替换的索引位置。 |

### 返回值

返回所有匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const String\&, int) 方法


在字符串中替换子串。未实现。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) 方法


在字符串中替换子串。未实现。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) 方法


将字符串中所有正则匹配项替换为替换字符串。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const char_t * | [Regex](../) 模式。 |
| replacement | const char_t * | 替换字符串。 |

### 返回值

返回所有正则匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const String\&, const char_t *) 方法


将字符串中所有正则匹配项替换为替换字符串。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 模式。 |
| replacement | const char_t * | 替换字符串。 |

### 返回值

返回所有正则匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) 方法


将字符串中所有匹配项替换为委托生成的替换字符串（静态函数）。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 模式。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 根据匹配项生成替换字符串的委托。 |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) 选项。 |

### 返回值

返回所有匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) 方法


将字符串中所有正则匹配项替换为替换字符串。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 模式。 |
| replacement | const [String](../../../system/string/)\& | 替换字符串。 |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) 选项。 |

### 返回值

返回所有正则匹配项已被替换的输入字符串。

## Regex::Replace(const String\&, const String\&, const String\&) 方法


替换正则匹配项。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | 正则表达式模式。 |
| replacement | const [String](../../../system/string/)\& | 替换字符串。 |

### 返回值

[String](../../../system/string/) 已经替换了所有匹配项。

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) 方法


替换正则匹配项。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 输入字符串。 |
| pattern | const [String](../../../system/string/)\& | 正则表达式模式。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 为每个匹配项生成替换字符串的委托。 |

### 返回值

[String](../../../system/string/) 已经替换了所有匹配项。

## 参见

* 枚举 [RegexOptions](../../regexoptions/)
* 类型定义 [MatchEvaluator](../../matchevaluator/)
* 类 [String](../../../system/string/)
* 类 [Regex](../)
* 命名空间 [System::Text::RegularExpressions](../../)
* 库 [Aspose.Slides](../../../)