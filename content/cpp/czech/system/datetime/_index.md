---
title: DateTime
second_title: Aspose.Slides pro C++ - referenční příručka API
description: "Reprezentuje konkrétní datum a čas na časové ose. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 222
url: /cs/system/datetime/
---
## DateTime třída

Represents a specific date and time value on the time continuum. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) třída to manage objects of this type.

```cpp
class DateTime
```

## Metody

| Metoda | Popis |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Returns a new instance of [DateTime](./) třída that represents a date and time value that results from addition of the specified time span to the date and time value represented by the current object. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Returns a new instance of the [DateTime](./) třída representing the date and time value which is the sum of the value represented by the current object and the specified number of days. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Returns a new instance of the [DateTime](./) třída representing the date and time value which is the sum of the value represented by the current object and the specified number of hours. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Returns a new instance of the [DateTime](./) třída representing the date and time value which is the sum of the value represented by the current object and the specified number of milliseconds. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Returns a new instance of the [DateTime](./) třída representing the date and time value which is the sum of the value represented by the current object and the specified number of minutes. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Returns a new instance of the [DateTime](./) třída representing the date and time value which is the sum of the value represented by the current object and the specified number of months. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Returns a new instance of the [DateTime](./) třída representing the date and time value which is the sum of the value represented by the current object and the specified number of seconds. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Returns a new instance of the [DateTime](./) třída representing the date and time value which is the sum of the value represented by the current object and the specified number of 100-nanosecond intervals. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Returns a new instance of the [DateTime](./) třída representing the date and time value equal to that represented by the current object with the year component increased by the specified number. |
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
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Determines if the specified instances of [DateTime](./) třída represent the same date and time value. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Determines if the specified instance of [DateTime](./) třída represent the same date and time value as the current object. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Deserializes the date time value from the specified unsigned 64-bit integer and sets the new instance of [DateTime](./) třída to that value. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Converts the specified File time to an instance of [DateTime](./) třída representing the same date and time value as local time. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Converts the specified File time to an instance of [DateTime](./) třída representing the same date and time value as UTC time. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Returns an instance of [DateTime](./) třída representing the date and time value equivalent to the specified OLE Automation Date. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Converts the specified Unix time value to an instance of [DateTime](./) třída. FOR INTERNAL USE. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Returns a new instance of [DateTime](./) třída that represents the date portion of the date and time represented by the current object with each component of the time portion set to 0. |
| int [get_Day](./get_day/)() const | Returns the ordinal number of the day in the month represented by the current object. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Returns a value representing a day of week that is represented by the current object. |
| int [get_DayOfYear](./get_dayofyear/)() const | Returns the ordinal number of the day in the year represented by the current object. |
| constexpr int [get_Hour](./get_hour/)() const | Returns the hour component of the date and time value represented by the current object. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Returns the value representing if the date and time represented by the current object is a local or UTC date and time or neither. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Returns the millisecond component of the date and time value represented by the current object. |
| constexpr int [get_Minute](./get_minute/)() const | Returns the minute component of the date and time value represented by the current object. |
| int [get_Month](./get_month/)() const | Returns the ordinal number of the month in the year represented by the current object. |
| static [DateTime](./) [get_Now](./get_now/)() | Returns an instance of [DateTime](./) třída that represents the current time as local time. |
| constexpr int [get_Second](./get_second/)() const | Returns the second component of the date and time value represented by the current object. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Returns a number of 100-nanosecond intervals passed since 0:00:00 UTC, January 1, 0001, in the Gregorian calendar until the date and time represented by the current object. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Returns the value that represents the time interval from the beginning of the day represented by the current object till the date and time value represented by the current object. |
| static [DateTime](./) [get_Today](./get_today/)() | Returns an instance of [DateTime](./) třída that represents the current date with each component of time portion of the value represented by the object set to 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Returns an instance of [DateTime](./) třída that represents the current time as UTC. |
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
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Returns a new instance of [DateTime](./) třída that represents the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Sets the current object to the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Returns a new instance of the [DateTime](./) třída representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Returns an instance of [TimeSpan](../timespan/) třída that represents the time interval between the date and time values represented by the current and the specified objects. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Sets the current object to the date and time value that is the result of subtraction of the specified time span from the date and time value represented by the current object. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Determines if the current object represents the date and time value that is earlier than the value represented by the specified [DateTime](./) object. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Determines if the current object represents the date and time value that is earlier than or the same as the value represented by the specified [DateTime](./) object. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Assigns the value represented by the specified [DateTime](./) instance to the current object. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Determines if the current object and the specified [DateTime](./) object represent the same date and time value. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Určuje, zda aktuální objekt představuje hodnotu data a času, která je pozdější než hodnota reprezentovaná zadaným objektem [DateTime](./). |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Určuje, zda aktuální objekt představuje hodnotu data a času, která je pozdější nebo stejná jako hodnota reprezentovaná zadaným objektem [DateTime](./). |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Převádí zadanou textovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](./). |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Převádí zadanou textovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](./) pomocí informací o formátu specifickém pro kulturu. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Převádí zadanou textovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](./) pomocí specifikovaného formátu a informací o formátu specifickém pro kulturu. Formát textové reprezentace musí přesně odpovídat specifikovanému formátu. Vyvolá výjimku, pokud převod selže. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Převádí zadanou textovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](./) pomocí specifikovaných formátů, informací o formátu specifickém pro kulturu a stylu. Formát textové reprezentace musí přesně odpovídat jednomu nebo více ze specifikovaných formátů. Vyvolá výjimku, pokud převod selže. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Vytvoří nový objekt [DateTime](./), který představuje stejný počet tiků jako zadaný objekt [DateTime](./) a reprezentuje místní čas, čas UTC nebo žádný, podle hodnoty argumentu **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Vrací novou instanci třídy [DateTime](./) představující hodnotu data a času, která je výsledkem odečtení zadaného časového intervalu od hodnoty reprezentované aktuálním objektem. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Vrací instanci třídy [TimeSpan](../timespan/) představující časový interval mezi hodnotami data a času reprezentovanými aktuálním a zadaným objektem. |
| **int64_t** [ToBinary](./tobinary/)() const | Serializuje aktuální objekt. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Vrací hodnotu, která představuje hodnotu data a času reprezentovanou aktuálním objektem jako File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Převádí hodnotu data a času reprezentovanou aktuálním objektem na File time UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Vrací novou instanci třídy [DateTime](./), která představuje hodnotu data a času reprezentovanou aktuálním objektem jako místní čas. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Vrací řetězec, který obsahuje dlouhou datumovou reprezentaci aktuálního objektu. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Vrací řetězec, který obsahuje dlouhou časovou reprezentaci aktuálního objektu. |
| **double** [ToOADate](./tooadate/)() const | Vrací hodnotu data a času reprezentovanou aktuálním objektem jako OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Vrací řetězec, který obsahuje krátkou datumovou reprezentaci aktuálního objektu. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Vrací řetězec, který obsahuje krátkou časovou reprezentaci aktuálního objektu. |
| [String](../string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem podle formátovacích konvencí definovaných aktuální kulturou. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem pomocí specifikovaného formátu a formátovacích konvencí definovaných aktuální kulturou. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem pomocí specifikovaných informací o formátu. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem pomocí specifikovaných informací o formátu. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Vrací novou instanci třídy [DateTime](./), která představuje hodnotu data a času reprezentovanou aktuálním objektem jako UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Vrací hodnotu, která představuje hodnotu data a času reprezentovanou aktuálním objektem jako Unix time. PRO INTERNÍ POUŽITÍ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Převádí zadanou textovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Převádí zadanou textovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](./) pomocí specifikovaných informací o formátu specifickém pro kulturu a stylu. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Převádí zadanou textovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](./) pomocí specifikovaného formátu, informací o formátu specifickém pro kulturu a stylu. Formát textové reprezentace musí přesně odpovídat specifikovanému formátu. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Převádí zadanou textovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](./) pomocí specifikovaných formátů, informací o formátu specifickém pro kulturu a stylu. Formát textové reprezentace musí přesně odpovídat jednomu nebo více ze specifikovaných formátů. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Vrací objekt [TypeInfo](../typeinfo/), který obsahuje informace o této třídě. |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Počet 100-nanosekund v časovém intervalu mezi minimální a maximální možnou hodnotou [DateTime](./). |
| static [MaxValue](./maxvalue/) | Instanci třídy [DateTime](./) představující maximální možnou hodnotu data a času. |
| static constexpr [MinTicks](./minticks/) | Minimální počet tiků, které může představovat instance třídy [DateTime](./). |
| static [MinValue](./minvalue/) | Instanci třídy [DateTime](./) představující minimální možnou hodnotu data a času. |
| static constexpr [TicksPerDay](./ticksperday/) | Počet tiků za den. |
| static constexpr [TicksPerHour](./ticksperhour/) | Počet tiků za hodinu. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Počet tiků za mikrosekundu. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Počet tiků za milisekundu. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Počet tiků za minutu. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Počet tiků za sekundu. |
| static [UnixEpoch](./unixepoch/) | Instanci třídy [DateTime](./) představující začátek epochy Unix (1970-01-01 00:00:00). |

## Poznámky

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Vytvořte instanci třídy 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Vytiskněte instanci v různých formátech.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Tento příklad kódu vypíše následující výstup:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Viz také

* Namespace [System](../)
* Library [Aspose.Slides](../../)