---
title: DateTimeOffset
second_title: Aspose.Slides for C++ API Reference
description: "Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 196
url: /cpp/system/datetimeoffset/
---
## DateTimeOffset class


Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeOffset
```

## Methods

| Method | Description |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Adds a specified time interval to the [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Adds a specified number of days to the [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Adds a specified number of hours to the [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Adds a specified number of milliseconds to the [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Adds a specified number of minutes to the [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Adds a specified number of months to the [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Adds a specified number of seconds to the [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Adds a specified number of ticks to the [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Adds a specified number of years to the [DateTimeOffset](./) object. |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Compares two [DateTimeOffset](./) objects. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Compares two [DateTimeOffset](./) objects. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Compares two [DateTimeOffset](./) objects. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Default constructor. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Constructor. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Constructor. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Constructor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Constructor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Constructor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Constructor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Checks if two [DateTimeOffset](./) objects represent the same time point. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Checks if two [DateTimeOffset](./) objects represents the same time point. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Checks if two [DateTimeOffset](./) objects represents the same time point. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Checks if two [DateTimeOffset](./) objects represents the same time point and has the same offset. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Checks if two [DateTimeOffset](./) objects represents the same time point and has the same offset. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) file time to date and time with local time offset. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time to [DateTimeOffset](./) object. |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time to [DateTimeOffset](./) object. |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Gets date component of the current object. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Gets [DateTime](../datetime/) value. |
| int [get_Day](./get_day/)() const | Gets day of the month of the current object. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Gets day of the week of the current object. |
| int [get_DayOfYear](./get_dayofyear/)() const | Gets day of year of the current object. |
| int [get_Hour](./get_hour/)() const | Gets hour component of the current object. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Gets [DateTime](../datetime/) value that represents the local date and time. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Gets millisecond component of the current object. |
| int [get_Minute](./get_minute/)() const | Gets minute component of the current object. |
| int [get_Month](./get_month/)() const | Gets month component of the current object. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Gets [DateTimeOffset](./) whose date and time are set to the current local-time and whose offset is set to local time's offset. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Gets offset from UTC. |
| constexpr int [get_Second](./get_second/)() const | Gets second component of the current object. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Gets number of ticks of the current object. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Gets time of day of the current object. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Gets [DateTime](../datetime/) value that represents the UTC date and time. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Gets [DateTimeOffset](./) whose date and time are set to the current UTC-time and whose offset is [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Gets number of ticks of the current object in UTC time. |
| int [get_Year](./get_year/)() const | Gets year component of the current object. |
| int [GetHashCode](./gethashcode/)() const | Gets hash code for the current [DateTimeOffset](./) object. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Determines if the current object and the specified [DateTimeOffset](./) object represent distinct date and time values. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Returns a new instance of [DateTimeOffset](./) class that represents the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Returns a new instance of the [DateTimeOffset](./) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Returns an instance of [TimeSpan](../timespan/) class that represents the time interval between the date and time values represented by the current and the specified objects. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Determines if the current object represents the date and time value that is earlier than the value represented by the specified [DateTimeOffset](./) object. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Determines if the current object represents the date and time value that is earlier than or the same as the value represented by the specified [DateTimeOffset](./) object. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Determines if the current object and the specified [DateTimeOffset](./) object represent the same date and time value. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Determines if the current object represents the date and time value that is later than the value represented by the specified [DateTimeOffset](./) object. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Determines if the current object represents the date and time value that is later than or the same as the value represented by the specified [DateTimeOffset](./) object. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Converts the specified string to [DateTimeOffset](./) equivalent. |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converts the specified string to [DateTimeOffset](./) object using the specified format provider and formatting style. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converts the specified string to [DateTimeOffset](./) object using the specified format, format provider and formatting style. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converts the specified string to [DateTimeOffset](./) object using the specified formats, format provider and formatting style. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Subtracts a specified time interval from the current object. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Subtracts a specified [DateTimeOffset](./) value from the current object. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Converts current object to the [Windows](../../system.windows/) file time. |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Converts current object to a object that represents the local time,. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Replace current object offset by the specified offset. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converts current object to string using the specified format and format provider. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converts current object to string using the specified format provider. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converts current object to string using the specified format. |
| [String](../string/) [ToString](./tostring/)() const | Converts current object to string. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Converts current object to a object that represents the UTC time,. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Gets milliseconds elapsed from Unix epoch start. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Gets seconds elapsed from Unix epoch start. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Tries to converts the specified string to [DateTimeOffset](./) object. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tries to converts the specified string to [DateTimeOffset](./) object using the specified format provider and formatting style. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tries to converts the specified string to [DateTimeOffset](./) object using the specified formats, format provider and formatting style. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tries to converts the specified string to [DateTimeOffset](./) object using the specified format, format provider and formatting style. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returns a [TypeInfo](../typeinfo/) object that represent [TimeSpan](../timespan/) structure. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Gets maximum offset in ticks. |
| static [MaxValue](./maxvalue/) | Gets greatest [DateTimeOffset](./) value. |
| static constexpr [MinOffset](./minoffset/) | Gets minimum offset in ticks. |
| static [MinValue](./minvalue/) | Gets earliest [DateTimeOffset](./) value. |
| static [UnixEpoch](./unixepoch/) | Gets Unix epoch start. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)