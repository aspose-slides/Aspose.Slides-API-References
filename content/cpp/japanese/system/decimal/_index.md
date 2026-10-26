---
title: Decimal
second_title: Aspose.Slides for C++ API リファレンス
description: "10 進数を表します。この型はスタック上に確保し、値または参照で関数に渡すべきです。この型のオブジェクトを管理するために System::SmartPtr クラスを使用しないでください。"
type: docs
weight: 261
url: /ja/system/decimal/
---
## Decimal クラス

Represents a decimal number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Decimal
```

## メソッド

| Method | Description |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | 指定された [Decimal](./) 値を2つ加算します。 |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | 指定された値以上の最小の整数値を返します。 |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | 最初の [Decimal](./) オブジェクトが表す値が、2番目の [Decimal](./) オブジェクトが表す値より小さいか、等しいか、または大きいかを判定します。 |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | 現在のオブジェクトが表す値が、指定されたオブジェクトが表す値より小さいか、等しいか、または大きいかを判定します。 |
| [Decimal](./decimal/)() | 0 を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(std::int8_t) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(std::int16_t) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(std::int32_t) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(std::int64_t) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(std::uint8_t) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(std::uint16_t) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(std::uint32_t) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(std::uint64_t) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(**float**) | 指定された値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(**double**) | 指定された値を表すインスタンスを構築します。 |
| explicit [Decimal](./decimal/)(const std::string\&) | std::string クラスのインスタンスとして指定された文字列表現を持つ値を表すインスタンスを構築します。 |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | [Decimal](./) オブジェクトを指定された構成要素から構築します。 |
| [Decimal](./decimal/)(const [Decimal](./)\&) | [Decimal](./) クラスのインスタンスを構築し、指定された [Decimal](./) オブジェクトと同じ数値を表します。 |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | [Decimal](./) クラスのインスタンスを、2 進表現を含む整数配列から構築します。 |
| [Decimal](./decimal/)(std::nullptr_t) | 常に ArgumentNullException をスローします。 |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | 指定された値を表す [Decimal](./) クラスのインスタンスを構築します。 |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | 指定された [Decimal](./) 値を2つ除算します。 |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す値が等しいかどうかを判定します。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 現在のオブジェクトと指定されたオブジェクトが表す値が等しいかどうかを判定します。 |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | 指定されたオブジェクトが表す値が等しいかどうかを判定します。 |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | 指定された値以下の最大の整数値を返します。 |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) 指定された OLE 通貨値を等価な [Decimal](./) 値に変換します。未実装。 |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | 指定された [Decimal](./) オブジェクトを、その表す値の 2 進表現に変換します。 |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) 指定された [Decimal](./) 値をバイト配列に変換します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | オブジェクトのタイプコードを取得します。 |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | 指定された [Decimal](./) 値を2つ乗算します。 |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | 指定されたオブジェクトが表す値の否定結果を表す新しい [Decimal](./) クラスのインスタンスを返します。 |
| explicit [operator bool](./operator_bool/)() const | 現在のオブジェクトが表す値をブール値に変換します。 |
| explicit [operator double](./operator_double/)() const | 現在のオブジェクトが表す値を double 精度浮動小数点数に変換します。 |
| explicit [operator float](./operator_float/)() const | 現在のオブジェクトが表す値を single 精度浮動小数点数に変換します。 |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す値が等しくないかどうかを判定します。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 現在のオブジェクトが表す値が 0 と異なるかどうかを判定します。 |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す値での剰余演算結果を表す新しい [Decimal](./) クラスのインスタンスを返します。 |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | 現在のオブジェクトと指定されたオブジェクトが表す値の剰余演算結果を新しい値として現在のオブジェクトに代入します。 |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す値の乗算結果を表す新しい [Decimal](./) クラスのインスタンスを返します。 |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | 現在のオブジェクトと指定されたオブジェクトが表す値の乗算結果を新しい値として現在のオブジェクトに代入します。 |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す値の合計を表す新しい [Decimal](./) クラスのインスタンスを返します。 |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | 現在のオブジェクトが表す値をインクリメントします。 |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | 現在のオブジェクトと指定されたオブジェクトが表す値の合計を新しい値として現在のオブジェクトに代入します。 |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | 現在のオブジェクトが表す値から指定されたオブジェクトが表す値を減算した結果を表す新しい [Decimal](./) クラスのインスタンスを返します。 |
| [Decimal](./) [operator-](./operator_minus/)() const | 現在のオブジェクトが表す値の否定結果を表す新しい [Decimal](./) クラスのインスタンスを返します。 |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | 現在のオブジェクトが表す値をデクリメントします。 |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | 現在のオブジェクトが表す値から指定されたオブジェクトが表す値を減算した結果を新しい値として現在のオブジェクトに代入します。 |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | 現在のオブジェクトが表す値を指定されたオブジェクトが表す値で除算した結果を表す新しい [Decimal](./) クラスのインスタンスを返します。 |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | 現在のオブジェクトが表す値を指定されたオブジェクトが表す値で除算した結果を新しい値として現在のオブジェクトに代入します。 |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | 現在のオブジェクトが表す値が、指定されたオブジェクトが表す値より小さいかどうかを判定します。 |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | 現在のオブジェクトが表す値が、指定されたオブジェクトが表す値以下かどうかを判定します。 |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | 指定されたオブジェクトが表す値を現在のオブジェクトに代入します。 |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す値が等しいかどうかを判定します。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 現在のオブジェクトが表す値が 0 かどうかを判定します。 |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | 現在のオブジェクトが表す値が、指定されたオブジェクトが表す値より大きいかどうかを判定します。 |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | 現在のオブジェクトが表す値が、指定されたオブジェクトが表す値以上かどうかを判定します。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | 10 進数の文字列表現を [Decimal](./) クラスの等価なインスタンスに変換します。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | 指定されたスタイルを使用して、10 進数の文字列表現を [Decimal](./) クラスの等価なインスタンスに変換します。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された書式プロバイダーを使用して、10 進数の文字列表現を [Decimal](./) クラスの等価なインスタンスに変換します。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたスタイルと書式プロバイダーを使用して、10 進数の文字列表現を [Decimal](./) クラスの等価なインスタンスに変換します。 |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | 2 つの [Decimal](./) 値を除算した余りを計算します。 |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | 指定された値を最も近い整数に丸めます。パラメーターは、指定された値が2つの最寄り整数と同等に近い場合の関数の動作を指定します。 |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | 指定された小数桁数で、指定された値を最も近い値に丸めます。パラメーターは、指定された値が2つの最寄りの数と同等に近い場合の関数の動作を指定します。 |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | 指定された 1 つの [Decimal](./) 値をもう 1 つから減算します。 |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | [Decimal](./) 値を符号なし 8 ビット整数に変換します。 |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | [Decimal](./) 値を double 精度浮動小数点数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | [Decimal](./) 値を符号付き 16 ビット整数に変換します。 |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | [Decimal](./) 値を符号付き 32 ビット整数に変換します。 |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | [Decimal](./) 値を符号付き 64 ビット整数に変換します。 |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) 指定された [Decimal](./) 値を等価な OLE 通貨値に変換します。未実装。 |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | [Decimal](./) 値を符号付き 8 ビット整数に変換します。 |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | [Decimal](./) 値を単精度浮動小数点数に変換します。 |
| std::string [ToStdString](./tostdstring/)() const | オブジェクトが表す値の文字列表現を含む std::string のインスタンスを返します。 |
| [String](../string/) [ToString](./tostring/)() const | オブジェクトが表す値の文字列表現を返します。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 現在のオブジェクトを、カルチャ固有の書式情報を使用して文字列に変換します。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 指定された文字列書式と、指定された [IFormatProvider](../iformatprovider/) オブジェクトが提供するカルチャ固有の書式情報を使用して、現在のオブジェクトを文字列表現に変換します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | オブジェクトが表す値の文字列表現を返します。内部使用向けです。 |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | [Decimal](./) 値を符号なし 16 ビット整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | [Decimal](./) 値を符号なし 32 ビット整数に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | [Decimal](./) 値を符号なし 64 ビット整数に変換します。 |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | 指定された [Decimal](./) オブジェクトが表す値の整数部と等しい値を表す [Decimal](./) オブジェクトを返し、すべての小数部は破棄されます。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | 数値の文字列表現を含む指定された文字列を、等価な [Decimal](./) 値に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | 提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を等価な [Decimal](./) 値に変換します。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [Decimal](./) クラスの型情報を表す [TypeInfo](../typeinfo/) オブジェクトへの参照を返します。 |
| [~Decimal](./~decimal/)() | デストラクタです。 |

## フィールド

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | [Decimal](./) クラスで表現可能な最大の数値を表します。 |
| static [MinusOne](./minusone/) | -1 の数値を表します。 |
| static [MinValue](./minvalue/) | [Decimal](./) クラスで表現可能な最小の数値を表します。 |
| static [One](./one/) | 1 の数値を表します。 |
| static [Zero](./zero/) | 0 の数値を表します。 |

## 型定義

| Typedef | Description |
| --- | --- |
| [number_type](./number_type/) | Detail::decimal_number_type の別名です。 |

## 備考

```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
このコード例は次の出力を生成します:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)