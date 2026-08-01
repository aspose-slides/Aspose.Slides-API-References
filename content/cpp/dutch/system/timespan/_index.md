---
title: TimeSpan
second_title: "Aspose.Slides voor C++ API-referentie"
description: "Vertegenwoordigt een tijdsinterval. Dit type moet op de stack worden toegewezen en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 1314
url: /nl/system/timespan/
---
## TimeSpan klasse

Vertegenwoordigt een tijdsinterval. Dit type moet worden toegewezen op de stack en doorgegeven aan functies per waarde of referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class TimeSpan
```

## Methodes

| Methode | Beschrijving |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Retourneert een nieuwe instantie van [TimeSpan](./) klasse die een tijdsinterval vertegenwoordigt dat de som is van de tijdsintervallen die worden vertegenwoordigd door het huidige en het opgegeven object. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Vergelijkt twee [TimeSpan](./) objecten. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Vergelijkt het huidige en het opgegeven objecten. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Vergelijkt het huidige en het opgegeven objecten. |
| [TimeSpan](./) [Duration](./duration/)() const | Retourneert een nieuwe instantie van [TimeSpan](./) object waarvan de waarde de absolute waarde van het huidige object is. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Bepaalt of het tijdsinterval dat wordt vertegenwoordigd door het huidige object gelijk is aan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Bepaalt of het tijdsinterval dat wordt vertegenwoordigd door het huidige object gelijk is aan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Retourneert true als de opgegeven objecten hetzelfde tijdsinterval vertegenwoordigen, anders false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Retourneert een nieuw [TimeSpan](./) object dat het opgegeven interval vertegenwoordigt. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Retourneert een nieuw [TimeSpan](./) object dat het opgegeven interval vertegenwoordigt. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Retourneert een nieuw [TimeSpan](./) object dat het opgegeven interval vertegenwoordigt. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Retourneert een nieuw [TimeSpan](./) object dat het opgegeven interval vertegenwoordigt. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Retourneert een nieuw [TimeSpan](./) object dat het opgegeven interval vertegenwoordigt. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Retourneert een nieuw [TimeSpan](./) object dat het opgegeven interval vertegenwoordigt. |
| constexpr int [get_Days](./get_days/)() const | Retourneert het dagenonderdeel van het tijdsinterval dat wordt vertegenwoordigd door het huidige [TimeSpan](./) object. |
| constexpr int [get_Hours](./get_hours/)() const | Retourneert het urenonderdeel van het tijdsinterval dat wordt vertegenwoordigd door het huidige [TimeSpan](./) object. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Retourneert het millisecondenonderdeel van het tijdsinterval dat wordt vertegenwoordigd door het huidige [TimeSpan](./) object. |
| constexpr int [get_Minutes](./get_minutes/)() const | Retourneert het minutenonderdeel van het tijdsinterval dat wordt vertegenwoordigd door het huidige [TimeSpan](./) object. |
| constexpr int [get_Seconds](./get_seconds/)() const | Retourneert het secondenonderdeel van het tijdsinterval dat wordt vertegenwoordigd door het huidige [TimeSpan](./) object. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Retourneert het aantal 100-nanosecondenintervallen waaruit het tijdsinterval bestaat dat wordt vertegenwoordigd door het huidige [TimeSpan](./) object. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Retourneert de waarde van het huidige [TimeSpan](./) object uitgedrukt in gehele en fractionele dagen. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Retourneert de waarde van het huidige [TimeSpan](./) object uitgedrukt in gehele en fractionele uren. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Retourneert de waarde van het huidige [TimeSpan](./) object uitgedrukt in gehele en fractionele milliseconden. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Retourneert de waarde van het huidige [TimeSpan](./) object uitgedrukt in gehele en fractionele minuten. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Retourneert de waarde van het huidige [TimeSpan](./) object uitgedrukt in gehele en fractionele seconden. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Retourneert een nieuwe instantie van [TimeSpan](./) object dat de negatief genomen waarde vertegenwoordigt van het huidige [TimeSpan](./) object. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Bepaalt of het tijdsinterval dat wordt vertegenwoordigd door het huidige object niet gelijk is aan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Retourneert een nieuwe instantie van [TimeSpan](./) klasse die een tijdsinterval vertegenwoordigt dat de som is van de tijdsintervallen die worden vertegenwoordigd door het huidige en het opgegeven object. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Retourneert zichzelf. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Wijst het tijdsinterval toe aan het huidige object dat de som is van het tijdsinterval dat wordt vertegenwoordigd door het huidige en het opgegeven object. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Retourneert een nieuwe instantie van [TimeSpan](./) klasse die een tijdsinterval vertegenwoordigt dat het resultaat is van het aftrekken van het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object van het tijdsinterval dat wordt vertegenwoordigd door het huidige object. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Retourneert een nieuwe instantie van [TimeSpan](./) object dat de negatief genomen waarde vertegenwoordigt van het huidige [TimeSpan](./) object. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Wijst het tijdsinterval toe aan het huidige object dat het resultaat is van het aftrekken van het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object van het tijdsinterval dat wordt vertegenwoordigd door het huidige object. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Bepaalt of het tijdsinterval dat wordt vertegenwoordigd door het huidige object korter is dan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Bepaalt of het tijdsinterval dat wordt vertegenwoordigd door het huidige object korter is dan of gelijk is aan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Stelt het tijdsinterval in van het opgegeven [TimeSpan](./) object op het huidige [TimeSpan](./) object. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Bepaalt of het tijdsinterval dat wordt vertegenwoordigd door het huidige object gelijk is aan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Bepaalt of het tijdsinterval dat wordt vertegenwoordigd door het huidige object langer is dan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Bepaalt of het tijdsinterval dat wordt vertegenwoordigd door het huidige object langer is dan of gelijk is aan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Converteert string naar gelijkwaardig [TimeSpan](./) object. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert string naar gelijkwaardig [TimeSpan](./) object met behulp van de opgegeven opmaakprovider. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Converteert string naar gelijkwaardig [TimeSpan](./) object met behulp van de opgegeven formaten, opmaakprovider en stijlen. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Converteert string naar gelijkwaardig [TimeSpan](./) object met behulp van het opgegeven formaat, opmaakprovider en stijlen. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Retourneert een nieuwe instantie van [TimeSpan](./) klasse die een tijdsinterval vertegenwoordigt dat het resultaat is van het aftrekken van het tijdsinterval dat wordt vertegenwoordigd door het opgegeven object van het tijdsinterval dat wordt vertegenwoordigd door het huidige object. |
| constexpr [TimeSpan](./timespan/)() | Construeert een [TimeSpan](./) object dat een nul tijdsinterval vertegenwoordigt. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Construeert een instantie van [TimeSpan](./) klasse die het opgegeven tijdsinterval vertegenwoordigt. |
|  [TimeSpan](./timespan/)(int, int, int) | Construeert een instantie van [TimeSpan](./) klasse die het tijdsinterval vertegenwoordigt dat gelijk is aan de som van het opgegeven aantal uren, minuten en seconden. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Construeert een instantie van [TimeSpan](./) klasse die het tijdsinterval vertegenwoordigt dat gelijk is aan de som van het opgegeven aantal uren, minuten, seconden en milliseconden. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Construeert een [TimeSpan](./) object dat het tijdsinterval vertegenwoordigt dat gelijk is aan het tijdsinterval dat wordt vertegenwoordigd door het opgegeven [TimeSpan](./) object. |
| [String](../string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van het tijdsinterval dat wordt vertegenwoordigd door het huidige object. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converteert de waarde van het huidige object naar een gelijkwaardige tekenreeksrepresentatie, met behulp van het opgegeven formaat. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converteert de waarde van het huidige object naar een gelijkwaardige tekenreeksrepresentatie, met behulp van het opgegeven formaat en de opmaakprovider. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Converteert string naar gelijkwaardig [TimeSpan](./) object en retourneert het resultaat van de conversie. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converteert string naar gelijkwaardig [TimeSpan](./) object met behulp van de opgegeven opmaakprovider en retourneert het resultaat van de conversie. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converteert string naar gelijkwaardig [TimeSpan](./) object met behulp van de opgegeven formaten en opmaakprovider, en retourneert het resultaat van de conversie. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Converteert string naar gelijkwaardig [TimeSpan](./) object met behulp van het opgegeven formaat, opmaakprovider en stijlen, en retourneert het resultaat van de conversie. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Converteert string naar gelijkwaardig [TimeSpan](./) object met behulp van de opgegeven formaten, opmaakprovider en stijlen, en retourneert het resultaat van de conversie. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converteert string naar gelijkwaardig [TimeSpan](./) object met behulp van het opgegeven formaat en de opmaakprovider, en retourneert het resultaat van de conversie. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retourneert een [TypeInfo](../typeinfo/) object dat de [TimeSpan](./) structuur vertegenwoordigt. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [MaxValue](./maxvalue/) | Het [TimeSpan](./) object dat het langst mogelijke interval vertegenwoordigt. |
| static [MinValue](./minvalue/) | /// Het [TimeSpan](./) object dat het kortst mogelijke interval vertegenwoordigt. |
| static constexpr [TicksPerDay](./ticksperday/) | Het aantal 100-nanosecondenintervallen in een dag (24-uur interval). |
| static constexpr [TicksPerHour](./ticksperhour/) | Het aantal 100-nanosecondenintervallen in een uur. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Het aantal 100-nanosecondenintervallen in een milliseconde. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Het aantal 100-nanosecondenintervallen in een minuut. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Het aantal 100-nanosecondenintervallen in een seconde. |
| static [Zero](./zero/) | Het [TimeSpan](./) object dat een nul-interval vertegenwoordigt. |

## Opmerkingen

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
Dit codevoorbeeld produceert de volgende output:
Aantal ticks: 260928000000000
Aantal milliseconden: 0
Totaal aantal milliseconden: 2.60928e+10
Aantal minuten: 0
Totaal aantal minuten: 434880
Aantal uren: 0
Totaal aantal uren: 0
Aantal dagen: 302
Totaal aantal dagen: 302
*/
```

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)