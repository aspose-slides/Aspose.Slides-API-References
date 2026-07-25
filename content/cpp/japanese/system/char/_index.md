---
title: Char
second_title: Aspose.Slides for C++ APIリファレンス
description: UTF-16 コード単位で表現された文字の操作用メソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはいけません。
type: docs
weight: 170
url: /ja/system/char/
---
## Char クラス


Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Char
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | UTF-32 コード単位を [System::String](../string/) クラスのインスタンスに変換します。 |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | 指定された UTF-16 サロゲートペアを UTF-32 コード単位に変換します。 |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | 文字列中の指定位置にある UTF-16 エンコード文字またはサロゲートペアの値を UTF-32 コード単位に変換します。 |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | 指定された UTF-16 文字を倍精度浮動小数点数値に変換します。 |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | 指定された文字の Unicode カテゴリを表す値を返します。 |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | 指定された文字が ASCII の空白文字として分類されるかどうかを判定します。 |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が Unicode 制御文字として分類されるかどうかを判定します。 |
| static **bool** [IsControl](./iscontrol/)(char_t) | 指定された文字が Unicode 制御文字として分類されるかどうかを判定します。 |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が10 進数字として分類されるかどうかを判定します。 |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | 指定された文字列内の指定インデックスの文字が10 進数字として分類されるかどうかを判定します。 |
| static **bool** [IsDigit](./isdigit/)(char_t) | 指定された文字が10 進数字として分類されるかどうかを判定します。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | 指定された文字列内の指定インデックスの文字が UTF-16 の上位サロゲートコード単位かどうかを判定します。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が上位サロゲートかどうかを判定します。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | 指定された文字が上位サロゲートかどうかを判定します。 |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が Unicode の文字として分類されるかどうかを判定します。 |
| static **bool** [IsLetter](./isletter/)(char_t) | 指定された文字が Unicode の文字として分類されるかどうかを判定します。 |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が Unicode の文字または10 進数字として分類されるかどうかを判定します。 |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | 指定された文字が Unicode の文字または10 進数字として分類されるかどうかを判定します。 |
| static **bool** [IsLower](./islower/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が小文字として分類されるかどうかを判定します。 |
| static **bool** [IsLower](./islower/)(char_t) | 指定された文字が小文字として分類されるかどうかを判定します。 |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | 指定された文字列内の指定インデックスの文字が小文字として分類されるかどうかを判定します。 |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が下位サロゲートかどうかを判定します。 |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | 指定された文字が下位サロゲートかどうかを判定します。 |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が数値として分類されるかどうかを判定します。 |
| static **bool** [IsNumber](./isnumber/)(char_t) | 指定された文字が数値として分類されるかどうかを判定します。 |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が句読点文字として分類されるかどうかを判定します。 |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | 指定された文字が句読点文字として分類されるかどうかを判定します。 |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が区切り文字として分類されるかどうかを判定します。 |
| static **bool** [IsSeparator](./isseparator/)(char_t) | 指定された文字が区切り文字として分類されるかどうかを判定します。 |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | 指定された文字が UTF-16 のサロゲートコード単位かどうかを判定します。 |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | 指定された文字列内の指定インデックスの文字が UTF-16 のサロゲートコード単位かどうかを判定します。 |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | 指定された 2 つの文字が UTF-16 のサロゲートペアであるかどうかを判定します。 |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | 指定された文字バッファ内の連続する 2 文字がサロゲートペアであるかどうかを判定します。 |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字がシンボル文字として分類されるかどうかを判定します。 |
| static **bool** [IsSymbol](./issymbol/)(char_t) | 指定された文字がシンボル文字として分類されるかどうかを判定します。 |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | 指定された文字列内の指定インデックスの文字が大文字として分類されるかどうかを判定します。 |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が大文字として分類されるかどうかを判定します。 |
| static **bool** [IsUpper](./isupper/)(char_t) | 指定された文字が大文字として分類されるかどうかを判定します。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | 指定された文字バッファ内の指定インデックスの文字が空白文字として分類されるかどうかを判定します。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | 指定された文字が空白文字として分類されるかどうかを判定します。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | 指定された文字列内の指定インデックスの文字が空白文字として分類されるかどうかを判定します。 |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列の最初で唯一の文字を char_t 値に変換します。 |
| static char_t [ToLower](./tolower/)(char_t) | 指定された文字を小文字に変換します。 |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 指定された文字を小文字に変換します。 |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | 指定された文字を小文字に変換します。 |
| static char_t [ToUpper](./toupper/)(char_t) | 指定された文字を大文字に変換します。 |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 指定された文字を大文字に変換します。 |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | 指定された文字を大文字に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | 単一文字からなる文字列を UTF-16 文字に変換しようとします。入力文字列が null でなく、ちょうど1文字の長さである場合にのみ関数は成功します。 |
## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)