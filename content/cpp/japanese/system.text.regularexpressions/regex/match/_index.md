---
title: Match()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列に対して正規表現を照合します。
type: docs
weight: 66
url: /ja/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) メソッド

文字列に対して正規表現を照合します。

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 対象文字列。 |

### 戻り値

[Match](../../match/) マッチステータスとサブマッチを含む値。

## Regex::Match(const String\&, int, int) メソッド

文字列に対して正規表現を照合します。

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 対象文字列。 |
| startat | int | 開始インデックス。 |
| length | int | 検索する文字数 (0 は文字列全体を検索)。 |

### 戻り値

[Match](../../match/) マッチステータスとサブマッチを含む値。

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) メソッド

文字列とパターンを照合します。

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const [String](../../../system/string/)\& | 正規表現パターン。 |
| options | [RegexOptions](../../regexoptions/) | マッチングオプション。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | タイムアウト。 |
| startat | int | [Match](../../match/) 開始位置。 |
| length | int | 検索する文字数 (0 は制限なし)。 |

### 戻り値

最初に見つかった一致。

## 参照

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)