---
title: DateTime
second_title: Aspose.Slides for C++ API Reference
description: "Represents a specific date and time value on the time continuum. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 183
url: /cpp/system/datetime/
---
## DateTime class


Represents a specific date and time value on the time continuum. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class DateTime
```

## Methods

| Method | Description |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Returns a new instance of [DateTime](./) class that represents a date and time value that results from addition of the specified time span to the date and time value represented by the current object. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of days. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of hours. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of milliseconds. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of minutes. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of months. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of seconds. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of 100-nanosecond intervals. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Returns a new instance of the [DateTime](./) class representing the date and time value equal to that represented by the current object with the year component increased by the specified number. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Compares two values represented by the specified instances of [DateTime](./) class and returns the value indicating values' relative positions on the time line. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Compares two date and time values represented by the current object and the specified instance of [DateTime](./) class and returns the value indicating values' relative positions on the time line. |
| constexpr [DateTime](./datetime/)() | Constructs an instance that represents the smallest possible date and time value equal to MinValue. |
|  [DateTime](./datetime/)(int, int, int) | Constructs an instance that represents a date and time value specified as a particular year, month and day. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Constructs an instance that represents a date and time value specified as a particular year, month and day in the specified calendar. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second in the specified calendar. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute, second and millisecond. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute, second and millisecond in the specified calendar. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Construct an instance that represents a date and time value specified as a number of ticks. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Construct an instance that represents a date and time value specified as a number of ticks. FOR INTERNAL USE. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Copy-constructs an instance. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Returns the number of days in the specified month of the specified year. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Determines if the specified instances of [DateTime](./) class represent the same date and time value. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Determines if the specified instance of [DateTime](./) class represent the same date and time value as the current object. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Deserializes the date time value from the specified unsigned 64-bit integer and sets the new instance of [DateTime](./) class to that value. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Converts the specified File time to an instance of [DateTime](./) class representing the same date and time value as local time. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Converts the specified File time to an instance of [DateTime](./) class representing the same date and time value as UTC time. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Returns an instance of [DateTime](./) class representing the date and time value equivalent to the specified OLE Automation Date. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Converts the specified Unix time value to an instance of [DateTime](./) class. FOR INTERNAL USE. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Returns a new instance of [DateTime](./) class that represents the date portion of the date and time represented by the current object with each component of the time portion set to 0. |
| int [get_Day](./get_day/)() const | Returns the ordinal number of the day in the month represented by the current object. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Returns a value representing a day of week that is represented by the current object. |
| int [get_DayOfYear](./get_dayofyear/)() const | Returns the ordinal number of the day in the year represented by the current object. |
| constexpr int [get_Hour](./get_hour/)() const | Returns the hour component of the date and time value represented by the current object. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Returns the value representing if the date and time represented by the current object is a local or UTC date and time or neither. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Returns the millisecond component of the date and time value represented by the current object. |
| constexpr int [get_Minute](./get_minute/)() const | Returns the minute component of the date and time value represented by the current object. |
| int [get_Month](./get_month/)() const | Returns the ordinal number of the month in the year represented by the current object. |
| static [DateTime](./) [get_Now](./get_now/)() | Returns an instance of [DateTime](./) class that represents the current time as local time. |
| constexpr int [get_Second](./get_second/)() const | Returns the second component of the date and time value represented by the current object. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Returns a number of 100-nanosecond intervals passed since 0:00:00 UTC, January 1, 0001, in the Gregorian calendar until the date and time represented by the current object. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Returns the value that represents the time interval from the beginning of the day represented by the current object till the date and time value represented by the current object. |
| static [DateTime](./) [get_Today](./get_today/)() | Returns an instance of [DateTime](./) class that represents the current date with each component of time portion of the value represented by the object set to 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Returns an instance of [DateTime](./) class that represents the current time as UTC. |
| int [get_Year](./get_year/)() const | Returns the year represented by the current object. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Gets date parts. FOR INTERNAL USE. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Returns array of strings where each element is the string representation of the current object formatted with one of the standard date and time format specifiers. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Returns array of strings where each element is the string representation of the current object formatted with the specified standard date and time format specifier. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Returns array of strings where each element is the string representation of the current object formatted with one of the standard date and time format specifiers and the specified format provider. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Returns array of strings where each element is the string representation of the current object formatted with the specified standard date and time format specifier and format provider. |
| int [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Determines if the date and time value represented by the current object falls in the range of daylight saving time for the current time zone. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Determines of the specified year is a leap year. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Determines if the current object and the specified [DateTime](./) object represent distinct date and time values. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Returns a new instance of [DateTime](./) class that represents the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Sets the current object to the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Returns an instance of [TimeSpan](../timespan/) class that represents the time interval between the date and time values represented by the current and the specified objects. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Sets the current object to the date and time value that is the result of subtraction of the specified time span from the date and time value represented by the current object. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Determines if the current object represents the date and time value that is earlier than the value represented by the specified [DateTime](./) object. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Determines if the current object represents the date and time value that is earlier than or the same as the value represented by the specified [DateTime](./) object. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Assigns the value represented by the specified [DateTime](./) instance to the current object. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Determines if the current object and the specified [DateTime](./) object represent the same date and time value. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Determines if the current object represents the date and time value that is later than the value represented by the specified [DateTime](./) object. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Determines if the current object represents the date and time value that is later than or the same as the value represented by the specified [DateTime](./) object. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using culture-specific format information. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified format and culture-specific format information. The format of the string representation must match the specified format exactly. Throws an exception if the conversion fails. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified formats, culture-specific format information and style. The format of the string representation must match one or more of the specified formats exactly. Throws an exception if the conversion fails. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Constructs a new [DateTime](./) object that represents the same number of ticks as the specified [DateTime](./) object and represents local time, UTC time or neither as specified by the argument **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Returns an instance of [TimeSpan](../timespan/) class representing the time interval between the date and time values represented by the current and the specified objects. |
| **int64_t** [ToBinary](./tobinary/)() const | Serializes the current object. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Returns a value that represents the date and time value represented by the current object as File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Converts the date and time value represented by the current object to File time UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Returns a new instance of [DateTime](./) class that represents the date and time value represented by the current object as local time. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Returns a string that contains the long date string representation of the current object. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Returns a string that contains the long time string representation of the current object. |
| **double** [ToOADate](./tooadate/)() const | Returns the date and time value represented by the current object as OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Returns a string that contains the short date string representation of the current object. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Returns a string that contains the short time string representation of the current object. |
| [String](../string/) [ToString](./tostring/)() const | Returns the string representation of the date and time value represented by the current object using the formatting conventions defined by the current culture. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Returns a string representation of the date and time value represented by the current object using the specified format and formatting conventions defined by the current culture. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Returns a string representation of the date and time value represented by the current object using the specified format information. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Returns a string representation of the date and time value represented by the current object using the specified format information. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Returns a new instance of [DateTime](./) class that represents the date and time value represented by the current object as UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Returns a value that represents the date and time value represented by the current object as Unix time. FOR INTERNAL USE. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified culture-specific format information and style. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified format, culture-specific format information and style. The format of the string representation must match the specified format exactly. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified formats, culture-specific format information and style. The format of the string representation must match one or more of the specified formats exactly. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returns a [TypeInfo](../typeinfo/) object that contains information about this class. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | The number of 100-nanosecond in the time interval between the minimal possible and maximal possible [DateTime](./) value. |
| static [MaxValue](./maxvalue/) | An instance of [DateTime](./) class that represents the maximal possible date and time value. |
| static constexpr [MinTicks](./minticks/) | The minimal number of ticks that an instance of [DateTime](./) class can represent. |
| static [MinValue](./minvalue/) | An instance of [DateTime](./) class that represents the minimal possible date and time value. |
| static constexpr [TicksPerDay](./ticksperday/) | The number of ticks in a day. |
| static constexpr [TicksPerHour](./ticksperhour/) | The number of ticks in a hour. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | The number of ticks in a microsecond. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | The number of ticks in a millisecond. |
| static constexpr [TicksPerMinute](./ticksperminute/) | The number of ticks in a minute. |
| static constexpr [TicksPerSecond](./tickspersecond/) | The number of ticks in a second. |
| static [UnixEpoch](./unixepoch/) | An instance of [DateTime](./) class that represents the Unix epoch start (1970.01.01 00:00:00). |
## Remarks



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Create the 'DateTime' class instance.
  DateTime dateTime{1990, 10, 30};

  // Print the instance in the multiple formats.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
This code example produces the following output:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
