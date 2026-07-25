---
title: UInt16
second_title: Aspose.Slides for C++ API リファレンス
description: 符号なし 16 ビット整数を操作するためのメソッドを含みます。
type: docs
weight: 1964
url: /ja/system/uint16/
---
## UInt16 構造体

符号なし 16 ビット整数を操作するためのメソッドを含みます。

```cpp
class UInt16
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列（数値の文字列表現を含む）を、同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報および数値スタイルを使用して、同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint16_t**\&) | 指定された文字列（数値の文字列表現を含む）を、同等の 16 ビット符号なし整数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint16_t**\&) | 指定された文字列（数値の文字一覧現を含む）を、提供された書式情報および数値スタイルを使用して、同等の 16 ビット符号なし整数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint16_t**\&) |  |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 取り得る最大の値。 |
| static constexpr [MinValue](./minvalue/) | 取り得る最小の値。 |

## 関連項目

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)