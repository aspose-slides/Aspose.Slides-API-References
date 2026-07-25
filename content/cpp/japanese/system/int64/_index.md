---
title: Int64
second_title: Aspose.Slides for C++ API リファレンス
description: 64 ビット整数を操作するためのメソッドを含みます。
type: docs
weight: 1054
url: /ja/system/int64/
---
## Int64 クラス

64 ビット整数を操作するためのメソッドを含みます。

```cpp
class Int64
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列（数値の文字列表現を含む）を、同等の 64 ビット符号付き整数に変換します。 |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報を使用して同等の 64 ビット符号付き整数に変換します。 |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して同等の 64 ビット符号付き整数に変換します。 |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int64_t**\&) | 指定された文字列（数値の文字列表現を含む）を、同等の 64 ビット符号付き整数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int64_t**\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して同等の 64 ビット符号付き整数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) |  |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 取りうる最大の値。 |
| static constexpr [MinValue](./minvalue/) | 取りうる最小の値。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)