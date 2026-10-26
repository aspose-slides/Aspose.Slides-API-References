---
title: Single
second_title: Aspose.Slides for C++ API リファレンス
description: 単精度浮動小数点数を扱うメソッドを含みます。
type: docs
weight: 1899
url: /ja/system/single/
---
## 単一構造体

単精度浮動小数点数を扱うメソッドを含みます。

```cpp
class Single
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列（数値の文字列表現を含む）を、対応する単精度浮動小数点値に変換します。 |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報を使用して対応する単精度浮動小数点値に変換します。 |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して対応する単精度浮動小数点値に変換します。 |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | 指定された文字列（数値の文字列表現を含む）を、対応する単精度浮動小数点値に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して対応する単精度浮動小数点値に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | 0 より大きい最小の正の値です。 |
| static constexpr [MaxValue](./maxvalue/) | 可能な最大値です。 |
| static constexpr [MinValue](./minvalue/) | 可能な最小値です。 |
| static constexpr [NaN](./nan/) | 数値ではない値です。 |
| static constexpr [NegativeInfinity](./negativeinfinity/) | 負の無限大です。 |
| static constexpr [PositiveInfinity](./positiveinfinity/) | 正の無限大です。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)