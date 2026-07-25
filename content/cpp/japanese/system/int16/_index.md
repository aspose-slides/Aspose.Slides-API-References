---
title: Int16
second_title: Aspose.Slides for C++ API リファレンス
description: 16ビット整数を操作するためのメソッドを含みます。
type: docs
weight: 1028
url: /ja/system/int16/
---
## Int16 クラス

16ビット整数を操作するためのメソッドを含みます。

```cpp
class Int16
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を、対応する 16 ビット符号付き整数に変換します。 |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を、対応する 16 ビット符号付き整数に変換します。 |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を、対応する 16 ビット符号付き整数に変換します。 |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int16_t**\&) | 数値の文字列表現を含む指定された文字列を、対応する 16 ビット符号付き整数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int16_t**\&) | 提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を、対応する 16 ビット符号付き整数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int16_t**\&) |  |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 可能な最大値。 |
| static constexpr [MinValue](./minvalue/) | 可能な最小値。 |

## 関連項目

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)