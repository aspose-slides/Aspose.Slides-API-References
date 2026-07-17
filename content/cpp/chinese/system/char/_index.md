---
title: Char
second_title: Aspose.Slides for C++ API 参考
description: 提供用于操作以 UTF-16 代码单元表示的字符的方法。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。
type: docs
weight: 170
url: /zh/system/char/
---
## Char 类

提供用于操作表示为 UTF-16 代码单元的字符的方法。它是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。

```cpp
class Char
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | 将 UTF-32 代码单元转换为 [System::String](../string/) 类的实例。 |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | 将指定的 UTF-16 代理对转换为 UTF-32 代码单元。 |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | 将字符串中指定位置的 UTF-16 编码字符或代理对的值转换为 UTF-32 代码单元。 |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | 将指定的 UTF-16 字符转换为双精度浮点数值。 |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | 返回表示指定字符的 Unicode 类别的值。 |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | 确定指定字符是否被归类为 ASCII 空白字符。 |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为 Unicode 控制字符。 |
| static **bool** [IsControl](./iscontrol/)(char_t) | 确定指定字符是否被归类为 Unicode 控制字符。 |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为十进制数字。 |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | 确定指定字符串中指定索引处的字符是否被归类为十进制数字。 |
| static **bool** [IsDigit](./isdigit/)(char_t) | 确定指定字符是否被归类为十进制数字。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | 确定指定字符串中指定索引处的字符是否为 UTF-16 高代理代码单元。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否为高代理。 |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | 确定指定字符是否为高代理。 |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为 Unicode 字母。 |
| static **bool** [IsLetter](./isletter/)(char_t) | 确定指定字符是否被归类为 Unicode 字母。 |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为 Unicode 字母或十进制数字。 |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | 确定指定字符是否被归类为 Unicode 字母或十进制数字。 |
| static **bool** [IsLower](./islower/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为小写字母。 |
| static **bool** [IsLower](./islower/)(char_t) | 确定指定字符是否被归类为小写字母。 |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | 确定指定字符串中指定索引处的字符是否被归类为小写字母。 |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否为低代理。 |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | 确定指定字符是否为低代理。 |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为数字。 |
| static **bool** [IsNumber](./isnumber/)(char_t) | 确定指定字符是否被归类为数字。 |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为标点字符。 |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | 确定指定字符是否被归类为标点字符。 |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为分隔符。 |
| static **bool** [IsSeparator](./isseparator/)(char_t) | 确定指定字符是否被归类为分隔符。 |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | 确定指定字符是否为 UTF-16 代理代码单元。 |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | 确定指定字符串中指定索引处的字符是否为 UTF-16 代理代码单元。 |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | 确定两个指定字符是否为 UTF-16 代理对。 |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | 确定指定字符缓冲区中两个连续字符是否为代理对。 |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为符号字符。 |
| static **bool** [IsSymbol](./issymbol/)(char_t) | 确定指定字符是否被归类为符号字符。 |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | 确定指定字符串中指定索引处的字符是否被归类为大写字母。 |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为大写字母。 |
| static **bool** [IsUpper](./isupper/)(char_t) | 确定指定字符是否被归类为大写字母。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | 确定指定字符缓冲区中指定索引处的字符是否被归类为空白字符。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | 确定指定字符是否被归类为空白字符。 |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | 确定指定字符串中指定索引处的字符是否被归类为空白字符。 |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | 将指定字符串的唯一字符转换为 char_t 值。 |
| static char_t [ToLower](./tolower/)(char_t) | 将指定字符转换为小写。 |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 将指定字符转换为小写。 |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | 将指定字符转换为小写。 |
| static char_t [ToUpper](./toupper/)(char_t) | 将指定字符转换为大写。 |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 将指定字符转换为大写。 |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | 将指定字符转换为大写。 |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | 尝试将仅包含单个字符的字符串转换为 UTF-16 字符。该函数仅在输入字符串非空且长度恰好为一个字符时成功。 |

## 参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)