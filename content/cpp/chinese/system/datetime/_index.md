---
title: DateTime
second_title: Aspose.Slides for C++ API 参考
description: "表示时间连续体上的特定日期和时间值。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 222
url: /zh/system/datetime/
---
## DateTime 类

表示时间连续体上的特定日期和时间值。此类型应在栈上分配并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
class DateTime
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | 返回一个新的 [DateTime](./) 类实例，表示将指定的时间跨度加到当前对象所表示的日期时间值后得到的日期时间值。 |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的值与指定天数相加后的日期时间值。 |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的值与指定小时数相加后的日期时间值。 |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的值与指定毫秒数相加后的日期时间值。 |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的值与指定分钟数相加后的日期时间值。 |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的值与指定月数相加后的日期时间值。 |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的值与指定秒数相加后的日期时间值。 |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的值与指定的 100 纳秒间隔数相加后的日期时间值。 |
| [DateTime](./) [AddYears](./addyears/)(int) const | 返回一个新的 [DateTime](./) 类实例，表示在当前对象的年份上增加指定数量后的日期时间值。 |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | 比较由指定的 [DateTime](./) 类实例表示的两个值，并返回指示它们在时间线上相对位置的值。 |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | 比较当前对象和指定的 [DateTime](./) 类实例表示的两个日期时间值，并返回指示它们在时间线上相对位置的值。 |
| constexpr [DateTime](./datetime/)() | 构造一个表示等于 MinValue 的最小可能日期时间值的实例。 |
|  [DateTime](./datetime/)(int, int, int) | 构造一个表示特定年份、月份和日期的日期时间值的实例。 |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | 构造一个在指定日历中表示特定年份、月份和日期的日期时间值的实例。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | 构造一个表示特定年份、月份、日期、小时、分钟和秒的日期时间值的实例。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | 构造一个表示特定年份、月份、日期、小时、分钟和秒的日期时间值的实例。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | 构造一个在指定日历中表示特定年份、月份、日期、小时、分钟和秒的日期时间值的实例。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | 构造一个表示特定年份、月份、日期、小时、分钟、秒和毫秒的日期时间值的实例。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | 构造一个在指定日历中表示特定年份、月份、日期、小时、分钟、秒和毫秒的日期时间值的实例。 |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | 构造一个根据给定的滴答数表示的日期时间值的实例。 |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | 构造一个根据给定的滴答数表示的日期时间值的实例。供内部使用。 |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | 拷贝构造一个实例。 |
| static int [DaysInMonth](./daysinmonth/)(int, int) | 返回指定年份中指定月份的天数。 |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | 判断指定的 [DateTime](./) 类实例是否表示相同的日期时间值。 |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | 判断指定的 [DateTime](./) 类实例是否与当前对象表示相同的日期时间值。 |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | 从指定的无符号 64 位整数反序列化日期时间值，并将新的 [DateTime](./) 类实例设为该值。 |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | 将指定的文件时间转换为表示相同本地时间的 [DateTime](./) 类实例。 |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | 将指定的文件时间转换为表示相同 UTC 时间的 [DateTime](./) 类实例。 |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | 返回一个表示等价于指定 OLE Automation Date 的 [DateTime](./) 类实例。 |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | 将指定的 Unix 时间值转换为 [DateTime](./) 类实例。供内部使用。 |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | 返回一个新的 [DateTime](./) 类实例，表示当前对象所表示的日期时间的日期部分，时间部分的各组件均设为 0。 |
| int [get_Day](./get_day/)() const | 返回当前对象所表示的月份中该日的序号。 |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | 返回一个表示当前对象所表示的星期几的值。 |
| int [get_DayOfYear](./get_dayofyear/)() const | 返回当前对象所表示的年份中该日的序号。 |
| constexpr int [get_Hour](./get_hour/)() const | 返回当前对象所表示的日期时间值的小时组件。 |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | 返回一个值，表示当前对象所表示的日期时间是本地时间、UTC 时间还是两者皆非。 |
| constexpr int [get_Millisecond](./get_millisecond/)() const | 返回当前对象所表示的日期时间值的毫秒组件。 |
| constexpr int [get_Minute](./get_minute/)() const | 返回当前对象所表示的日期时间值的分钟组件。 |
| int [get_Month](./get_month/)() const | 返回当前对象所表示的年份中该月的序号。 |
| static [DateTime](./) [get_Now](./get_now/)() | 返回一个表示当前时间（本地时间）的 [DateTime](./) 类实例。 |
| constexpr int [get_Second](./get_second/)() const | 返回当前对象所表示的日期时间值的秒组件。 |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | 返回自公历 0001-01-01 00:00:00 UTC 起至当前对象所表示的日期时间之间经过的 100 纳秒间隔数。 |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | 返回一个值，表示从当前对象表示的当天开始至当前对象所表示的日期时间值的时间间隔。 |
| static [DateTime](./) [get_Today](./get_today/)() | 返回一个 [DateTime](./) 类实例，表示当前对象的日期部分，时间部分的各组件均设为 0。 |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | 返回一个表示当前时间（UTC）的 [DateTime](./) 类实例。 |
| int [get_Year](./get_year/)() const | 返回当前对象所表示的年份。 |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | 获取日期部分。供内部使用。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | 返回一个字符串数组，每个元素是使用标准日期时间格式说明符之一格式化当前对象后的字符串表示。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | 返回一个字符串数组，每个元素是使用指定的标准日期时间格式说明符格式化当前对象后的字符串表示。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 返回一个字符串数组，每个元素是使用标准日期时间格式说明符之一以及指定的格式提供程序格式化当前对象后的字符串表示。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 返回一个字符串数组，每个元素是使用指定的标准日期时间格式说明符和格式提供程序格式化当前对象后的字符串表示。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | 判断当前对象所表示的日期时间值是否落在当前时区的夏令时范围内。 |
| static **bool** [IsLeapYear](./isleapyear/)(int) | 判断指定的年份是否为闰年。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | 判断当前对象和指定的 [DateTime](./) 对象是否表示不同的日期时间值。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的值与指定时间跨度相加后的日期时间值。 |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | 将当前对象设为当前对象的值与指定时间跨度相加后的日期时间值。 |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | 返回一个新的 [DateTime](./) 类实例，表示从当前对象的值中减去指定时间跨度后的日期时间值。 |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | 返回一个 [TimeSpan](../timespan/) 类实例，表示当前对象和指定对象的日期时间值之间的时间间隔。 |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | 将当前对象设为从当前对象的日期时间值中减去指定时间跨度后的结果。 |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | 判断当前对象的日期时间值是否早于指定的 [DateTime](./) 对象的值。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | 判断当前对象的日期时间值是否早于或等于指定的 [DateTime](./) 对象的值。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | 将指定的 [DateTime](./) 实例的值赋给当前对象。 |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | 判断当前对象和指定的 [DateTime](./) 对象是否表示相同的日期时间值。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | 判断当前对象的日期时间值是否晚于指定的 [DateTime](./) 对象的值。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | 判断当前对象的日期时间值是否晚于或等于指定的 [DateTime](./) 对象的值。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | 将指定的日期时间值字符串表示转换为等价的 [DateTime](./) 对象。 |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 将指定的日期时间值字符串表示转换为等价的 [DateTime](./) 对象，使用特定文化的格式信息。 |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 将指定的日期时间值字符串表示转换为等价的 [DateTime](./) 对象，使用指定的格式和特定文化的格式信息。字符串的格式必须完全匹配指定的格式。转换失败时抛出异常。 |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 将指定的日期时间值字符串表示转换为等价的 [DateTime](./) 对象，使用指定的格式、特定文化的格式信息和样式。字符串的格式必须完全匹配一个或多个指定的格式。转换失败时抛出异常。 |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | 构造一个新的 [DateTime](./) 对象，表示与指定 [DateTime](./) 对象相同的滴答数，并根据 **kind** 参数表示本地时间、UTC 时间或两者皆非。 |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | 返回一个新的 [DateTime](./) 类实例，表示从当前对象的值中减去指定时间跨度后的日期时间值。 |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | 返回一个 [TimeSpan](../timespan/) 类实例，表示当前对象和指定对象的日期时间值之间的时间间隔。 |
| **int64_t** [ToBinary](./tobinary/)() const | 序列化当前对象。 |
| **int64_t** [ToFileTime](./tofiletime/)() const | 返回一个表示当前对象所表示的日期时间值的文件时间。 |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | 将当前对象所表示的日期时间值转换为 UTC 文件时间。 |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | 返回一个新的 [DateTime](./) 类实例，表示当前对象所表示的日期时间值的本地时间。 |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | 返回一个包含当前对象的长日期字符串表示的字符串。 |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | 返回一个包含当前对象的长时间字符串表示的字符串。 |
| **double** [ToOADate](./tooadate/)() const | 返回当前对象所表示的日期时间值的 OLE Automation Date。 |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | 返回一个包含当前对象的短日期字符串表示的字符串。 |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | 返回一个包含当前对象的短时间字符串表示的字符串。 |
| [String](../string/) [ToString](./tostring/)() const | 返回当前对象的日期时间值的字符串表示，使用当前文化定义的格式约定。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 返回当前对象的日期时间值的字符串表示，使用指定的格式和当前文化定义的格式约定。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 返回当前对象的日期时间值的字符串表示，使用指定的格式信息。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 返回当前对象的日期时间值的字符串表示，使用指定的格式信息。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | 返回一个新的 [DateTime](./) 类实例，表示当前对象的日期时间值的 UTC 表示。 |
| time_t [ToUnixTime](./tounixtime/)() const | 返回一个表示当前对象的日期时间值的 Unix 时间。供内部使用。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | 将指定的日期时间值字符串表示转换为等价的 [DateTime](./) 对象。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 将指定的日期时间值字符串表示转换为等价的 [DateTime](./) 对象，使用指定的特定文化格式信息和样式。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 将指定的日期时间值字符串表示转换为等价的 [DateTime](./) 对象，使用指定的格式、特定文化的格式信息和样式。字符串的格式必须完全匹配指定的格式。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 将指定的日期时间值字符串表示转换为等价的 [DateTime](./) 对象，使用指定的格式、特定文化的格式信息和样式。字符串的格式必须完全匹配一个或多个指定的格式。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 返回一个 [TypeInfo](../typeinfo/) 对象，包含有关此类的信息。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | 最小可能和最大可能 [DateTime](./) 值之间的时间间隔中 100 纳秒的数量。 |
| static [MaxValue](./maxvalue/) | 一个表示最大可能日期时间值的 [DateTime](./) 类实例。 |
| static constexpr [MinTicks](./minticks/) | [DateTime](./) 类实例可以表示的最小滴答数。 |
| static [MinValue](./minvalue/) | 一个表示最小可能日期时间值的 [DateTime](./) 类实例。 |
| static constexpr [TicksPerDay](./ticksperday/) | 一天中的滴答数。 |
| static constexpr [TicksPerHour](./ticksperhour/) | 一小时中的滴答数。 |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | 一微秒中的滴答数。 |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | 一毫秒中的滴答数。 |
| static constexpr [TicksPerMinute](./ticksperminute/) | 一分钟中的滴答数。 |
| static constexpr [TicksPerSecond](./tickspersecond/) | 一秒钟中的滴答数。 |
| static [UnixEpoch](./unixepoch/) | 一个表示 Unix 纪元开始（1970-01-01 00:00:00）的 [DateTime](./) 类实例。 |
## 备注

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // 创建 'DateTime' 类实例。
  DateTime dateTime{1990, 10, 30};

  // 以多种格式打印实例。
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
此代码示例产生以下输出：
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## 参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)