---
title: TimeSpan
second_title: Aspose.Slides for C++ API 参考
description: "表示时间间隔。此类型应在栈上分配并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 1288
url: /zh/system/timespan/
---
## TimeSpan 类

表示时间间隔。此类型应在栈上分配并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
class TimeSpan
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | 返回一个新的 [TimeSpan](./) 类实例，表示当前对象和指定对象所表示的时间间隔之和。 |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | 比较两个 [TimeSpan](./) 对象。 |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | 比较当前对象和指定对象。 |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 比较当前对象和指定对象。 |
| [TimeSpan](./) [Duration](./duration/)() const | 返回一个新的 [TimeSpan](./) 对象实例，其值为当前对象的绝对值。 |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | 确定当前对象表示的时间间隔是否等于指定对象表示的时间间隔。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 确定当前对象表示的时间间隔是否等于指定对象表示的时间间隔。 |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | 如果指定对象表示相同的时间间隔则返回 true，否则返回 false。 |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | 返回一个新的 [TimeSpan](./) 对象，表示指定的间隔。 |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | 返回一个新的 [TimeSpan](./) 对象，表示指定的间隔。 |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | 返回一个新的 [TimeSpan](./) 对象，表示指定的间隔。 |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | 返回一个新的 [TimeSpan](./) 对象，表示指定的间隔。 |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | 返回一个新的 [TimeSpan](./) 对象，表示指定的间隔。 |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | 返回一个新的 [TimeSpan](./) 对象，表示指定的间隔。 |
| constexpr int [get_Days](./get_days/)() const | 返回当前 [TimeSpan](./) 对象表示的时间间隔的天数部分。 |
| constexpr int [get_Hours](./get_hours/)() const | 返回当前 [TimeSpan](./) 对象表示的时间间隔的小时部分。 |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | 返回当前 [TimeSpan](./) 对象表示的时间间隔的毫秒部分。 |
| constexpr int [get_Minutes](./get_minutes/)() const | 返回当前 [TimeSpan](./) 对象表示的时间间隔的分钟部分。 |
| constexpr int [get_Seconds](./get_seconds/)() const | 返回当前 [TimeSpan](./) 对象表示的时间间隔的秒数部分。 |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | 返回当前 [TimeSpan](./) 对象表示的时间间隔所包含的 100 纳秒间隔数量。 |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | 返回当前 [TimeSpan](./) 对象的值，以完整天数和小数天数表示。 |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | 返回当前 [TimeSpan](./) 对象的值，以完整小时数和小数小时数表示。 |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | 返回当前 [TimeSpan](./) 对象的值，以完整毫秒数和小数毫秒数表示。 |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | 返回当前 [TimeSpan](./) 对象的值，以完整分钟数和小数分钟数表示。 |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | 返回当前 [TimeSpan](./) 对象的值，以完整秒数和小数秒数表示。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | 返回一个新的 [TimeSpan](./) 对象实例，表示当前 [TimeSpan](./) 对象的取反值。 |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | 确定当前对象表示的时间间隔是否不等于指定对象表示的时间间隔。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | 返回一个新的 [TimeSpan](./) 类实例，表示当前对象和指定对象所表示的时间间隔之和。 |
| [TimeSpan](./) [operator+](./operator_plus/)() const | 返回自身。 |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | 将当前对象赋值为当前对象与指定对象所表示的时间间隔之和。 |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | 返回一个新的 [TimeSpan](./) 类实例，表示从指定对象的时间间隔中减去当前对象的时间间隔的结果。 |
| [TimeSpan](./) [operator-](./operator_minus/)() const | 返回一个新的 [TimeSpan](./) 对象实例，表示当前 [TimeSpan](./) 对象的取反值。 |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | 将当前对象赋值为当前对象的时间间隔减去指定对象的时间间隔的结果。 |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | 确定当前对象表示的时间间隔是否短于指定对象表示的时间间隔。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | 确定当前对象表示的时间间隔是否短于或等于指定对象表示的时间间隔。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | 将指定 [TimeSpan](./) 对象表示的时间间隔设置为当前 [TimeSpan](./) 对象。 |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | 确定当前对象表示的时间间隔是否等于指定对象表示的时间间隔。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | 确定当前对象表示的时间间隔是否长于指定对象表示的时间间隔。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | 确定当前对象表示的时间间隔是否长于或等于指定对象表示的时间间隔。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | 将字符串转换为等价的 [TimeSpan](./) 对象。 |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的格式提供程序将字符串转换为等价的 [TimeSpan](./) 对象。 |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | 使用指定的格式、格式提供程序和样式将字符串转换为等价的 [TimeSpan](./) 对象。 |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | 使用指定的格式、格式提供程序和样式将字符串转换为等价的 [TimeSpan](./) 对象。 |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | 返回一个新的 [TimeSpan](./) 类实例，表示从指定对象的时间间隔中减去当前对象的时间间隔的结果。 |
| constexpr [TimeSpan](./timespan/)() | 构造一个表示零时间间隔的 [TimeSpan](./) 对象。 |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | 构造一个表示指定时间间隔的 [TimeSpan](./) 类实例。 |
|  [TimeSpan](./timespan/)(int, int, int) | 构造一个表示小时、分钟和秒数之和的 [TimeSpan](./) 类实例。 |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | 构造一个表示小时、分钟、秒和毫秒之和的 [TimeSpan](./) 类实例。 |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | 构造一个表示与指定 [TimeSpan](./) 对象相同时间间隔的 [TimeSpan](./) 对象。 |
| [String](../string/) [ToString](./tostring/)() const | 返回当前对象所表示的时间间隔的字符串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 使用指定的格式将当前对象的值转换为等价的字符串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的格式和格式提供程序将当前对象的值转换为等价的字符串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | 将字符串转换为等价的 [TimeSpan](./) 对象并返回转换结果。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 使用指定的格式提供程序将字符串转换为等价的 [TimeSpan](./) 对象并返回转换结果。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 使用指定的格式和格式提供程序将字符串转换为等价的 [TimeSpan](./) 对象并返回转换结果。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | 使用指定的格式、格式提供程序和样式将字符串转换为等价的 [TimeSpan](./) 对象并返回转换结果。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | 使用指定的格式、格式提供程序和样式将字符串转换为等价的 [TimeSpan](./) 对象并返回转换结果。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 使用指定的格式和格式提供程序将字符串转换为等价的 [TimeSpan](./) 对象并返回转换结果。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 返回一个表示 [TimeSpan](./) 结构的 [TypeInfo](../typeinfo/) 对象。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [MaxValue](./maxvalue/) | 表示最长可能间隔的 [TimeSpan](./) 对象。 |
| static [MinValue](./minvalue/) | /// 表示最短可能间隔的 [TimeSpan](./) 对象。 |
| static constexpr [TicksPerDay](./ticksperday/) | 一天（24 小时）内的 100 纳秒间隔数。 |
| static constexpr [TicksPerHour](./ticksperhour/) | 一小时内的 100 纳秒间隔数。 |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | 一毫秒内的 100 纳秒间隔数。 |
| static constexpr [TicksPerMinute](./ticksperminute/) | 一分钟内的 100 纳秒间隔数。 |
| static constexpr [TicksPerSecond](./tickspersecond/) | 一秒钟内的 100 纳秒间隔数。 |
| static [Zero](./zero/) | 表示零间隔的 [TimeSpan](./) 对象。 |

## 备注

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
此代码示例产生以下输出:
滴答数: 260928000000000
毫秒数: 0
总毫秒数: 2.60928e+10
分钟数: 0
总分钟数: 434880
小时数: 0
总小时数: 0
天数: 302
总天数: 302
*/
```

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)