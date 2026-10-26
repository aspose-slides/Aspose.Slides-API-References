---
title: TimeSpan
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Představuje časový interval. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 1314
url: /cs/system/timespan/
---
## TimeSpan třída


Representuje časový interval. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) k řízení objektů tohoto typu.

```cpp
class TimeSpan
```

## Metody

| Metoda | Popis |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Vrací novou instanci třídy [TimeSpan](./), která představuje časový interval, který je součtem časových intervalů reprezentovaných aktuálním a specifikovaným objektem. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Porovnává dva objekty [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Porovnává aktuální a specifikované objekty. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Porovnává aktuální a specifikované objekty. |
| [TimeSpan](./) [Duration](./duration/)() const | Vrací novou instanci objektu [TimeSpan](./), jehož hodnota je absolutní hodnota aktuálního objektu. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Určuje, zda časový interval reprezentovaný aktuálním objektem je roven časovému intervalu reprezentovanému specifikovaným objektem. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Určuje, zda časový interval reprezentovaný aktuálním objektem je roven časovému intervalu reprezentovanému specifikovaným objektem. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Vrací true, pokud specifikované objekty představují stejný časový interval, jinak false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Vrací nový objekt [TimeSpan](./), který představuje zadaný interval. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Vrací nový objekt [TimeSpan](./), který představuje zadaný interval. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Vrací nový objekt [TimeSpan](./), který představuje zadaný interval. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Vrací nový objekt [TimeSpan](./), který představuje zadaný interval. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Vrací nový objekt [TimeSpan](./), který představuje zadaný interval. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Vrací nový objekt [TimeSpan](./), který představuje zadaný interval. |
| constexpr int [get_Days](./get_days/)() const | Vrací část dnů časového intervalu reprezentovaného aktuálním objektem [TimeSpan](./). |
| constexpr int [get_Hours](./get_hours/)() const | Vrací část hodin časového intervalu reprezentovaného aktuálním objektem [TimeSpan](./). |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Vrací část milisekund časového intervalu reprezentovaného aktuálním objektem [TimeSpan](./). |
| constexpr int [get_Minutes](./get_minutes/)() const | Vrací část minut časového intervalu reprezentovaného aktuálním objektem [TimeSpan](./). |
| constexpr int [get_Seconds](./get_seconds/)() const | Vrací část sekund časového intervalu reprezentovaného aktuálním objektem [TimeSpan](./). |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Vrací počet intervalů 100 nanosekund, které tvoří časový interval reprezentovaný aktuálním objektem [TimeSpan](./). |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Vrací hodnotu aktuálního objektu [TimeSpan](./) vyjádřenou v celých a zlomkových dnech. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Vrací hodnotu aktuálního objektu [TimeSpan](./) vyjádřenou v celých a zlomkových hodinách. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Vrací hodnotu aktuálního objektu [TimeSpan](./) vyjádřenou v celých a zlomkových milisekundách. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Vrací hodnotu aktuálního objektu [TimeSpan](./) vyjádřenou v celých a zlomkových minutách. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Vrací hodnotu aktuálního objektu [TimeSpan](./) vyjádřenou v celých a zlomkových sekundách. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Vrací novou instanci objektu [TimeSpan](./), která představuje negovanou hodnotu reprezentovanou aktuálním objektem [TimeSpan](./). |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Určuje, zda časový interval reprezentovaný aktuálním objektem není roven časovému intervalu reprezentovanému specifikovaným objektem. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Vrací novou instanci třídy [TimeSpan](./), která představuje časový interval, jenž je součtem časových intervalů reprezentovaných aktuálním a specifikovaným objektem. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Vrací sebe. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Přiřadí aktuálnímu objektu časový interval, který je součtem časových intervalů reprezentovaných aktuálním a specifikovaným objektem. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Vrací novou instanci třídy [TimeSpan](./), která představuje časový interval, jenž je výsledkem odečtení časového intervalu reprezentovaného specifikovaným objektem od časového intervalu reprezentovaného aktuálním objektem. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Vrací novou instanci objektu [TimeSpan](./), která představuje negovanou hodnotu reprezentovanou aktuálním objektem [TimeSpan](./). |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Přiřadí aktuálnímu objektu časový interval, který je výsledkem odečtení časového intervalu reprezentovaného specifikovaným objektem od časového intervalu reprezentovaného aktuálním objektem. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Určuje, zda časový interval reprezentovaný aktuálním objektem je kratší než časový interval reprezentovaný specifikovaným objektem. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Určuje, zda časový interval reprezentovaný aktuálním objektem je kratší než nebo roven časovému intervalu reprezentovanému specifikovaným objektem. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Nastaví časový interval reprezentovaný specifikovaným objektem [TimeSpan](./) na aktuální objekt [TimeSpan](./). |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Určuje, zda časový interval reprezentovaný aktuálním objektem je roven časovému intervalu reprezentovanému specifikovaným objektem. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Určuje, zda časový interval reprezentovaný aktuálním objektem je delší než časový interval reprezentovaný specifikovaným objektem. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Určuje, zda časový interval reprezentovaný aktuálním objektem je delší než nebo roven časovému intervalu reprezentovanému specifikovaným objektem. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./). |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) pomocí zadaného poskytovatele formátu. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) pomocí zadaných formátů, poskytovatele formátu a stylů. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) pomocí zadaného formátu, poskytovatele formátu a stylů. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Vrací novou instanci třídy [TimeSpan](./), která představuje časový interval, jenž je výsledkem odečtení časového intervalu reprezentovaného specifikovaným objektem od časového intervalu reprezentovaného aktuálním objektem. |
| constexpr [TimeSpan](./timespan/)() | Vytvoří objekt [TimeSpan](./), který představuje nulový časový interval. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Vytvoří instanci třídy [TimeSpan](./), která představuje zadaný časový interval. |
|  [TimeSpan](./timespan/)(int, int, int) | Vytvoří instanci třídy [TimeSpan](./), která představuje časový interval roven součtu zadaného počtu hodin, minut a sekund. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Vytvoří instanci třídy [TimeSpan](./), která představuje časový interval roven součtu zadaného počtu hodin, minut, sekund a milisekund. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Vytvoří objekt [TimeSpan](./), který představuje časový interval roven časovému intervalu reprezentovanému specifikovaným objektem [TimeSpan](./). |
| [String](../string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci časového intervalu reprezentovaného aktuálním objektem. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Převádí hodnotu aktuálního objektu na ekvivalentní řetězcovou reprezentaci pomocí zadaného formátu. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Převádí hodnotu aktuálního objektu na ekvivalentní řetězcovou reprezentaci pomocí zadaného formátu a poskytovatele formátu. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) a vrací výsledek konverze. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) pomocí zadaného poskytovatele formátu a vrací výsledek konverze. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) pomocí zadaných formátů a poskytovatele formátu, a vrací výsledek konverze. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) pomocí zadaného formátu, poskytovatele formátu a stylů, a vrací výsledek konverze. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) pomocí zadaných formátů, poskytovatele formátu a stylů, a vrací výsledek konverze. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Převádí řetězec na ekvivalentní objekt [TimeSpan](./) pomocí zadaného formátu a poskytovatele formátu, a vrací výsledek konverze. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Vrací objekt [TypeInfo](../typeinfo/), který reprezentuje strukturu [TimeSpan](./). |

## Pole

| Pole | Popis |
| --- | --- |
| static [MaxValue](./maxvalue/) | Objekt [TimeSpan](./) představuje nejdelší možný interval. |
| static [MinValue](./minvalue/) | /// Objekt [TimeSpan](./) představuje nejkratší možný interval. |
| static constexpr [TicksPerDay](./ticksperday/) | Počet 100-nanosekundových intervalů za den (24-hodinový interval). |
| static constexpr [TicksPerHour](./ticksperhour/) | Počet 100-nanosekundových intervalů za hodinu. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Počet 100-nanosekundových intervalů za milisekundu. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Počet 100-nanosekundových intervalů za minutu. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Počet 100-nanosekundových intervalů za sekundu. |
| static [Zero](./zero/) | Objekt [TimeSpan](./) představuje nulový interval. |

## Poznámky



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
Tento ukázkový kód generuje následující výstup:
Počet tiků: 260928000000000
Počet milisekund: 0
Celkový počet milisekund: 2.60928e+10
Počet minut: 0
Celkový počet minut: 434880
Počet hodin: 0
Celkový počet hodin: 0
Počet dní: 302
Celkový počet dní: 302
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)