---
title: Char
second_title: Aspose.Slides C++ API 參考
description: 提供以 UTF-16 代碼單元表示的字元操作方法。這是一個靜態類型，沒有實例服務。絕不應以任何方式建立其實例。
type: docs
weight: 170
url: /zh-hant/system/char/
---
## Char 類別

提供操作以 UTF-16 代碼單元表示的字元的方法。這是一個靜態型別，沒有實例服務。絕不應以任何方式建立其實例。

```cpp
class Char
```

## 方法

| Method | Description |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | 將 UTF-32 代碼單元轉換為 [System::String](../string/) 類別的實例。 |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | 將指定的 UTF-16 代理對轉換為 UTF-32 代碼單元。 |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | 將字串中指定位置的 UTF-16 編碼字元或代理對的值轉換為 UTF-32 代碼單元。 |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | 將指定的 UTF-16 字元轉換為雙精度浮點數值。 |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | 傳回表示指定字元之 Unicode 類別的值。 |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | 判斷指定的字元是否被歸類為 ASCII 空白字元。 |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為 Unicode 控制字元。 |
| static **bool** [IsControl](./iscontrol/)(char_t) | 判斷指定的字元是否被歸類為 Unicode 控制字元。 |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為十進位數字。 |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | 判斷指定字串中指定索引處的字元是否被歸類為十進位數字。 |
| static **bool** [IsDigit](./isdigit/)(char_t) | 判斷指定的字元是否被歸類為十進位數字。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | 判斷指定字串中指定索引處的字元是否為 UTF-16 高位代理代碼單元。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否為高位代理。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | 判斷指定的字元是否為高位代理。 |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為 Unicode 字母。 |
| static **bool** [IsLetter](./isletter/)(char_t) | 判斷指定的字元是否被歸類為 Unicode 字母。 |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為 Unicode 字母或十進位數字。 |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | 判斷指定的字元是否被歸類為 Unicode 字母或十進位數字。 |
| static **bool** [IsLower](./islower/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為小寫字母。 |
| static **bool** [IsLower](./islower/)(char_t) | 判斷指定的字元是否被歸類為小寫字母。 |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | 判斷指定字串中指定索引處的字元是否被歸類為小寫字母。 |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否為低位代理。 |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | 判斷指定的字元是否為低位代理。 |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為數字。 |
| static **bool** [IsNumber](./isnumber/)(char_t) | 判斷指定的字元是否被歸類為數字。 |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為標點字元。 |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | 判斷指定的字元是否被歸類為標點字元。 |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為分隔字元。 |
| static **bool** [IsSeparator](./isseparator/)(char_t) | 判斷指定的字元是否被歸類為分隔字元。 |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | 判斷指定的字元是否為 UTF-16 代理代碼單元。 |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | 判斷指定字串中指定索引處的字元是否為 UTF-16 代理代碼單元。 |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | 判斷兩個指定的字元是否構成 UTF-16 代理對。 |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | 判斷指定字元緩衝區中相繼的兩個字元是否為代理對。 |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為符號字元。 |
| static **bool** [IsSymbol](./issymbol/)(char_t) | 判斷指定的字元是否被歸類為符號字元。 |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | 判斷指定字串中指定索引處的字元是否被歸類為大寫字母。 |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為大寫字母。 |
| static **bool** [IsUpper](./isupper/)(char_t) | 判斷指定的字元是否被歸類為大寫字母。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | 判斷指定字元緩衝區中指定索引處的字元是否被歸類為空白字元。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | 判斷指定的字元是否被歸類為空白字元。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | 判斷指定字串中指定索引處的字元是否被歸類為空白字元。 |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | 將指定字串的唯一字元轉換為 char_t 值。 |
| static char_t [ToLower](./tolower/)(char_t) | 將指定的字元轉換為小寫。 |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 將指定的字元轉換為小寫。 |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | 將指定的字元轉換為小寫。 |
| static char_t [ToUpper](./toupper/)(char_t) | 將指定的字元轉換為大寫。 |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 將指定的字元轉換為大寫。 |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | 將指定的字元轉換為大寫。 |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | 嘗試將僅包含單一字元的字串轉換為 UTF-16 字元。僅當輸入字串非空且長度恰好為一個字元時，函式才會成功。 |

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)