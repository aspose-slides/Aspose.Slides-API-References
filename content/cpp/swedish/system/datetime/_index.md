---
title: DateTime
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett specifikt datum- och tidsvärde på tidskontinuumet. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 222
url: /sv/system/datetime/
---
## DateTime klass

Representerar ett specifikt datum- och tidsvärde på tidskontinuumet. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class DateTime
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Returnerar en ny instans av [DateTime](./) klass som representerar ett datum- och tidsvärde som erhålls genom att lägga till det specificerade tidsintervallet till datum- och tidsvärdet som representeras av det aktuella objektet. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade antalet dagar. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade antalet timmar. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade antalet millisekunder. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade antalet minuter. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade antalet månader. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade antalet sekunder. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade antalet 100-nanosekundintervall. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet där årsdelen har ökats med det specificerade antalet. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Jämför två värden som representeras av de specificerade instanserna av [DateTime](./) klass och returnerar ett värde som indikerar värdenas relativa positioner på tidslinjen. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Jämför två datum- och tidsvärden som representeras av det aktuella objektet och den specificerade instansen av [DateTime](./) klass och returnerar ett värde som indikerar värdenas relativa positioner på tidslinjen. |
| constexpr [DateTime](./datetime/)() | Skapar en instans som representerar det minsta möjliga datum- och tidsvärdet som är lika med MinValue. |
|  [DateTime](./datetime/)(int, int, int) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett visst år, månad och dag. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett visst år, månad och dag i den specificerade kalendern. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett visst år, månad, dag, timme, minut och sekund. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett visst år, månad, dag, timme, minut och sekund. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett visst år, månad, dag, timme, minut och sekund i den specificerade kalendern. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett visst år, månad, dag, timme, minut, sekund och millisekund. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett visst år, månad, dag, timme, minut, sekund och millisekund i den specificerade kalendern. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett antal tick. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Skapar en instans som representerar ett datum- och tidsvärde specificerat som ett antal tick. FÖR INTERNT ANVÄNDNING. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Kopierar en instans. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Returnerar antalet dagar i den specificerade månaden för det specificerade året. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Avgör om de specificerade instanserna av [DateTime](./) klass representerar samma datum- och tidsvärde. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Avgör om den specificerade instansen av [DateTime](./) klass representerar samma datum- och tidsvärde som det aktuella objektet. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Deserialiserar datum- och tidsvärdet från det specificerade icke-signerade 64-bit-heltalet och sätter den nya instansen av [DateTime](./) klass till det värdet. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Konverterar den specificerade filtiden till en instans av [DateTime](./) klass som representerar samma datum- och tidsvärde som lokal tid. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Konverterar den specificerade filtiden till en instans av [DateTime](./) klass som representerar samma datum- och tidsvärde som UTC-tid. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Returnerar en instans av [DateTime](./) klass som representerar datum- och tidsvärdet som motsvarar den specificerade OLE Automation-datumet. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Konverterar det specificerade Unix-tidsvärdet till en instans av [DateTime](./) klass. FÖR INTERNT ANVÄNDNING. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Returnerar en ny instans av [DateTime](./) klass som representerar datumdelen av datum- och tidsvärdet som representeras av det aktuella objektet, med varje komponent av tidsdelen satt till 0. |
| int [get_Day](./get_day/)() const | Returnerar det ordningsmässiga numret på dagen i månaden som representeras av det aktuella objektet. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Returnerar ett värde som representerar veckodagen som representeras av det aktuella objektet. |
| int [get_DayOfYear](./get_dayofyear/)() const | Returnerar det ordningsmässiga numret på dagen i året som representeras av det aktuella objektet. |
| constexpr int [get_Hour](./get_hour/)() const | Returnerar timkomponenten av datum- och tidsvärdet som representeras av det aktuella objektet. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Returnerar ett värde som indikerar om datum- och tidsvärdet som representeras av det aktuella objektet är lokalt, UTC eller ingen av dem. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Returnerar millisekundkomponenten av datum- och tidsvärdet som representeras av det aktuella objektet. |
| constexpr int [get_Minute](./get_minute/)() const | Returnerar minutkomponenten av datum- och tidsvärdet som representeras av det aktuella objektet. |
| int [get_Month](./get_month/)() const | Returnerar det ordningsmässiga numret på månaden i året som representeras av det aktuella objektet. |
| static [DateTime](./) [get_Now](./get_now/)() | Returnerar en instans av [DateTime](./) klass som representerar den aktuella tiden som lokal tid. |
| constexpr int [get_Second](./get_second/)() const | Returnerar sekundkomponenten av datum- och tidsvärdet som representeras av det aktuella objektet. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Returnerar antalet 100-nanosekundintervall som har passerat sedan 0:00:00 UTC den 1 januari 0001 i den gregorianska kalendern fram till datum- och tidsvärdet som representeras av det aktuella objektet. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Returnerar värdet som representerar tidsintervallet från början av dagen som representeras av det aktuella objektet till datum- och tidsvärdet som representeras av det aktuella objektet. |
| static [DateTime](./) [get_Today](./get_today/)() | Returnerar en instans av [DateTime](./) klass som representerar det aktuella datumet med varje komponent av tidsdelen av värdet som representeras av objektet satt till 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Returnerar en instans av [DateTime](./) klass som representerar den aktuella tiden som UTC. |
| int [get_Year](./get_year/)() const | Returnerar året som representeras av det aktuella objektet. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Hämtar datumdelar. FÖR INTERNT ANVÄNDNING. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Returnerar en array av strängar där varje element är strängrepresentationen av det aktuella objektet formaterad med en av de standardiserade datum- och tidsformat-specifierarna. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Returnerar en array av strängar där varje element är strängrepresentationen av det aktuella objektet formaterad med den specificerade standardiserade datum- och tidsformat-specifieraren. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Returnerar en array av strängar där varje element är strängrepresentationen av det aktuella objektet formaterad med en av de standardiserade datum- och tidsformat-specifierarna samt den specificerade formatleverantören. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Returnerar en array av strängar där varje element är strängrepresentationen av det aktuella objektet formaterad med den specificerade standardiserade datum- och tidsformat-specifieraren och formatleverantören. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hash-kod för det aktuella objektet. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Avgör om datum- och tidsvärdet som representeras av det aktuella objektet faller inom sommartidsintervallet för den aktuella tidszonen. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Avgör om det specificerade året är ett skottår. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Avgör om det aktuella objektet och det specificerade [DateTime](./)-objektet representerar olika datum- och tidsvärden. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade tidsintervallet. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Sätter det aktuella objektet till datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det specificerade tidsintervallet. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Returnerar en ny instans av [DateTime](./) klass som representerar datum- och tidsvärdet som är resultatet av att subtrahera det specificerade tidsintervallet från värdet som representeras av det aktuella objektet. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Returnerar en instans av [TimeSpan](../timespan/) klass som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella och det specificerade objektet. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Sätter det aktuella objektet till datum- och tidsvärdet som är resultatet av att subtrahera det specificerade tidsintervallet från datum- och tidsvärdet som representeras av det aktuella objektet. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Avgör om det aktuella objektet representerar datum- och tidsvärdet som är tidigare än värdet som representeras av det specificerade [DateTime](./)-objektet. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Avgör om det aktuella objektet representerar datum- och tidsvärdet som är tidigare än eller lika med värdet som representeras av det specificerade [DateTime](./)-objektet. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Tilldelar värdet som representeras av den specificerade [DateTime](./)-instansen till det aktuella objektet. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Avgör om det aktuella objektet och det specificerade [DateTime](./)-objektet representerar samma datum- och tidsvärde. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är senare än värdet som representeras av det specificerade [DateTime](./)-objektet. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är senare än eller samma som värdet som representeras av det specificerade [DateTime](./)-objektet. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Konverterar den specificerade strängrepresentationen av ett datum- och tidsvärde till det motsvarande [DateTime](./)-objektet. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konverterar den specificerade strängrepresentationen av ett datum- och tidsvärde till det motsvarande [DateTime](./)-objektet med hjälp av kulturspecifik formatinformation. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konverterar den specificerade strängrepresentationen av ett datum- och tidsvärde till det motsvarande [DateTime](./)-objektet med det angivna formatet och kulturspecifik formatinformation. Strängrepresentationens format måste exakt matcha det specificerade formatet. Ett undantag kastas om konverteringen misslyckas. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konverterar den specificerade strängrepresentationen av ett datum- och tidsvärde till det motsvarande [DateTime](./)-objektet med de angivna formaten, kulturspecifik formatinformation och stil. Strängrepresentationens format måste exakt matcha ett eller flera av de specificerade formaten. Ett undantag kastas om konverteringen misslyckas. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Skapar ett nytt [DateTime](./)-objekt som representerar samma antal tickar som det specificerade [DateTime](./)-objektet och representerar lokaltid, UTC-tid eller ingen av delarna enligt argumentet **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Returnerar en ny instans av [DateTime](./)-klassen som representerar datum- och tidsvärdet som är resultatet av subtraktion av den specificerade tidsintervallen från värdet som representeras av det aktuella objektet. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Returnerar en instans av [TimeSpan](../timespan/)-klassen som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella och det specificerade objektet. |
| **int64_t** [ToBinary](./tobinary/)() const | Serialiserar det aktuella objektet. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Returnerar ett värde som representerar datum- och tidsvärdet som det aktuella objektet representerar som filtid. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Konverterar datum- och tidsvärdet som det aktuella objektet representerar till filtid UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Returnerar en ny instans av [DateTime](./)-klassen som representerar datum- och tidsvärdet som det aktuella objektet representerar som lokaltid. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Returnerar en sträng som innehåller den långa datumsträngrepresentationen av det aktuella objektet. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Returnerar en sträng som innehåller den långa tidssträngrepresentationen av det aktuella objektet. |
| **double** [ToOADate](./tooadate/)() const | Returnerar datum- och tidsvärdet som det aktuella objektet representerar som OLE Automation-datum. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Returnerar en sträng som innehåller den korta datumsträngrepresentationen av det aktuella objektet. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Returnerar en sträng som innehåller den korta tidssträngrepresentationen av det aktuella objektet. |
| [String](../string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av datum- och tidsvärdet som det aktuella objektet representerar med de formateringskonventioner som definieras av den aktuella kulturen. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Returnerar en strängrepresentation av datum- och tidsvärdet som det aktuella objektet representerar med det specificerade formatet och de formateringskonventioner som definieras av den aktuella kulturen. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Returnerar en strängrepresentation av datum- och tidsvärdet som det aktuella objektet representerar med den specificerade formatinformationen. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Returnerar en strängrepresentation av datum- och tidsvärdet som det aktuella objektet representerar med den specificerade formatinformationen. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Returnerar en ny instans av [DateTime](./)-klassen som representerar datum- och tidsvärdet som det aktuella objektet representerar som UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Returnerar ett värde som representerar datum- och tidsvärdet som det aktuella objektet representerar som Unix-tid. FÖR INTERNT BRUK. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Konverterar den specificerade strängrepresentationen av ett datum- och tidsvärde till det motsvarande [DateTime](./)-objektet. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konverterar den specificerade strängrepresentationen av ett datum- och tidsvärde till det motsvarande [DateTime](./)-objektet med den specificerade kulturspecifika formatinformationen och stilen. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konverterar den specificerade strängrepresentationen av ett datum- och tidsvärde till det motsvarande [DateTime](./)-objektet med det specificerade formatet, kulturspecifik formatinformation och stil. Strängrepresentationens format måste exakt matcha det specificerade formatet. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konverterar den specificerade strängrepresentationen av ett datum- och tidsvärde till det motsvarande [DateTime](./)-objektet med de specificerade formaten, kulturspecifik formatinformation och stil. Strängrepresentationens format måste exakt matcha ett eller flera av de specificerade formaten. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returnerar ett [TypeInfo](../typeinfo/)-objekt som innehåller information om den här klassen. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Antalet 100-nanosekunder i tidsintervallet mellan det minsta möjliga och det största möjliga [DateTime](./)-värdet. |
| static [MaxValue](./maxvalue/) | En instans av [DateTime](./)-klassen som representerar det största möjliga datum- och tidsvärdet. |
| static constexpr [MinTicks](./minticks/) | Det minsta antalet tickar som en instans av [DateTime](./)-klassen kan representera. |
| static [MinValue](./minvalue/) | En instans av [DateTime](./)-klassen som representerar det minsta möjliga datum- och tidsvärdet. |
| static constexpr [TicksPerDay](./ticksperday/) | Antalet tickar i en dag. |
| static constexpr [TicksPerHour](./ticksperhour/) | Antalet tickar i en timme. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Antalet tickar i en mikrosekund. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Antalet tickar i en millisekund. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Antalet tickar i en minut. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Antalet tickar i en sekund. |
| static [UnixEpoch](./unixepoch/) | En instans av [DateTime](./)-klassen som representerar Unix-epokens start (1970-01-01 00:00:00). |

## Anmärkningar



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Skapa en instans av klassen 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Skriv ut instansen i flera format.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Detta kodexempel producerar följande utdata:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)