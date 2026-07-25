---
title: TimeSpan
second_title: Aspose.Slides for C++ API リファレンス
description: "時間間隔を表します。この型はスタックに割り当て、値渡しまたは参照渡しで関数に渡す必要があります。System::SmartPtr クラスをこの型のオブジェクト管理に使用しないでください。"
type: docs
weight: 1314
url: /ja/system/timespan/
---
## TimeSpan クラス

時間間隔を表します。この型はスタックに割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスをこの型のオブジェクト管理に使用しないでください。

```cpp
class TimeSpan
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | 現在のオブジェクトと指定されたオブジェクトが表す時間間隔の合計を表す、[TimeSpan](./) クラスの新しいインスタンスを返します。 |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | 2つの [TimeSpan](./) オブジェクトを比較します。 |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | 現在のオブジェクトと指定されたオブジェクトを比較します。 |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 現在のオブジェクトと指定されたオブジェクトを比較します。 |
| [TimeSpan](./) [Duration](./duration/)() const | 現在のオブジェクトの絶対値を持つ [TimeSpan](./) オブジェクトの新しいインスタンスを返します。 |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔と等しいかどうかを判定します。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔と等しいかどうかを判定します。 |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | 指定されたオブジェクトが同じ時間間隔を表す場合は true を返し、そうでない場合は false を返します。 |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | 指定された間隔を表す新しい [TimeSpan](./) オブジェクトを返します。 |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | 指定された間隔を表す新しい [TimeSpan](./) オブジェクトを返します。 |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | 指定された間隔を表す新しい [TimeSpan](./) オブジェクトを返します。 |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | 指定された間隔を表す新しい [TimeSpan](./) オブジェクトを返します。 |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | 指定された間隔を表す新しい [TimeSpan](./) オブジェクトを返します。 |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | 指定された間隔を表す新しい [TimeSpan](./) オブジェクトを返します。 |
| constexpr int [get_Days](./get_days/)() const | 現在の [TimeSpan](./) オブジェクトが表す時間間隔の「日」成分を返します。 |
| constexpr int [get_Hours](./get_hours/)() const | 現在の [TimeSpan](./) オブジェクトが表す時間間隔の「時間」成分を返します。 |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | 現在の [TimeSpan](./) オブジェクトが表す時間間隔のミリ秒成分を返します。 |
| constexpr int [get_Minutes](./get_minutes/)() const | 現在の [TimeSpan](./) オブジェクトが表す時間間隔の分成分を返します。 |
| constexpr int [get_Seconds](./get_seconds/)() const | 現在の [TimeSpan](./) オブジェクトが表す時間間隔の秒成分を返します。 |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | 現在の [TimeSpan](./) オブジェクトが表す時間間隔を構成する 100 ナノ秒間隔の数を返します。 |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | 現在の [TimeSpan](./) オブジェクトの値を、整数部と小数部の両方で日単位で表したものを返します。 |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | 現在の [TimeSpan](./) オブジェクトの値を、整数部と小数部の両方で時間単位で表したものを返します。 |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | 現在の [TimeSpan](./) オブジェクトの値を、整数部と小数部の両方でミリ秒単位で表したものを返します。 |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | 現在の [TimeSpan](./) オブジェクトの値を、整数部と小数部の両方で分単位で表したものを返します。 |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | 現在の [TimeSpan](./) オブジェクトの値を、整数部と小数部の両方で秒単位で表したものを返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | 現在の [TimeSpan](./) オブジェクトが表す値の否定を表す [TimeSpan](./) オブジェクトの新しいインスタンスを返します。 |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔と等しくないかどうかを判定します。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | 現在のオブジェクトと指定されたオブジェクトが表す時間間隔の合計を表す、[TimeSpan](./) クラスの新しいインスタンスを返します。 |
| [TimeSpan](./) [operator+](./operator_plus/)() const | 自身を返します。 |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | 現在のオブジェクトと指定されたオブジェクトが表す時間間隔の合計を、現在のオブジェクトに代入します。 |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔から、指定されたオブジェクトが表す時間間隔を減算した結果の時間間隔を表す [TimeSpan](./) クラスの新しいインスタンスを返します。 |
| [TimeSpan](./) [operator-](./operator_minus/)() const | 現在の [TimeSpan](./) オブジェクトが表す値の否定を表す [TimeSpan](./) オブジェクトの新しいインスタンスを返します。 |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | 現在のオブジェクトと指定されたオブジェクトが表す時間間隔の合計を、現在のオブジェクトに代入します。 |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔より短いかどうかを判定します。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔以下（短いまたは等しい）かどうかを判定します。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | 指定された [TimeSpan](./) オブジェクトが表す時間間隔を、現在の [TimeSpan](./) オブジェクトに設定します。 |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔と等しいかどうかを判定します。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔より長いかどうかを判定します。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔以上（長いまたは等しい）かどうかを判定します。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | 文字列を同等の [TimeSpan](./) オブジェクトに変換します。 |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたフォーマットプロバイダーを使用して、文字列を同等の [TimeSpan](./) オブジェクトに変換します。 |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | 指定されたフォーマット、フォーマットプロバイダー、スタイルを使用して、文字列を同等の [TimeSpan](./) オブジェクトに変換します。 |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | 指定されたフォーマット、フォーマットプロバイダー、スタイルを使用して、文字列を同等の [TimeSpan](./) オブジェクトに変換します。 |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | 現在のオブジェクトが表す時間間隔から、指定されたオブジェクトが表す時間間隔を減算した結果の時間間隔を表す [TimeSpan](./) クラスの新しいインスタンスを返します。 |
| constexpr [TimeSpan](./timespan/)() | ゼロの時間間隔を表す [TimeSpan](./) オブジェクトを構築します。 |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | 指定された時間間隔を表す [TimeSpan](./) クラスのインスタンスを構築します。 |
| [TimeSpan](./timespan/)(int, int, int) | 指定された時間、分、秒の合計に等しい時間間隔を表す [TimeSpan](./) クラスのインスタンスを構築します。 |
| [TimeSpan](./timespan/)(int, int, int, int, int) | 指定された時間、分、秒、ミリ秒の合計に等しい時間間隔を表す [TimeSpan](./) クラスのインスタンスを構築します。 |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | 指定された [TimeSpan](./) オブジェクトが表す時間間隔と等しい時間間隔を表す [TimeSpan](./) オブジェクトを構築します。 |
| [String](../string/) [ToString](./tostring/)() const | 現在のオブジェクトが表す時間間隔の文字列表現を返します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 指定されたフォーマットを使用して、現在のオブジェクトの値を同等の文字列表現に変換します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 指定されたフォーマットとフォーマットプロバイダーを使用して、現在のオブジェクトの値を同等の文字列に変換します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | 文字列を同等の [TimeSpan](./) オブジェクトに変換し、変換結果を返します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 指定されたフォーマットプロバイダーを使用して、文字列を同等の [TimeSpan](./) オブジェクトに変換し、変換結果を返します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 指定されたフォーマット、フォーマットプロバイダーを使用して、文字列を同等の [TimeSpan](./) オブジェクトに変換し、変換結果を返します。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | 指定されたフォーマット、フォーマットプロバイダー、スタイルを使用して、文字列を同等の [TimeSpan](./) オブジェクトに変換し、変換結果を返します。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | 指定されたフォーマット、フォーマットプロバイダー、スタイルを使用して、文字列を同等の [TimeSpan](./) オブジェクトに変換し、変換結果を返します。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 指定されたフォーマットとフォーマットプロバイダーを使用して、文字列を同等の [TimeSpan](./) オブジェクトに変換し、変換結果を返します。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TimeSpan](./) 構造体を表す [TypeInfo](../typeinfo/) オブジェクトを返します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [MaxValue](./maxvalue/) | 最長の間隔を表す [TimeSpan](./) オブジェクトです。 |
| static [MinValue](./minvalue/) | /// 最短の間隔を表す [TimeSpan](./) オブジェクトです。 |
| static constexpr [TicksPerDay](./ticksperday/) | 1 日（24 時間）に含まれる 100 ナノ秒間隔の数です。 |
| static constexpr [TicksPerHour](./ticksperhour/) | 1 時間に含まれる 100 ナノ秒間隔の数です。 |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | 1 ミリ秒に含まれる 100 ナノ秒間隔の数です。 |
| static constexpr [TicksPerMinute](./ticksperminute/) | 1 分に含まれる 100 ナノ秒間隔の数です。 |
| static constexpr [TicksPerSecond](./tickspersecond/) | 1 秒に含まれる 100 ナノ秒間隔の数です。 |
| static [Zero](./zero/) | ゼロ間隔を表す [TimeSpan](./) オブジェクトです。 |

## 備考



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
このコード例は以下の出力を生成します:
ティックの数: 260928000000000
ミリ秒の数: 0
ミリ秒の合計: 2.60928e+10
分の数: 0
分の合計: 434880
時間の数: 0
時間の合計: 0
日の数: 302
日の合計: 302
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)