---
title: DateTimeOffset
second_title: Aspose.Slides för C++ API-referens
description: "Innehåller datum och tid på dagen i förhållande till koordinerad universell tid. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Inslut alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 235
url: /sv/system/datetimeoffset/
---
## DateTimeOffset klass

Innehåller datum och tid på dagen i förhållande till Koordinerad universell tid. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Inslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class DateTimeOffset
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Lägger till ett specificerat tidsintervall till [DateTimeOffset](./)-objektet. |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Lägger till ett specificerat antal dagar till [DateTimeOffset](./)-objektet. |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Lägger till ett specificerat antal timmar till [DateTimeOffset](./)-objektet. |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Lägger till ett specificerat antal millisekunder till [DateTimeOffset](./)-objektet. |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Lägger till ett specificerat antal minuter till [DateTimeOffset](./)-objektet. |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Lägger till ett specificerat antal månader till [DateTimeOffset](./)-objektet. |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Lägger till ett specificerat antal sekunder till [DateTimeOffset](./)-objektet. |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Lägger till ett specificerat antal tickar till [DateTimeOffset](./)-objektet. |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Lägger till ett specificerat antal år till [DateTimeOffset](./)-objektet. |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Jämför två [DateTimeOffset](./)-objekt. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Jämför två [DateTimeOffset](./)-objekt. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Jämför två [DateTimeOffset](./)-objekt. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Standardkonstruktör. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Konstruktor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt och har samma offset. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt och har samma offset. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) filtid till datum och tid med lokal tidsoffset. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-tid till [DateTimeOffset](./)-objekt. |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-tid till [DateTimeOffset](./)-objekt. |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Hämtar datumkomponenten för det aktuella objektet. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Hämtar [DateTime](../datetime/)-värde. |
| int [get_Day](./get_day/)() const | Hämtar dagen i månaden för det aktuella objektet. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Hämtar veckodagen för det aktuella objektet. |
| int [get_DayOfYear](./get_dayofyear/)() const | Hämtar dagen på året för det aktuella objektet. |
| int [get_Hour](./get_hour/)() const | Hämtar timmekomponenten för det aktuella objektet. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Hämtar [DateTime](../datetime/)-värde som representerar det lokala datumet och tiden. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Hämtar millisekundkomponenten för det aktuella objektet. |
| int [get_Minute](./get_minute/)() const | Hämtar minutkomponenten för det aktuella objektet. |
| int [get_Month](./get_month/)() const | Hämtar månadskomponenten för det aktuella objektet. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Hämtar [DateTimeOffset](./) vars datum och tid är satta till den aktuella lokala tiden och vars offset är satt till den lokala tidens offset. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Hämtar offset från UTC. |
| constexpr int [get_Second](./get_second/)() const | Hämtar sekundkomponenten för det aktuella objektet. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Hämtar antalet tickar för det aktuella objektet. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Hämtar tid på dagen för det aktuella objektet. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Hämtar [DateTime](../datetime/)-värde som representerar UTC-datum och tid. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Hämtar [DateTimeOffset](./) vars datum och tid är satta till den aktuella UTC-tiden och vars offset är [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Hämtar antalet tickar för det aktuella objektet i UTC-tid. |
| int [get_Year](./get_year/)() const | Hämtar årskomponenten för det aktuella objektet. |
| int [GetHashCode](./gethashcode/)() const | Hämtar hash-kod för det aktuella [DateTimeOffset](./)-objektet. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Bestämmer om det aktuella objektet och det specificerade [DateTimeOffset](./)-objektet representerar olika datum- och tidsvärden. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Returnerar en ny instans av [DateTimeOffset](./)-klassen som representerar datum- och tidsvärdet som är summan av värdet representerat av det aktuella objektet och den specificerade tidsperioden. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Returnerar en ny instans av [DateTimeOffset](./)-klassen som representerar datum- och tidsvärdet som är resultatet av subtraktionen av den specificerade tidsperioden från värdet representerat av det aktuella objektet. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Returnerar en instans av [TimeSpan](../timespan/)-klassen som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella och det specificerade objektet. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är tidigare än värdet representerat av det specificerade [DateTimeOffset](./)-objektet. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är tidigare än eller lika med värdet representerat av det specificerade [DateTimeOffset](./)-objektet. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Bestämmer om det aktuella objektet och det specificerade [DateTimeOffset](./)-objektet representerar samma datum- och tidsvärde. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är senare än värdet representerat av det specificerade [DateTimeOffset](./)-objektet. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är senare än eller lika med värdet representerat av det specificerade [DateTimeOffset](./)-objektet. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Konverterar den specificerade strängen till [DateTimeOffset](./)-ekvivalent. |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konverterar den specificerade strängen till [DateTimeOffset](./)-objekt med den specificerade formatleverantören och formateringsstilen. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konverterar den specificerade strängen till [DateTimeOffset](./)-objekt med det specificerade formatet, formatleverantören och formateringsstilen. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konverterar den specificerade strängen till [DateTimeOffset](./)-objekt med de specificerade formaten, formatleverantören och formateringsstilen. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Subtraherar ett specificerat tidsintervall från det aktuella objektet. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Subtraherar ett specificerat [DateTimeOffset](./)-värde från det aktuella objektet. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Konverterar det aktuella objektet till [Windows](../../system.windows/)-filtid. |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Konverterar det aktuella objektet till ett objekt som representerar den lokala tiden. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Ersätter det aktuella objektets offset med den specificerade offseten. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konverterar det aktuella objektet till en sträng med det specificerade formatet och formatleverantören. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konverterar det aktuella objektet till en sträng med den specificerade formatleverantören. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konverterar det aktuella objektet till en sträng med det specificerade formatet. |
| [String](../string/) [ToString](./tostring/)() const | Konverterar det aktuella objektet till en sträng. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Konverterar det aktuella objektet till ett objekt som representerar UTC-tiden. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Hämtar millisekunder som har förflutit sedan Unix-epokens start. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Hämtar sekunder som har förflutit sedan Unix-epokens start. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Försöker konvertera den specificerade strängen till [DateTimeOffset](./)-objekt. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Försöker konvertera den specificerade strängen till [DateTimeOffset](./)-objekt med den specificerade formatleverantören och formateringsstilen. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Försöker konvertera den specificerade strängen till [DateTimeOffset](./)-objekt med de specificerade formaten, formatleverantören och formateringsstilen. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Försöker konvertera den specificerade strängen till [DateTimeOffset](./)-objekt med det specificerade formatet, formatleverantören och formateringsstilen. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returnerar ett [TypeInfo](../typeinfo/)-objekt som representerar [TimeSpan](../timespan/)-strukturen. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Hämtar maximal offset i tickar. |
| static [MaxValue](./maxvalue/) | Hämtar största [DateTimeOffset](./)-värde. |
| static constexpr [MinOffset](./minoffset/) | Hämtar minimal offset i tickar. |
| static [MinValue](./minvalue/) | Hämtar tidigaste [DateTimeOffset](./)-värde. |
| static [UnixEpoch](./unixepoch/) | Hämtar Unix-epokens start. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)