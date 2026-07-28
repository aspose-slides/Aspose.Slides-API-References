---
title: TimeSpan
second_title: Aspose.Slides a C++ API-referenciához
description: "Időintervallumot reprezentál. Ezt a típust a stack-en kell lefoglalni, és értékként vagy referencia szerint kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 1314
url: /hu/system/timespan/
---
## TimeSpan osztály


Időintervallumot reprezentál. Ezt a típust a stack-en kell lefoglalni, és értékként vagy referencia szerint kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class TimeSpan
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Visszaad egy új példányt a [TimeSpan](./) osztályból, amely egy időintervallumot reprezentál, amely a jelenlegi és a megadott objektumok által reprezentált időintervallumok összege. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Két [TimeSpan](./) objektumot hasonlít össze. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | A jelenlegi és a megadott objektumokat hasonlítja össze. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | A jelenlegi és a megadott objektumokat hasonlítja össze. |
| [TimeSpan](./) [Duration](./duration/)() const | Visszaad egy új [TimeSpan](./) objektumot, amelynek értéke a jelenlegi objektum abszolút értéke. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Megállapítja, hogy a jelenlegi objektum által reprezentált időintervallum egyenlő-e a megadott objektum által reprezentált időintervallummal. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Megállapítja, hogy a jelenlegi objektum által reprezentált időintervallum egyenlő-e a megadott objektum által reprezentált időintervallummal. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Igaz értéket ad vissza, ha a megadott objektumok ugyanazt az időintervallumot reprezentálják, egyébként hamis. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Visszaad egy új [TimeSpan](./) objektumot, amely a megadott intervallumot reprezentál. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Visszaad egy új [TimeSpan](./) objektumot, amely a megadott intervallumot reprezentál. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Visszaad egy új [TimeSpan](./) objektumot, amely a megadott intervallumot reprezentál. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Visszaad egy új [TimeSpan](./) objektumot, amely a megadott intervallumot reprezentál. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Visszaad egy új [TimeSpan](./) objektumot, amely a megadott intervallumot reprezentál. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Visszaad egy új [TimeSpan](./) objektumot, amely a megadott intervallumot reprezentál. |
| constexpr int [get_Days](./get_days/)() const | Visszaadja a napok komponensét a jelenlegi [TimeSpan](./) objektum által reprezentált időintervallumból. |
| constexpr int [get_Hours](./get_hours/)() const | Visszaadja az órák komponensét a jelenlegi [TimeSpan](./) objektum által reprezentált időintervallumból. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Visszaadja a ezredmásodpercek komponensét a jelenlegi [TimeSpan](./) objektum által reprezentált időintervallumból. |
| constexpr int [get_Minutes](./get_minutes/)() const | Visszaadja a percek komponensét a jelenlegi [TimeSpan](./) objektum által reprezentált időintervallumból. |
| constexpr int [get_Seconds](./get_seconds/)() const | Visszaadja a másodpercek komponensét a jelenlegi [TimeSpan](./) objektum által reprezentált időintervallumból. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Visszaadja a 100 nanomásodperces intervallumok számát, amelyek a jelenlegi [TimeSpan](./) objektum által reprezentált időintervallumot alkotják. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Visszaadja a jelenlegi [TimeSpan](./) objektum értékét egész és tört napokban kifejezve. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Visszaadja a jelenlegi [TimeSpan](./) objektum értékét egész és tört órákban kifejezve. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Visszaadja a jelenlegi [TimeSpan](./) objektum értékét egész és tört ezredmásodpercekben kifejezve. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Visszaadja a jelenlegi [TimeSpan](./) objektum értékét egész és tört percekben kifejezve. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Visszaadja a jelenlegi [TimeSpan](./) objektum értékét egész és tört másodpercekben kifejezve. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumhoz. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Visszaad egy új [TimeSpan](./) objektumot, amely a jelenlegi [TimeSpan](./) objektum által reprezentált érték negálását tartalmazza. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Megállapítja, hogy a jelenlegi objektum által reprezentált időintervallum nem egyenlő-e a megadott objektum által reprezentált időintervallummal. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Visszaad egy új [TimeSpan](./) osztályból származó példányt, amely egy időintervallumot reprezentál, amely a jelenlegi és a megadott objektumok által reprezentált időintervallumok összege. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Visszaadja önmagát. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | A jelenlegi objektumhoz rendeli azt az időintervallumot, amely a jelenlegi és a megadott objektumok által reprezentált időintervallumok összege. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Visszaad egy új [TimeSpan](./) osztályból származó példányt, amely egy időintervallumot reprezentál, amely a megadott objektum által reprezentált időintervallum kivonásának eredménye a jelenlegi objektum által reprezentált időintervallumból. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Visszaad egy új [TimeSpan](./) objektumot, amely a jelenlegi [TimeSpan](./) objektum által reprezentált érték negálását tartalmazza. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | A jelenlegi objektumhoz rendeli azt az időintervallumot, amely a megadott objektum által reprezentált időintervallum kivonásának eredménye a jelenlegi objektum által reprezentált időintervallumból. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Megállapítja, hogy a jelenlegi objektum által reprezentált időintervallum rövidebb-e a megadott objektum által reprezentált időintervallumnál. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Megállapítja, hogy a jelenlegi objektum által reprezentált időintervallum rövidebb vagy egyenlő-e a megadott objektum által reprezentált időintervallummal. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Beállítja a megadott [TimeSpan](./) objektum által reprezentált időintervallumot a jelenlegi [TimeSpan](./) objektumra. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Megállapítja, hogy a jelenlegi objektum által reprezentált időintervallum egyenlő-e a megadott objektum által reprezentált időintervallummal. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Megállapítja, hogy a jelenlegi objektum által reprezentált időintervallum hosszabb-e a megadott objektum által reprezentált időintervallumnál. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Megállapítja, hogy a jelenlegi objektum által reprezentált időintervallum hosszabb vagy egyenlő-e a megadott objektum által reprezentált időintervallummal. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá a megadott formátum-szolgáltató használatával. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá a megadott formátumok, formátum-szolgáltató és stílusok használatával. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá a megadott formátum, formátum-szolgáltató és stílusok használatával. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Visszaad egy új [TimeSpan](./) osztályból származó példányt, amely egy időintervallumot reprezentál, amely a megadott objektum által reprezentált időintervallum kivonásának eredménye a jelenlegi objektum által reprezentált időintervallumból. |
| constexpr [TimeSpan](./timespan/)() | Létrehoz egy [TimeSpan](./) objektumot, amely egy nulla időintervallumot reprezentál. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Létrehoz egy [TimeSpan](./) osztályból származó példányt, amely a megadott időintervallumot reprezentálja. |
| [TimeSpan](./timespan/)(int, int, int) | Létrehoz egy [TimeSpan](./) osztályból származó példányt, amely egy olyan időintervallumot reprezentál, amely a megadott órák, percek és másodpercek összegével egyenlő. |
| [TimeSpan](./timespan/)(int, int, int, int, int) | Létrehoz egy [TimeSpan](./) osztályból származó példányt, amely egy olyan időintervallumot reprezentál, amely a megadott órák, percek, másodpercek és ezredmásodpercek összegével egyenlő. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Létrehoz egy [TimeSpan](./) objektumot, amely egy olyan időintervallumot reprezentál, amely egyenlő a megadott [TimeSpan](./) objektum által reprezentált időintervallummal. |
| [String](../string/) [ToString](./tostring/)() const | Visszaadja a jelenlegi objektum által reprezentált időintervallum karakterlánc ábrázolását. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Átalakítja a jelenlegi objektum értékét egy megfelelő karakterlánc ábrázolássá a megadott formátum használatával. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Átalakítja a jelenlegi objektum értékét egy megfelelő karakterlánc ábrázolássá a megadott formátum és formátum-szolgáltató használatával. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá és visszaadja a konverzió eredményét. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá a megadott formátum-szolgáltató használatával, és visszaadja a konverzió eredményét. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá a megadott formátumok és formátum-szolgáltató használatával, és visszaadja a konverzió eredményét. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá a megadott formátum, formátum-szolgáltató és stílusok használatával, és visszaadja a konverzió eredményét. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá a megadott formátumok, formátum-szolgáltató és stílusok használatával, és visszaadja a konverzió eredményét. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Átalakítja a karakterláncot a megfelelő [TimeSpan](./) objektummá a megadott formátum és formátum-szolgáltató használatával, és visszaadja a konverzió eredményét. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Visszaad egy [TypeInfo](../typeinfo/) objektumot, amely a [TimeSpan](./) struktúrát reprezentálja. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [MaxValue](./maxvalue/) | A [TimeSpan](./) objektum, amely a leghosszabb lehetséges intervallumot reprezentálja. |
| static [MinValue](./minvalue/) | /// A [TimeSpan](./) objektum, amely a legrövidebb lehetséges intervallumot reprezentálja. |
| static constexpr [TicksPerDay](./ticksperday/) | Egy napban (24-órás intervallumban) lévő 100 nanomásodperces intervallumok száma. |
| static constexpr [TicksPerHour](./ticksperhour/) | Egy órában lévő 100 nanomásodperces intervallumok száma. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Egy ezredmásodpercben lévő 100 nanomásodperces intervallumok száma. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Egy percben lévő 100 nanomásodperces intervallumok száma. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Egy másodpercben lévő 100 nanomásodperces intervallumok száma. |
| static [Zero](./zero/) | A [TimeSpan](./) objektum, amely a nulla intervallumot reprezentálja. |

## Megjegyzések

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
Ez a kódpélda a következő kimenetet állítja elő:
A tickek száma: 260928000000000
A ezredmásodpercek száma: 0
Az összes ezredmásodperc száma: 2.60928e+10
A percek száma: 0
Az összes perc száma: 434880
A órák száma: 0
Az összes óra száma: 0
A napok száma: 302
Az összes nap száma: 302
*/
```

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)