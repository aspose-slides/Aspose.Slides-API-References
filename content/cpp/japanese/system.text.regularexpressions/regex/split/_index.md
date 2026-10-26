---
title: Split()
second_title: Aspose.Slides for C++ API リファレンス
description: 正規表現の一致で文字列を分割します。
type: docs
weight: 105
url: /ja/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) メソッド

正規表現の一致で文字列を分割します。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) を分割します。 |

### 戻り値

[Array](../../../system/array/) は一致間の部分文字列です。

## Regex::Split(const String\&, int) メソッド

正規表現の一致で文字列を分割します。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) を分割します。 |
| count | int | 部分文字列の数制限。 |

### 戻り値

[Array](../../../system/array/) は一致間の部分文字列です。

## Regex::Split(const String\&, int, int) メソッド

入力文字列を、[Regex](../) コンストラクタで指定された正規表現で定義された位置で、指定された最大回数だけ部分文字列の配列に分割します。正規表現パターンの検索は、入力文字列内の指定された文字位置から開始します。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 分割する文字列です。 |
| count | int | 分割が発生できる最大回数。 |
| startat | int | 検索が開始される入力文字列内の文字位置。 |

### 戻り値

文字列の配列。

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) メソッド

正規表現で文字列を分割します。

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列です。 |
| pattern | const [String](../../../system/string/)\& | 正規表現パターンです。 |
| options | [RegexOptions](../../regexoptions/) | マッチングオプションです。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | タイムアウトです。 |

### 戻り値

[Array](../../../system/array/) はマッチ間の文字列です。

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) メソッド

正規表現で文字列を分割します。

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列です。 |
| pattern | const [String](../../../system/string/)\& | 正規表現パターンです。 |
| count | int | [Match](../../match/) の数制限。 |
| options | [RegexOptions](../../regexoptions/) | マッチングオプションです。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | タイムアウトです。 |

### 戻り値

[Array](../../../system/array/) はマッチ間の文字列です。

## 参照

* 列挙 [RegexOptions](../../regexoptions/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [Regex](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Text::RegularExpressions](../../)
* ライブラリ [Aspose.Slides](../../../)