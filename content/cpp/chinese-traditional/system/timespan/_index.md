---
title: TimeSpan
second_title: Aspose.Slides for C++ API 參考
description: "表示時間間隔。此類型應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 1314
url: /zh-hant/system/timespan/
---
## TimeSpan 類別

表示一個時間間隔。此型別應在堆疊上配置，並以值或參考方式傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此型別的物件。

```cpp
class TimeSpan
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | 傳回一個新的 [TimeSpan](./) 類別實例，該實例表示由目前物件和指定物件所代表的時間間隔之總和。 |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | 比較兩個 [TimeSpan](./) 物件。 |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | 比較目前與指定的物件。 |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 比較目前與指定的物件。 |
| [TimeSpan](./) [Duration](./duration/)() const | 傳回一個新的 [TimeSpan](./) 物件，其值為目前物件的絕對值。 |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | 判斷目前物件所代表的時間間隔是否等於指定物件所代表的時間間隔。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 判斷目前物件所代表的時間間隔是否等於指定物件所代表的時間間隔。 |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | 如果指定的物件表示相同的時間間隔，則傳回 true；否則傳回 false。 |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | 傳回一個新的 [TimeSpan](./) 物件，該物件代表指定的間隔。 |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | 傳回一個新的 [TimeSpan](./) 物件，該物件代表指定的間隔。 |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | 傳回一個新的 [TimeSpan](./) 物件，該物件代表指定的間隔。 |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | 傳回一個新的 [TimeSpan](./) 物件，該物件代表指定的間隔。 |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | 傳回一個新的 [TimeSpan](./) 物件，該物件代表指定的間隔。 |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | 傳回一個新的 [TimeSpan](./) 物件，該物件代表指定的間隔。 |
| constexpr int [get_Days](./get_days/)() const | 傳回目前 [TimeSpan](./) 物件所代表的時間間隔之天數部分。 |
| constexpr int [get_Hours](./get_hours/)() const | 傳回目前 [TimeSpan](./) 物件所代表的時間間隔之小時部分。 |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | 傳回目前 [TimeSpan](./) 物件所代表的時間間隔之毫秒部分。 |
| constexpr int [get_Minutes](./get_minutes/)() const | 傳回目前 [TimeSpan](./) 物件所代表的時間間隔之分鐘部分。 |
| constexpr int [get_Seconds](./get_seconds/)() const | 傳回目前 [TimeSpan](./) 物件所代表的時間間隔之秒數部分。 |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | 傳回目前 [TimeSpan](./) 物件所代表的時間間隔中 100 奈秒間隔的數量。 |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | 傳回目前 [TimeSpan](./) 物件以整天與小數天表示的值。 |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | 傳回目前 [TimeSpan](./) 物件以整小時與小數小時表示的值。 |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | 傳回目前 [TimeSpan](./) 物件以整毫秒與小數毫秒表示的值。 |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | 傳回目前 [TimeSpan](./) 物件以整分鐘與小數分鐘表示的值。 |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | 傳回目前 [TimeSpan](./) 物件以整秒與小數秒表示的值。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | 傳回一個新的 [TimeSpan](./) 物件，其值為目前 [TimeSpan](./) 物件所代表的相反值。 |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | 判斷目前物件所代表的時間間隔是否不等於指定物件所代表的時間間隔。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | 傳回一個新的 [TimeSpan](./) 類別實例，該實例表示由目前物件和指定物件所代表的時間間隔之總和。 |
| [TimeSpan](./) [operator+](./operator_plus/)() const | 傳回自身。 |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | 將目前物件設定為目前與指定物件之時間間隔的總和。 |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | 傳回一個新的 [TimeSpan](./) 類別實例，該實例表示從目前物件所代表的時間間隔減去指定物件所代表的時間間隔之結果。 |
| [TimeSpan](./) [operator-](./operator_minus/)() const | 傳回一個新的 [TimeSpan](./) 物件，其值為目前 [TimeSpan](./) 物件所代表的相反值。 |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | 將目前物件設定為目前物件所代表的時間間隔減去指定物件所代表的時間間隔之結果。 |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | 判斷目前物件所代表的時間間隔是否較短於指定物件所代表的時間間隔。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | 判斷目前物件所代表的時間間隔是否較短或等於指定物件所代表的時間間隔。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | 將指定的 [TimeSpan](./) 物件所代表的時間間隔設定為目前 [TimeSpan](./) 物件。 |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | 判斷目前物件所代表的時間間隔是否等於指定物件所代表的時間間隔。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | 判斷目前物件所代表的時間間隔是否較長於指定物件所代表的時間間隔。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | 判斷目前物件所代表的時間間隔是否較長或等於指定物件所代表的時間間隔。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | 將字串轉換為等效的 [TimeSpan](./) 物件。 |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的格式提供者，將字串轉換為等效的 [TimeSpan](./) 物件。 |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | 使用指定的格式、格式提供者與樣式，將字串轉換為等效的 [TimeSpan](./) 物件。 |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | 使用指定的格式、格式提供者與樣式，將字串轉換為等效的 [TimeSpan](./) 物件。 |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | 傳回一個新的 [TimeSpan](./) 類別實例，該實例表示從目前物件所代表的時間間隔減去指定物件所代表的時間間隔之結果。 |
| constexpr [TimeSpan](./timespan/)() | 建立一個代表零時間間隔的 [TimeSpan](./) 物件。 |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | 建立一個代表指定時間間隔的 [TimeSpan](./) 類別實例。 |
|  [TimeSpan](./timespan/)(int, int, int) | 建立一個 [TimeSpan](./) 類別實例，其時間間隔等於指定的時、分、秒之總和。 |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | 建立一個 [TimeSpan](./) 類別實例，其時間間隔等於指定的時、分、秒與毫秒之總和。 |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | 建立一個 [TimeSpan](./) 物件，其時間間隔等於指定 [TimeSpan](./) 物件所代表的時間間隔。 |
| [String](../string/) [ToString](./tostring/)() const | 傳回目前物件所代表的時間間隔的字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 使用指定的格式，將目前物件的值轉換為等效的字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的格式與格式提供者，將目前物件的值轉換為等效的字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | 將字串轉換為等效的 [TimeSpan](./) 物件，並傳回轉換結果。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 使用指定的格式提供者，將字串轉換為等效的 [TimeSpan](./) 物件，並傳回轉換結果。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 使用指定的格式與格式提供者，將字串轉換為等效的 [TimeSpan](./) 物件，並傳回轉換結果。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | 使用指定的格式、格式提供者與樣式，將字串轉換為等效的 [TimeSpan](./) 物件，並傳回轉換結果。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | 使用指定的格式、格式提供者與樣式，將字串轉換為等效的 [TimeSpan](./) 物件，並傳回轉換結果。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 使用指定的格式與格式提供者，將字串轉換為等效的 [TimeSpan](./) 物件，並傳回轉換結果。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 傳回一個代表 [TimeSpan](./) 結構的 [TypeInfo](../typeinfo/) 物件。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [MaxValue](./maxvalue/) | [TimeSpan](./) 物件代表可能的最長間隔。 |
| static [MinValue](./minvalue/) | /// [TimeSpan](./) 物件代表可能的最短間隔。 |
| static constexpr [TicksPerDay](./ticksperday/) | 一天（24 小時）內的 100 奈秒間隔數。 |
| static constexpr [TicksPerHour](./ticksperhour/) | 一小時內的 100 奈秒間隔數。 |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | 一毫秒內的 100 奈秒間隔數。 |
| static constexpr [TicksPerMinute](./ticksperminute/) | 一分鐘內的 100 奈秒間隔數。 |
| static constexpr [TicksPerSecond](./tickspersecond/) | 一秒鐘內的 100 奈秒間隔數。 |
| static [Zero](./zero/) | [TimeSpan](./) 物件代表零間隔。 |

## 備註

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
此程式碼範例會產生以下輸出：
滴答數: 260928000000000
毫秒數: 0
總毫秒數: 2.60928e+10
分鐘數: 0
總分鐘數: 434880
小時數: 0
總小時數: 0
天數: 302
總天數: 302
*/
```

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)