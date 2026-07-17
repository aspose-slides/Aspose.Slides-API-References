---
title: DateTimeOffset
second_title: Aspose.Slides for C++ API 参考
description: "包含相对于协调世界时的日期和时间。此类的对象应仅使用 System::MakeObject() 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 235
url: /zh/system/datetimeoffset/
---
## DateTimeOffset 类

包含相对于协调世界时的日期和时间。此类的对象应仅使用 [System::MakeObject()](../makeobject/) 函数进行分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class DateTimeOffset
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | 向 [DateTimeOffset](./) 对象添加指定的时间间隔。 |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | 向 [DateTimeOffset](./) 对象添加指定天数。 |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | 向 [DateTimeOffset](./) 对象添加指定小时数。 |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | 向 [DateTimeOffset](./) 对象添加指定毫秒数。 |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | 向 [DateTimeOffset](./) 对象添加指定分钟数。 |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | 向 [DateTimeOffset](./) 对象添加指定月数。 |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | 向 [DateTimeOffset](./) 对象添加指定秒数。 |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | 向 [DateTimeOffset](./) 对象添加指定的滴答数。 |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | 向 [DateTimeOffset](./) 对象添加指定年数。 |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | 比较两个 [DateTimeOffset](./) 对象。 |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | 比较两个 [DateTimeOffset](./) 对象。 |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 比较两个 [DateTimeOffset](./) 对象。 |
| constexpr [DateTimeOffset](./datetimeoffset/)() | 默认构造函数。 |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | 构造函数。 |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | 构造函数。 |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | 构造函数。 |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | 构造函数。 |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | 构造函数。 |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | 构造函数。 |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | 检查两个 [DateTimeOffset](./) 对象是否表示相同的时间点。 |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | 检查两个 [DateTimeOffset](./) 对象是否表示相同的时间点。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 检查两个 [DateTimeOffset](./) 对象是否表示相同的时间点。 |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | 检查两个 [DateTimeOffset](./) 对象是否表示相同的时间点且具有相同的偏移量。 |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 检查两个 [DateTimeOffset](./) 对象是否表示相同的时间点且具有相同的偏移量。 |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) 文件时间转换为带本地时间偏移的日期和时间。 |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix 时间转换为 [DateTimeOffset](./) 对象。 |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix 时间转换为 [DateTimeOffset](./) 对象。 |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | 获取当前对象的日期部分。 |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | 获取 [DateTime](../datetime/) 值。 |
| int [get_Day](./get_day/)() const | 获取当前对象的月份中的天数。 |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | 获取当前对象的星期几。 |
| int [get_DayOfYear](./get_dayofyear/)() const | 获取当前对象的年中天数。 |
| int [get_Hour](./get_hour/)() const | 获取当前对象的小时部分。 |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | 获取表示本地日期和时间的 [DateTime](../datetime/) 值。 |
| constexpr int [get_Millisecond](./get_millisecond/)() const | 获取当前对象的毫秒部分。 |
| int [get_Minute](./get_minute/)() const | 获取当前对象的分钟部分。 |
| int [get_Month](./get_month/)() const | 获取当前对象的月份部分。 |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | 获取 [DateTimeOffset](./)，其日期和时间设置为当前本地时间，偏移量设置为本地时间的偏移量。 |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | 获取相对于 UTC 的偏移量。 |
| constexpr int [get_Second](./get_second/)() const | 获取当前对象的秒部分。 |
| **int64_t** [get_Ticks](./get_ticks/)() const | 获取当前对象的滴答数。 |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | 获取当前对象的时间（当天）。 |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | 获取表示 UTC 日期和时间的 [DateTime](../datetime/) 值。 |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | 获取 [DateTimeOffset](./)，其日期和时间设置为当前 UTC 时间，且偏移量为 [TimeSpan::Zero](../timespan/zero/)。 |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | 获取当前对象在 UTC 时间下的滴答数。 |
| int [get_Year](./get_year/)() const | 获取当前对象的年份部分。 |
| int [GetHashCode](./gethashcode/)() const | 获取当前 [DateTimeOffset](./) 对象的哈希码。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | 确定当前对象和指定的 [DateTimeOffset](./) 对象是否表示不同的日期和时间值。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | 返回一个新的 [DateTimeOffset](./) 类实例，表示当前对象与指定时间跨度相加后的日期和时间值。 |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | 返回一个新的 [DateTimeOffset](./) 类实例，表示从当前对象表示的值中减去指定时间跨度后的日期和时间值。 |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | 返回一个 [TimeSpan](../timespan/) 类实例，表示当前对象和指定对象之间的时间间隔。 |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | 确定当前对象的日期和时间值是否早于指定的 [DateTimeOffset](./) 对象表示的值。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | 确定当前对象的日期和时间值是否早于或等于指定的 [DateTimeOffset](./) 对象表示的值。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | 确定当前对象和指定的 [DateTimeOffset](./) 对象是否表示相同的日期和时间值。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | 确定当前对象的日期和时间值是否晚于指定的 [DateTimeOffset](./) 对象表示的值。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | 确定当前对象的日期和时间值是否晚于或等于指定的 [DateTimeOffset](./) 对象表示的值。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | 将指定的字符串转换为 [DateTimeOffset](./) 等价物。 |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用指定的格式提供程序和格式样式，将指定的字符串转换为 [DateTimeOffset](./) 对象。 |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用指定的格式、格式提供程序和格式样式，将指定的字符串转换为 [DateTimeOffset](./) 对象。 |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用指定的格式、格式提供程序和格式样式，将指定的字符串转换为 [DateTimeOffset](./) 对象。 |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | 从当前对象减去指定的时间间隔。 |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | 从当前对象减去指定的 [DateTimeOffset](./) 值。 |
| **int64_t** [ToFileTime](./tofiletime/)() const | 将当前对象转换为 [Windows](../../system.windows/) 文件时间。 |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | 将当前对象转换为表示本地时间的对象。 |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | 用指定的偏移量替换当前对象的偏移。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的格式和格式提供程序，将当前对象转换为字符串。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的格式提供程序，将当前对象转换为字符串。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 使用指定的格式，将当前对象转换为字符串。 |
| [String](../string/) [ToString](./tostring/)() const | 将当前对象转换为字符串。 |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | 将当前对象转换为表示 UTC 时间的对象。 |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | 获取自 Unix 纪元起始以来的毫秒数。 |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | 获取自 Unix 纪元起始以来的秒数。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | 尝试将指定的字符串转换为 [DateTimeOffset](./) 对象。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 尝试使用指定的格式提供程序和格式样式，将指定的字符串转换为 [DateTimeOffset](./) 对象。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 尝试使用指定的格式、格式提供程序和格式样式，将指定的字符串转换为 [DateTimeOffset](./) 对象。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 尝试使用指定的格式、格式提供程序和格式样式，将指定的字符串转换为 [DateTimeOffset](./) 对象。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 返回一个表示 [TimeSpan](../timespan/) 结构的 [TypeInfo](../typeinfo/) 对象。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | 获取以滴答为单位的最大偏移量。 |
| static [MaxValue](./maxvalue/) | 获取最大的 [DateTimeOffset](./) 值。 |
| static constexpr [MinOffset](./minoffset/) | 获取以滴答为单位的最小偏移量。 |
| static [MinValue](./minvalue/) | 获取最早的 [DateTimeOffset](./) 值。 |
| static [UnixEpoch](./unixepoch/) | 获取 Unix 纪元起始。 |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)