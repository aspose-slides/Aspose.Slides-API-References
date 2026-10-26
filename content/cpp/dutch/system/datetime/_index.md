---
title: DateTime
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een specifieke datum- en tijdwaarde op de tijdlijn voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr-klasse om objecten van dit type te beheren."
type: docs
weight: 222
url: /nl/system/datetime/
---
## DateTime klasse

Stelt een specifieke datum- en tijdwaarde op de tijdcontinuüm voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class DateTime
```

## Methodes

| Methode | Beschrijving |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Retourneert een nieuwe instantie van [DateTime](./) klasse die een datum- en tijdwaarde voorstelt die voortkomt uit de toevoeging van de opgegeven tijdsduur aan de datum- en tijdwaarde die wordt vertegenwoordigd door het huidige object. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Retourneert een nieuwe instantie van de [DateTime](./) klasse die de datum- en tijdwaarde weergeeft die de som is van de waarde die door het huidige object wordt vertegenwoordigd en het opgegeven aantal dagen. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Retourneert een nieuwe instantie van de [DateTime](./) klasse die de datum- en tijdwaarde weergeeft die de som is van de waarde die door het huidige object wordt vertegenwoordigd en het opgegeven aantal uren. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Retourneert een nieuwe instantie van de [DateTime](./) klasse die de datum- en tijdwaarde weergeeft die de som is van de waarde die door het huidige object wordt vertegenwoordigd en het opgegeven aantal milliseconden. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Retourneert een nieuwe instantie van de [DateTime](./) klasse die de datum- en tijdwaarde weergeeft die de som is van de waarde die door het huidige object wordt vertegenwoordigd en het opgegeven aantal minuten. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Retourneert een nieuwe instantie van de [DateTime](./) klasse die de datum- en tijdwaarde weergeeft die de som is van de waarde die door het huidige object wordt vertegenwoordigd en het opgegeven aantal maanden. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Retourneert een nieuwe instantie van de [DateTime](./) klasse die de datum- en tijdwaarde weergeeft die de som is van de waarde die door het huidige object wordt vertegenwoordigd en het opgegeven aantal seconden. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Retourneert een nieuwe instantie van de [DateTime](./) klasse die de datum- en tijdwaarde weergeeft die de som is van de waarde die door het huidige object wordt vertegenwoordigd en het opgegeven aantal 100-nanosecondenintervallen. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Retourneert een nieuwe instantie van de [DateTime](./) klasse die de datum- en tijdwaarde weergeeft die gelijk is aan die van het huidige object met het jaarcomponent verhoogd met het opgegeven aantal. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Vergelijkt twee waarden die worden vertegenwoordigd door de opgegeven instanties van [DateTime](./) klasse en retourneert de waarde die de relatieve positie van de waarden op de tijdlijn aangeeft. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Vergelijkt twee datum- en tijdwaarden die worden vertegenwoordigd door het huidige object en de opgegeven instantie van [DateTime](./) klasse en retourneert de waarde die de relatieve positie van de waarden op de tijdlijn aangeeft. |
| constexpr [DateTime](./datetime/)() | Construeert een instantie die de kleinst mogelijke datum- en tijdwaarde vertegenwoordigt die gelijk is aan MinValue. |
|  [DateTime](./datetime/)(int, int, int) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand en dag. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand en dag in de opgegeven kalender. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut en seconde. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut en seconde. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut en seconde in de opgegeven kalender. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut, seconde en milliseconde. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut, seconde en milliseconde in de opgegeven kalender. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een aantal ticks. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een aantal ticks. VOOR INTERN GEBRUIK. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Copy-constructeert een instantie. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Retourneert het aantal dagen in de opgegeven maand van het opgegeven jaar. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Bepaalt of de opgegeven instanties van [DateTime](./) klasse dezelfde datum- en tijdwaarde vertegenwoordigen. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Bepaalt of de opgegeven instantie van [DateTime](./) klasse dezelfde datum- en tijdwaarde heeft als het huidige object. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Deserialiseert de datum-tijdwaarde uit het opgegeven ongetekende 64-bit geheel getal en stelt de nieuwe instantie van [DateTime](./) klasse in op die waarde. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Converteert de opgegeven bestandstijd naar een instantie van [DateTime](./) klasse die dezelfde datum- en tijdwaarde als lokale tijd vertegenwoordigt. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Converteert de opgegeven bestandstijd naar een instantie van [DateTime](./) klasse die dezelfde datum- en tijdwaarde als UTC-tijd vertegenwoordigt. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Retourneert een instantie van [DateTime](./) klasse die de datum- en tijdwaarde vertegenwoordigt die overeenkomt met de opgegeven OLE Automation-datum. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Converteert de opgegeven Unix-tijdwaarde naar een instantie van [DateTime](./) klasse. VOOR INTERN GEBRUIK. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Retourneert een nieuwe instantie van [DateTime](./) klasse die het datumgedeelte van de datum- en tijdwaarde die door het huidige object wordt vertegenwoordigd weergeeft, waarbij elk onderdeel van het tijdgedeelte op 0 is ingesteld. |
| int [get_Day](./get_day/)() const | Retourneert het ordinale nummer van de dag in de maand die door het huidige object wordt vertegenwoordigd. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Retourneert een waarde die een dag van de week vertegenwoordigt die door het huidige object wordt weergegeven. |
| int [get_DayOfYear](./get_dayofyear/)() const | Retourneert het ordinale nummer van de dag in het jaar dat door het huidige object wordt weergegeven. |
| constexpr int [get_Hour](./get_hour/)() const | Retourneert het uur-component van de datum- en tijdwaarde die door het huidige object wordt weergegeven. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Retourneert de waarde die aangeeft of de datum- en tijdwaarde die door het huidige object wordt vertegenwoordigd lokaal, UTC of geen van beide is. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Retourneert het milliseconde-component van de datum- en tijdwaarde die door het huidige object wordt weergegeven. |
| constexpr int [get_Minute](./get_minute/)() const | Retourneert het minuut-component van de datum- en tijdwaarde die door het huidige object wordt weergegeven. |
| int [get_Month](./get_month/)() const | Retourneert het ordinale nummer van de maand in het jaar dat door het huidige object wordt weergegeven. |
| static [DateTime](./) [get_Now](./get_now/)() | Retourneert een instantie van [DateTime](./) klasse die de huidige tijd als lokale tijd weergeeft. |
| constexpr int [get_Second](./get_second/)() const | Retourneert het seconde-component van de datum- en tijdwaarde die door het huidige object wordt weergegeven. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Retourneert een aantal 100-nanosecondenintervallen dat is verstreken sinds 0:00:00 UTC, 1 januari 0001, in de Gregoriaanse kalender tot de datum- en tijdwaarde die door het huidige object wordt weergegeven. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Retourneert de waarde die het tijdsinterval weergeeft vanaf het begin van de dag die door het huidige object wordt vertegenwoordigd tot de datum- en tijdwaarde die door het huidige object wordt weergegeven. |
| static [DateTime](./) [get_Today](./get_today/)() | Retourneert een instantie van [DateTime](./) klasse die de huidige datum weergeeft met elk onderdeel van het tijdgedeelte van de waarde die door het object wordt vertegenwoordigd ingesteld op 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Retourneert een instantie van [DateTime](./) klasse die de huidige tijd als UTC weergeeft. |
| int [get_Year](./get_year/)() const | Retourneert het jaar dat door het huidige object wordt weergegeven. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Haalt datumonderdelen op. VOOR INTERN GEBRUIK. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, opgemaakt met een van de standaard datum- en tijdformaat-specificators. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, opgemaakt met de opgegeven standaard datum- en tijdformaat-specificator. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, opgemaakt met een van de standaard datum- en tijdformaat-specificators en de opgegeven format-provider. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, opgemaakt met de opgegeven standaard datum- en tijdformaat-specificator en format-provider. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hash-code voor het huidige object. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Bepaalt of de datum- en tijdwaarde die door het huidige object wordt vertegenwoordigd valt binnen het bereik van de zomertijd voor de huidige tijdzone. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Bepaalt of het opgegeven jaar een schrikkeljaar is. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Bepaalt of het huidige object en het opgegeven [DateTime](./) object verschillende datum- en tijdwaarden vertegenwoordigen. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Retourneert een nieuwe instantie van [DateTime](./) klasse die de datum- en tijdwaarde vertegenwoordigt die de som is van de waarde die door het huidige object wordt weergegeven en de opgegeven tijdsduur. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Stelt het huidige object in op de datum- en tijdwaarde die de som is van de waarde die door het huidige object wordt weergegeven en de opgegeven tijdsduur. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Retourneert een nieuwe instantie van [DateTime](./) klasse die de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van de opgegeven tijdsduur van de waarde die door het huidige object wordt weergegeven. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Retourneert een instantie van [TimeSpan](../timespan/) klasse die het tijdsinterval vertegenwoordigt tussen de datum- en tijdwaarden die door het huidige en het opgegeven object worden weergegeven. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Stelt het huidige object in op de datum- en tijdwaarde die het resultaat is van het aftrekken van de opgegeven tijdsduur van de datum- en tijdwaarde die door het huidige object wordt weergegeven. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Bepaalt of het huidige object de datum- en tijdwaarde vertegenwoordigt die eerder is dan de waarde die door het opgegeven [DateTime](./) object wordt weergegeven. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Bepaalt of het huidige object de datum- en tijdwaarde vertegenwoordigt die eerder is dan of gelijk is aan de waarde die door het opgegeven [DateTime](./) object wordt weergegeven. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Kent de waarde toe die wordt vertegenwoordigd door de opgegeven [DateTime](./) instantie aan het huidige object. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Bepaalt of het huidige object en het opgegeven [DateTime](./) object dezelfde datum- en tijdwaarde vertegenwoordigen. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Bepaalt of het huidige object de datum- en tijdwaarde vertegenwoordigt die later ligt dan de waarde die wordt weergegeven door het opgegeven [DateTime](./) object. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Bepaalt of het huidige object de datum- en tijdwaarde vertegenwoordigt die later is of gelijk aan de waarde die wordt weergegeven door het opgegeven [DateTime](./) object. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](./) object. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](./) object met behulp van cultuurspecifieke opmaakgegevens. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](./) object met behulp van het opgegeven formaat en cultuurspecifieke opmaakgegevens. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met het opgegeven formaat. Werpt een uitzondering als de conversie mislukt. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](./) object met behulp van de opgegeven formaten, cultuurspecifieke opmaakgegevens en stijl. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met een of meer van de opgegeven formaten. Werpt een uitzondering als de conversie mislukt. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Construeert een nieuw [DateTime](./) object dat hetzelfde aantal ticks vertegenwoordigt als het opgegeven [DateTime](./) object en lokale tijd, UTC-tijd of geen van beide weergeeft zoals gespecificeerd door het argument **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Retourneert een nieuw exemplaar van de [DateTime](./) klasse die de datum- en tijdwaarde vertegenwoordigt die het resultaat is van aftrekken van de opgegeven tijdsduur van de waarde die wordt weergegeven door het huidige object. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Retourneert een exemplaar van de [TimeSpan](../timespan/) klasse die het tijdsinterval vertegenwoordigt tussen de datum- en tijdwaarden die worden weergegeven door het huidige en het opgegeven object. |
| **int64_t** [ToBinary](./tobinary/)() const | Serialiseert het huidige object. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Retourneert een waarde die de datum- en tijdwaarde van het huidige object weergeeft als File-tijd. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Converteert de datum- en tijdwaarde van het huidige object naar File-tijd UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Retourneert een nieuw exemplaar van de [DateTime](./) klasse die de datum- en tijdwaarde van het huidige object weergeeft als lokale tijd. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Retourneert een tekenreeks die de lange datumreeksrepresentatie van het huidige object bevat. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Retourneert een tekenreeks die de lange tijdreeksrepresentatie van het huidige object bevat. |
| **double** [ToOADate](./tooadate/)() const | Retourneert de datum- en tijdwaarde van het huidige object als OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Retourneert een tekenreeks die de korte datumreeksrepresentatie van het huidige object bevat. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Retourneert een tekenreeks die de korte tijdreeksrepresentatie van het huidige object bevat. |
| [String](../string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van de datum- en tijdwaarde van het huidige object met behulp van de opmaakconventies die zijn gedefinieerd door de huidige cultuur. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Retourneert een tekenreeksrepresentatie van de datum- en tijdwaarde van het huidige object met behulp van het opgegeven formaat en de opmaakconventies die zijn gedefinieerd door de huidige cultuur. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retourneert een tekenreeksrepresentatie van de datum- en tijdwaarde van het huidige object met behulp van de opgegeven opmaakinformatie. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retourneert een tekenreeksrepresentatie van de datum- en tijdwaarde van het huidige object met behulp van de opgegeven opmaakinformatie. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Retourneert een nieuw exemplaar van de [DateTime](./) klasse die de datum- en tijdwaarde van het huidige object weergeeft als UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Retourneert een waarde die de datum- en tijdwaarde van het huidige object weergeeft als Unix-tijd. VOOR INTERN GEBRUIK. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](./) object. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](./) object met behulp van de opgegeven cultuurspecifieke opmaakinformatie en stijl. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](./) object met behulp van het opgegeven formaat, cultuurspecifieke opmaakinformatie en stijl. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met het opgegeven formaat. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](./) object met behulp van de opgegeven formaten, cultuurspecifieke opmaakinformatie en stijl. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met een of meer van de opgegeven formaten. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retourneert een [TypeInfo](../typeinfo/) object dat informatie over deze klasse bevat. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Het aantal 100-nanoseconden in het tijdsinterval tussen de minimaal mogelijke en maximaal mogelijke [DateTime](./) waarde. |
| static [MaxValue](./maxvalue/) | Een exemplaar van de [DateTime](./) klasse die de maximaal mogelijke datum- en tijdwaarde vertegenwoordigt. |
| static constexpr [MinTicks](./minticks/) | Het minimale aantal ticks dat een exemplaar van de [DateTime](./) klasse kan vertegenwoordigen. |
| static [MinValue](./minvalue/) | Een exemplaar van de [DateTime](./) klasse die de minimaal mogelijke datum- en tijdwaarde vertegenwoordigt. |
| static constexpr [TicksPerDay](./ticksperday/) | Het aantal ticks in een dag. |
| static constexpr [TicksPerHour](./ticksperhour/) | Het aantal ticks in een uur. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Het aantal ticks in een microseconde. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Het aantal ticks in een milliseconde. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Het aantal ticks in een minuut. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Het aantal ticks in een seconde. |
| static [UnixEpoch](./unixepoch/) | Een exemplaar van de [DateTime](./) klasse die het begin van de Unix-epoch (1970-01-01 00:00:00) vertegenwoordigt. |

## Opmerkingen

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Maak een instantie van de klasse 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Print de instantie in de verschillende formaten.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende uitvoer:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Zie ook

* Namespace [System](../)
* Library [Aspose.Slides](../../)