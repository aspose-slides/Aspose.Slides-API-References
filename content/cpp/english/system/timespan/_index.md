---
title: TimeSpan
second_title: Aspose.Slides for C++ API Reference
description: "Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 1275
url: /system/timespan/
---
## TimeSpan class


Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class TimeSpan
```

## Methods

| Method | Description |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Returns a new instance of [TimeSpan](./) class that represents a time interval which is the sum of the time intervals represented by the current and the specified objects. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Compares two [TimeSpan](./) objects. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Compares current and the specified objects. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Compares current and the specified objects. |
| [TimeSpan](./) [Duration](./duration/)() const | Returns a new instance of [TimeSpan](./) object whose value is the absolute value of the current object. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Determines if the time interval represented by the current object is equal to the time interval represented by the specified object. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determines if the time interval represented by the current object is equal to the time interval represented by the specified object. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Returns true if the specified objects represent the same time interval, otherwise - false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| constexpr int [get_Days](./get_days/)() const | Returns the days component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr int [get_Hours](./get_hours/)() const | Returns the hours component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Returns the milliseconds component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr int [get_Minutes](./get_minutes/)() const | Returns the minutes component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr int [get_Seconds](./get_seconds/)() const | Returns the seconds component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Returns the number of 100-nanoseconds intervals that constitute the time interval represented by the current [TimeSpan](./) object. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional days. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional hours. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional milliseconds. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional minutes. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional seconds. |
| int [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Returns a new instance of [TimeSpan](./) object that represents negated value represented by the current [TimeSpan](./) object. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Determines if the time interval represented by the current object is not equal to the time interval represented by the specified object. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Returns a new instance of [TimeSpan](./) class that represents a time interval which is the sum of the time intervals represented by the current and the specified objects. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Returns self. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Assigns to the current object the time interval which is the sum of the time interval represented by the current and the specified objects. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Returns a new instance of [TimeSpan](./) class that represents a time interval which is the result of subtraction of the time interval represented by the specified object from the time interval represented by the current object. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Returns a new instance of [TimeSpan](./) object that represents negated value represented by the current [TimeSpan](./) object. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Assigns to the current object the time interval which is the result of subtraction of the time interval represented by the specified object from the time interval represented by the current object. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Determines if the time interval represented by the current object is shorter than the time interval represented by the specified object. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Determines if the time interval represented by the current object is shorter than or equal to the time interval represented by the specified object. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Sets the time interval represented by the specified [TimeSpan](./) object to the current [TimeSpan](./) object. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Determines if the time interval represented by the current object is equal to the time interval represented by the specified object. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Determines if the time interval represented by the current object is longer than the time interval represented by the specified object. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Determines if the time interval represented by the current object is longer than or equal to the time interval represented by the specified object. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Converts string to equivalent [TimeSpan](./) object. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts string to equivalent [TimeSpan](./) object using the specified format provider. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Converts string to equivalent [TimeSpan](./) object using the specified formats, format provider and styles. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Converts string to equivalent [TimeSpan](./) object using the specified format, format provider and styles. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Returns a new instance of [TimeSpan](./) class that represents a time interval which is the result of subtraction of the time interval represented by the specified object from the time interval represented by the current object. |
| constexpr [TimeSpan](./timespan/)() | Constructs a [TimeSpan](./) object that represents a zero time interval. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Constructs an instance of [TimeSpan](./) class that represents the specified time interval. |
|  [TimeSpan](./timespan/)(int, int, int) | Constructs an instance of [TimeSpan](./) class that represents the time interval which is equal to the sum of the specified number of hours, minutes and seconds. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Constructs an instance of [TimeSpan](./) class that represents the time interval which is equal to the sum of the specified number of hours, minutes, seconds and milliseconds. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Constructs a [TimeSpan](./) object that represents the time interval equal to the time interval represented by the specified [TimeSpan](./) object. |
| [String](../string/) [ToString](./tostring/)() const | Returns the string representation of the time interval represented by the current object. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converts the value of the current object to equivalent string representation, using the specified format. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converts the value of the current object to equivalent string representation, using the specified format and format provider. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Converts string to equivalent [TimeSpan](./) object and returns result of conversion. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converts string to equivalent [TimeSpan](./) object using the specified format provider and returns result of conversion. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converts string to equivalent [TimeSpan](./) object using the specified formats and format provider, and returns result of conversion. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Converts string to equivalent [TimeSpan](./) object using the specified format, format provider and styles, and returns result of conversion. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Converts string to equivalent [TimeSpan](./) object using the specified formats, format provider and styles, and returns result of conversion. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converts string to equivalent [TimeSpan](./) object using the specified format and format provider, and returns result of conversion. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returns a [TypeInfo](../typeinfo/) object that represent [TimeSpan](./) structure. |
## Fields

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | The [TimeSpan](./) object that represents the longest possible interval. |
| static [MinValue](./minvalue/) | /// The [TimeSpan](./) object that represents the shortest possible interval. |
| static constexpr [TicksPerDay](./ticksperday/) | The number of 100-nanoseconds intervals in a day (24-hour interval). |
| static constexpr [TicksPerHour](./ticksperhour/) | The number of 100-nanoseconds intervals in a hour. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | The number of 100-nanoseconds intervals in a millisecond. |
| static constexpr [TicksPerMinute](./ticksperminute/) | The number of 100-nanoseconds intervals in a minute. |
| static constexpr [TicksPerSecond](./tickspersecond/) | The number of 100-nanoseconds intervals in a second. |
| static [Zero](./zero/) | The [TimeSpan](./) object that represents zero-interval. |
## Remarks



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
This code example produces the following output:
Number of ticks: 260928000000000
Number of milliseconds: 0
Total number of milliseconds: 2.60928e+10
Number of minutes: 0
Total number of minutes: 434880
Number of hours: 0
Total number of hours: 0
Number of days: 302
Total number of days: 302
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)