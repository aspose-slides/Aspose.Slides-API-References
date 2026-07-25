---
title: Replace()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列内の正規表現のすべての一致を置換文字列で置き換えます。
type: docs
weight: 92
url: /ja/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) メソッド

正規表現のすべての一致を、置換文字列で置き換えます。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| replacement | const [String](../../../system/string/)\& | 置換文字列。 |

### 戻り値

正規表現のすべての一致が置換文字列で置き換えられた入力文字列。

## Regex::Replace(const String\&, const char_t *) メソッド

正規表現のすべての一致を、置換文字列で置き換えます。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| replacement | const char_t * | 置換文字列。 |

### 戻り値

正規表現のすべての一致が置換文字列で置き換えられた入力文字列。

## Regex::Replace(const String\&, const MatchEvaluator\&) メソッド

正規表現のすべての一致を、デリゲートで生成された置換文字列で置き換えます。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 一致に基づいて置換文字列を生成するデリゲート。 |

### 戻り値

すべての一致が置換された入力文字列。

## Regex::Replace(const String\&, const MatchEvaluator\&, int) メソッド

正規表現のすべての一致を、デリゲートで生成された置換文字列で置き換えます。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 一致に基づいて置換文字列を生成するデリゲート。 |
| count | int | 置換回数の上限。 |

### 戻り値

すべての一致が置換された入力文字列。

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) メソッド

正規表現のすべての一致を、デリゲートで生成された置換文字列で置き換えます。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 一致に基づいて置換文字列を生成するデリゲート。 |
| count | int | 置換回数の上限。 |
| startat | int | [Index](../../../system/index/) を入力文字列で置換開始位置として使用します。 |

### 戻り値

すべての一致が置換された入力文字列。

## Regex::Replace(const String\&, const String\&, int) メソッド

文字列の部分文字列を置換します。実装されていません。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) メソッド

文字列の部分文字列を置換します。実装されていません。

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) メソッド

正規表現のすべての一致を、置換文字列で置き換えます。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const char_t * | [Regex](../) パターン。 |
| replacement | const char_t * | 置換文字列。 |

### 戻り値

正規表現のすべての一致が置換文字列で置き換えられた入力文字列。

## Regex::Replace(const String\&, const String\&, const char_t *) メソッド

正規表現のすべての一致を、置換文字列で置き換えます。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) パターン。 |
| replacement | const char_t * | 置換文字列。 |

### 戻り値

正規表現のすべての一致が置換文字列で置き換えられた入力文字列。

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) メソッド

正規表現のすべての一致を、デリゲートで生成された置換文字列（静的関数）で置き換えます。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) パターン。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 一致に基づいて置換文字列を生成するデリゲート。 |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) オプション。 |

### 戻り値

すべての一致が置換された入力文字列。

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) メソッド

正規表現のすべての一致を、置換文字列で置き換えます。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const [String](../../../system/string/)\& | [Regex](../) パターン。 |
| replacement | const [String](../../../system/string/)\& | 置換文字列。 |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) オプション。 |

### 戻り値

正規表現のすべての一致が置換文字列で置き換えられた入力文字列。

## Regex::Replace(const String\&, const String\&, const String\&) メソッド

正規表現の一致を置換します。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const [String](../../../system/string/)\& | 正規表現パターン。 |
| replacement | const [String](../../../system/string/)\& | 置換文字列。 |

### 戻り値

[String](../../../system/string/) がすべての一致で置換されました。

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) メソッド

正規表現の一致を置換します。

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const [String](../../../system/string/)\& | 正規表現パターン。 |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 各一致に対して置換文字列を生成するデリゲート。 |

### 戻り値

[String](../../../system/string/) がすべての一致で置換されました。

## 参照

* 列挙体 [RegexOptions](../../regexoptions/)
* 型定義 [MatchEvaluator](../../matchevaluator/)
* クラス [String](../../../system/string/)
* クラス [Regex](../)
* 名前空間 [System::Text::RegularExpressions](../../)
* ライブラリ [Aspose.Slides](../../../)