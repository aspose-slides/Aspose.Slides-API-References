---
title: IsMatch()
second_title: Aspose.Slides for C++ APIリファレンス
description: 文字列に対して正規表現を照合します。
type: docs
weight: 53
url: /ja/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) メソッド

文字列に対して正規表現を照合します。

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| startat | int | 開始インデックス。 |

### 戻り値

文字列が正規表現に一致すれば true、そうでなければ false を返します。

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) メソッド

文字列がパターンに一致するか確認します。

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const [String](../../../system/string/)\& | 正規表現パターン。 |
| options | [RegexOptions](../../regexoptions/) | 照合オプション。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | タイムアウト。 |
| startat | int | [Match](../../match/) 開始位置。 |

### 戻り値

マッチが見つかれば true、そうでなければ false を返します。

## 参照

* Enum [RegexOptions](../../regexoptions/)
* クラス [String](../../../system/string/)
* クラス [Regex](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)