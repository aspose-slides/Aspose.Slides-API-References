---
title: Matches()
second_title: Aspose.Slides for C++ API リファレンス
description: 正規表現のすべてのマッチを、文字列に対して繰り返しマッチさせることで取得します。
type: docs
weight: 79
url: /ja/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String&, int) メソッド


正規表現のすべてのマッチを、文字列に対して繰り返しマッチさせることで取得します。

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| startat | int | [Index](../../../system/index/) を開始位置として使用。 |

### 戻り値

見つかったすべてのマッチのコレクション。

## Regex::Matches(const String&, const String&, RegexOptions, TimeSpan, int, int) メソッド


文字列とパターン間のすべてのマッチを取得します。

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 入力文字列。 |
| pattern | const [String](../../../system/string/)\& | 正規表現パターン。 |
| options | [RegexOptions](../../regexoptions/) | マッチングオプション。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | タイムアウト。 |
| startat | int | [Match](../../match/) の開始位置。 |
| length | int | 検索する文字数 (0 は制限なし)。 |

### 戻り値

繰り返しマッチさせて見つかったすべてのマッチ。

## 参照

* 列挙体 [RegexOptions](../../regexoptions/)
* 型定義 [MatchCollectionPtr](../../matchcollectionptr/)
* クラス [String](../../../system/string/)
* クラス [Regex](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Text::RegularExpressions](../../)
* ライブラリ [Aspose.Slides](../../../)