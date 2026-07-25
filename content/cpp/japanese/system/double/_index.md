---
title: Double
second_title: Aspose.Slides for C++ API リファレンス
description: double精度浮動小数点数を扱うためのメソッドを含みます。
type: docs
weight: 1574
url: /ja/system/double/
---
## Double struct

double精度浮動小数点数を扱うためのメソッドを含みます。

```cpp
class Double
```

## Methods

| メソッド | 説明 |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列（数値の文字列表現）を同等のdouble精度浮動小数点値に変換します。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現）を、提供された書式情報を使用して同等のdouble精度浮動小数点値に変換します。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現）を、提供された書式情報と数値スタイルを使用して同等のdouble精度浮動小数点値に変換します。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | 指定された文字列（数値の文字列表現）を同等のdouble精度浮動小数点値に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | 指定された文字列（数値の文字列表現）を、提供された書式情報と数値スタイルを使用して同等のdouble精度浮動小数点値に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Fields

| フィールド | 説明 |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | 0より大きい最小の正の値。 |
| static constexpr [MaxValue](./maxvalue/) | 可能な最大値。 |
| static constexpr [MinValue](./minvalue/) | 可能な最小値。 |
| static constexpr [NaN](./nan/) | 数値ではない値 (NaN)。 |
| static constexpr [NegativeInfinity](./negativeinfinity/) | 負の無限大。 |
| static constexpr [PositiveInfinity](./positiveinfinity/) | 正の無限大。 |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)