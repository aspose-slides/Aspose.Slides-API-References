---
title: Replace()
second_title: Aspose.Slides for C++ API 參考文件
description: 將字串中符合正規表達式的所有項目取代為取代字串。
type: docs
weight: 92
url: /zh-hant/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) method


將字串中所有符合正規表達式的項目取代為取代字串。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| replacement | const [String](../../../system/string/)\& | 取代字串。 |

### 返回值

已將所有正規表達式符合項目取代為取代字串的輸入字串。

## Regex::Replace(const String\&, const char_t *) method


將字串中所有符合正規表達式的項目取代為取代字串。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| replacement | const char_t * | 取代字串。 |

### 返回值

已將所有正規表達式符合項目取代為取代字串的輸入字串。

## Regex::Replace(const String\&, const MatchEvaluator\&) method


將字串中所有符合項目以委派產生的取代字串取代。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 依符合項目產生取代字串的委派。 |

### 返回值

已將所有符合項目取代的輸入字串。

## Regex::Replace(const String\&, const MatchEvaluator\&, int) method


將字串中所有符合項目以委派產生的取代字串取代。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 依符合項目產生取代字串的委派。 |
| count | int | 取代次數上限。 |

### 返回值

已將所有符合項目取代的輸入字串。

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method


將字串中所有符合項目以委派產生的取代字串取代。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 依符合項目產生取代字串的委派。 |
| count | int | 取代次數上限。 |
| startat | int | [Index](../../../system/index/) 在輸入字串中的起始位置。 |

### 返回值

已將所有符合項目取代的輸入字串。

## Regex::Replace(const String\&, const String\&, int) method


在字串中取代子字串。未實作。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) method


在字串中取代子字串。未實作。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) method


將字串中所有符合正規表達式的項目取代為取代字串。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const char_t * | [Regex](../) 模式。 |
| replacement | const char_t * | 取代字串。 |

### 返回值

已將所有正規表達式符合項目取代為取代字串的輸入字串。

## Regex::Replace(const String\&, const String\&, const char_t *) method


將字串中所有符合正規表達式的項目取代為取代字串。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 模式。 |
| replacement | const char_t * | 取代字串。 |

### 返回值

已將所有正規表達式符合項目取代為取代字串的輸入字串。

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method


將字串中所有符合項目以委派產生的取代字串取代（靜態函式）。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 模式。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 依符合項目產生取代字串的委派。 |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) 選項。 |

### 返回值

已將所有符合項目取代的輸入字串。

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method


將字串中所有符合正規表達式的項目取代為取代字串。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 模式。 |
| replacement | const [String](../../../system/string/)\& | 取代字串。 |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) 選項。 |

### 返回值

已將所有正規表達式符合項目取代為取代字串的輸入字串。

## Regex::Replace(const String\&, const String\&, const String\&) method


取代正規表達式符合項目。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | 正規表達式模式。 |
| replacement | const [String](../../../system/string/)\& | 取代字串。 |

### 返回值

[String](../../../system/string/) 已取代所有符合項目。

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method


取代正規表達式符合項目。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | 正規表達式模式。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 為每個符合項目產生取代字串的委派。 |

### 返回值

[String](../../../system/string/) 已取代所有符合項目。

## 另見

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)