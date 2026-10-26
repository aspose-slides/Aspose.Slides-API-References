---
title: TimeSpan
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett tidsintervall. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig System::SmartPtr klassen för att hantera objekt av denna typ."
type: docs
weight: 1314
url: /sv/system/timespan/
---
## TimeSpan klass

Representerar ett tidsintervall. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class TimeSpan
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Returnerar en ny instans av [TimeSpan](./) klass som representerar ett tidsintervall som är summan av de tidsintervall som representeras av det aktuella och de angivna objekten. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Jämför två [TimeSpan](./) objekt. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Jämför det aktuella och de angivna objekten. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Jämför det aktuella och de angivna objekten. |
| [TimeSpan](./) [Duration](./duration/)() const | Returnerar en ny instans av [TimeSpan](./) objekt vars värde är det absoluta värdet av det aktuella objektet. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Fastställer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det angivna objektet. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Fastställer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det angivna objektet. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Returnerar true om de angivna objekten representerar samma tidsintervall, annars false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det angivna intervallet. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det angivna intervallet. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det angivna intervallet. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det angivna intervallet. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det angivna intervallet. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det angivna intervallet. |
| constexpr int [get_Days](./get_days/)() const | Returnerar dagkomponenten i tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| constexpr int [get_Hours](./get_hours/)() const | Returnerar timkomponenten i tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Returnerar millisekundkomponenten i tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| constexpr int [get_Minutes](./get_minutes/)() const | Returnerar minutkomponenten i tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| constexpr int [get_Seconds](./get_seconds/)() const | Returnerar sekundkomponenten i tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Returnerar antalet 100-nanosekundintervall som utgör tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av dagar. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av timmar. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av millisekunder. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av minuter. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av sekunder. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Returnerar en ny instans av [TimeSpan](./) objekt som representerar det negerade värdet som det aktuella [TimeSpan](./) objektet har. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Fastställer om tidsintervallet som representeras av det aktuella objektet inte är lika med tidsintervallet som representeras av det angivna objektet. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Returnerar en ny instans av [TimeSpan](./) klass som representerar ett tidsintervall som är summan av de tidsintervall som representeras av det aktuella och de angivna objekten. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Returnerar sig själv. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Tilldelar det aktuella objektet tidsintervallet som är summan av tidsintervallet som representeras av det aktuella och det angivna objektet. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Returnerar en ny instans av [TimeSpan](./) klass som representerar ett tidsintervall som är resultatet av att subtrahera tidsintervallet som representeras av det angivna objektet från tidsintervallet som representeras av det aktuella objektet. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Returnerar en ny instans av [TimeSpan](./) objekt som representerar det negerade värdet som det aktuella [TimeSpan](./) objektet har. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Tilldelar det aktuella objektet tidsintervallet som är resultatet av att subtrahera tidsintervallet som representeras av det angivna objektet från tidsintervallet som representeras av det aktuella objektet. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Fastställer om tidsintervallet som representeras av det aktuella objektet är kortare än tidsintervallet som representeras av det angivna objektet. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Fastställer om tidsintervallet som representeras av det aktuella objektet är kortare än eller lika med tidsintervallet som representeras av det angivna objektet. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Ställer in tidsintervallet som representeras av det angivna [TimeSpan](./) objektet till det aktuella [TimeSpan](./) objektet. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Fastställer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det angivna objektet. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Fastställer om tidsintervallet som representeras av det aktuella objektet är längre än tidsintervallet som representeras av det angivna objektet. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Fastställer om tidsintervallet som representeras av det aktuella objektet är längre än eller lika med tidsintervallet som representeras av det angivna objektet. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt med den angivna formatleverantören. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt med de angivna formaten, formatleverantören och stilarna. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt med det angivna formatet, formatleverantören och stilarna. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Returnerar en ny instans av [TimeSpan](./) klass som representerar ett tidsintervall som är resultatet av att subtrahera tidsintervallet som representeras av det angivna objektet från tidsintervallet som representeras av det aktuella objektet. |
| constexpr [TimeSpan](./timespan/)() | Skapar ett [TimeSpan](./) objekt som representerar ett nolltidsintervall. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Skapar en instans av [TimeSpan](./) klass som representerar det angivna tidsintervallet. |
|  [TimeSpan](./timespan/)(int, int, int) | Skapar en instans av [TimeSpan](./) klass som representerar tidsintervallet som är lika med summan av det angivna antalet timmar, minuter och sekunder. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Skapar en instans av [TimeSpan](./) klass som representerar tidsintervallet som är lika med summan av det angivna antalet timmar, minuter, sekunder och millisekunder. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Skapar ett [TimeSpan](./) objekt som representerar tidsintervallet som är lika med tidsintervallet som representeras av det angivna [TimeSpan](./) objektet. |
| [String](../string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av tidsintervallet som representeras av det aktuella objektet. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konverterar värdet av det aktuella objektet till motsvarande strängrepresentation med det angivna formatet. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konverterar värdet av det aktuella objektet till motsvarande strängrepresentation med det angivna formatet och formatleverantören. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt och returnerar konverteringsresultatet. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt med den angivna formatleverantören och returnerar konverteringsresultatet. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt med de angivna formaten och formatleverantören, och returnerar konverteringsresultatet. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt med det angivna formatet, formatleverantören och stilarna, och returnerar konverteringsresultatet. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt med de angivna formaten, formatleverantören och stilarna, och returnerar konverteringsresultatet. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konverterar en sträng till motsvarande [TimeSpan](./) objekt med det angivna formatet och formatleverantören, och returnerar konverteringsresultatet. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returnerar ett [TypeInfo](../typeinfo/) objekt som representerar [TimeSpan](./) struktur. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [MaxValue](./maxvalue/) | Objektet [TimeSpan](./) som representerar det längsta möjliga intervallet. |
| static [MinValue](./minvalue/) | /// Objektet [TimeSpan](./) som representerar det kortaste möjliga intervallet. |
| static constexpr [TicksPerDay](./ticksperday/) | Antalet 100-nanosekundintervall på en dag (24-timmarsintervall). |
| static constexpr [TicksPerHour](./ticksperhour/) | Antalet 100-nanosekundintervall på en timme. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Antalet 100-nanosekundintervall på en millisekund. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Antalet 100-nanosekundintervall på en minut. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Antalet 100-nanosekundintervall på en sekund. |
| static [Zero](./zero/) | Objektet [TimeSpan](./) som representerar ett nollintervall. |

## Anmärkningar



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
Det här kodexemplet producerar följande utskrift:
Antal tick: 260928000000000
Antal millisekunder: 0
Totalt antal millisekunder: 2.60928e+10
Antal minuter: 0
Totalt antal minuter: 434880
Antal timmar: 0
Totalt antal timmar: 0
Antal dagar: 302
Totalt antal dagar: 302
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)