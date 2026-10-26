---
title: TimeSpan
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt ein Zeitintervall dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr-Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 1314
url: /de/system/timespan/
---
## TimeSpan Klasse

Stellt ein Zeitintervall dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/)-Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class TimeSpan
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Gibt eine neue Instanz der [TimeSpan](./)-Klasse zurück, die ein Zeitintervall darstellt, das die Summe der von dem aktuellen und dem angegebenen Objekt dargestellten Zeitintervalle ist. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Vergleicht zwei [TimeSpan](./)-Objekte. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Vergleicht das aktuelle und das angegebene Objekt. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Vergleicht das aktuelle und das angegebene Objekt. |
| [TimeSpan](./) [Duration](./duration/)() const | Gibt eine neue Instanz des [TimeSpan](./)-Objekts zurück, dessen Wert den absoluten Wert des aktuellen Objekts darstellt. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Bestimmt, ob das vom aktuellen Objekt dargestellte Zeitintervall gleich dem vom angegebenen Objekt dargestellten Zeitintervall ist. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Bestimmt, ob das vom aktuellen Objekt dargestellte Zeitintervall gleich dem vom angegebenen Objekt dargestellten Zeitintervall ist. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Gibt true zurück, wenn die angegebenen Objekte dasselbe Zeitintervall darstellen, andernfalls false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Gibt ein neues [TimeSpan](./)-Objekt zurück, das das angegebene Intervall darstellt. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Gibt ein neues [TimeSpan](./)-Objekt zurück, das das angegebene Intervall darstellt. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Gibt ein neues [TimeSpan](./)-Objekt zurück, das das angegebene Intervall darstellt. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Gibt ein neues [TimeSpan](./)-Objekt zurück, das das angegebene Intervall darstellt. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Gibt ein neues [TimeSpan](./)-Objekt zurück, das das angegebene Intervall darstellt. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Gibt ein neues [TimeSpan](./)-Objekt zurück, das das angegebene Intervall darstellt. |
| constexpr int [get_Days](./get_days/)() const | Gibt den Tagesanteil des vom aktuellen [TimeSpan](./)-Objekt dargestellten Zeitintervalls zurück. |
| constexpr int [get_Hours](./get_hours/)() const | Gibt den Stundenanteil des vom aktuellen [TimeSpan](./)-Objekt dargestellten Zeitintervalls zurück. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Gibt den Millisekunden-Anteilswert des vom aktuellen [TimeSpan](./)-Objekt dargestellten Zeitintervalls zurück. |
| constexpr int [get_Minutes](./get_minutes/)() const | Gibt den Minutenanteil des vom aktuellen [TimeSpan](./)-Objekt dargestellten Zeitintervalls zurück. |
| constexpr int [get_Seconds](./get_seconds/)() const | Gibt den Sekundenanteil des vom aktuellen [TimeSpan](./)-Objekt dargestellten Zeitintervalls zurück. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Gibt die Anzahl der 100-Nanosekunden-Intervalle zurück, aus denen das vom aktuellen [TimeSpan](./)-Objekt dargestellte Zeitintervall besteht. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Gibt den Wert des aktuellen [TimeSpan](./)-Objekts in ganzen und fraktionalen Tagen zurück. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Gibt den Wert des aktuellen [TimeSpan](./)-Objekts in ganzen und fraktionalen Stunden zurück. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Gibt den Wert des aktuellen [TimeSpan](./)-Objekts in ganzen und fraktionalen Millisekunden zurück. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Gibt den Wert des aktuellen [TimeSpan](./)-Objekts in ganzen und fraktionalen Minuten zurück. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Gibt den Wert des aktuellen [TimeSpan](./)-Objekts in ganzen und fraktionalen Sekunden zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code für das aktuelle Objekt zurück. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Gibt eine neue Instanz des [TimeSpan](./)-Objekts zurück, das den negierten Wert des aktuellen [TimeSpan](./)-Objekts darstellt. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Bestimmt, ob das vom aktuellen Objekt dargestellte Zeitintervall ungleich dem vom angegebenen Objekt dargestellten Zeitintervall ist. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Gibt eine neue Instanz der [TimeSpan](./)-Klasse zurück, die ein Zeitintervall darstellt, das die Summe der von dem aktuellen und dem angegebenen Objekt dargestellten Zeitintervalle ist. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Gibt sich selbst zurück. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Weist dem aktuellen Objekt das Zeitintervall zu, das die Summe der vom aktuellen und vom angegebenen Objekt dargestellten Zeitintervalle ist. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Gibt eine neue Instanz der [TimeSpan](./)-Klasse zurück, die ein Zeitintervall darstellt, das das Ergebnis der Subtraktion des vom angegebenen Objekt dargestellten Zeitintervalls vom vom aktuellen Objekt dargestellten Zeitintervall ist. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Gibt eine neue Instanz des [TimeSpan](./)-Objekts zurück, das den negierten Wert des aktuellen [TimeSpan](./)-Objekts darstellt. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Weist dem aktuellen Objekt das Zeitintervall zu, das das Ergebnis der Subtraktion des vom angegebenen Objekt dargestellten Zeitintervalls vom vom aktuellen Objekt dargestellten Zeitintervall ist. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Bestimmt, ob das vom aktuellen Objekt dargestellte Zeitintervall kürzer ist als das vom angegebenen Objekt dargestellte Zeitintervall. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Bestimmt, ob das vom aktuellen Objekt dargestellte Zeitintervall kürzer oder gleich dem vom angegebenen Objekt dargestellten Zeitintervall ist. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Setzt das vom angegebenen [TimeSpan](./)-Objekt dargestellte Zeitintervall auf das aktuelle [TimeSpan](./)-Objekt. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Bestimmt, ob das vom aktuellen Objekt dargestellte Zeitintervall gleich dem vom angegebenen Objekt dargestellten Zeitintervall ist. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Bestimmt, ob das vom aktuellen Objekt dargestellte Zeitintervall länger ist als das vom angegebenen Objekt dargestellte Zeitintervall. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Bestimmt, ob das vom aktuellen Objekt dargestellte Zeitintervall länger oder gleich dem vom angegebenen Objekt dargestellten Zeitintervall ist. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Konvertiert einen String in ein gleichwertiges [TimeSpan](./)-Objekt. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert einen String mithilfe des angegebenen Formatproviders in ein gleichwertiges [TimeSpan](./)-Objekt. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Konvertiert einen String mithilfe der angegebenen Formate, des Formatproviders und der Stile in ein gleichwertiges [TimeSpan](./)-Objekt. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Konvertiert einen String mithilfe des angegebenen Formats, des Formatproviders und der Stile in ein gleichwertiges [TimeSpan](./)-Objekt. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Gibt eine neue Instanz der [TimeSpan](./)-Klasse zurück, die ein Zeitintervall darstellt, das das Ergebnis der Subtraktion des vom angegebenen Objekt dargestellten Zeitintervalls vom vom aktuellen Objekt dargestellten Zeitintervall ist. |
| constexpr [TimeSpan](./timespan/)() | Konstruiert ein [TimeSpan](./)-Objekt, das ein Null-Zeitintervall darstellt. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Konstruiert eine Instanz der [TimeSpan](./)-Klasse, die das angegebene Zeitintervall darstellt. |
| [TimeSpan](./timespan/)(int, int, int) | Konstruiert eine Instanz der [TimeSpan](./)-Klasse, die ein Zeitintervall darstellt, das der Summe der angegebenen Stunden, Minuten und Sekunden entspricht. |
| [TimeSpan](./timespan/)(int, int, int, int, int) | Konstruiert eine Instanz der [TimeSpan](./)-Klasse, die ein Zeitintervall darstellt, das der Summe der angegebenen Stunden, Minuten, Sekunden und Millisekunden entspricht. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Konstruiert ein [TimeSpan](./)-Objekt, das das Zeitintervall darstellt, das dem vom angegebenen [TimeSpan](./)-Objekt dargestellten Zeitintervall entspricht. |
| [String](../string/) [ToString](./tostring/)() const | Gibt die Zeichenkettendarstellung des vom aktuellen Objekt dargestellten Zeitintervalls zurück. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konvertiert den Wert des aktuellen Objekts in eine gleichwertige Zeichenkettendarstellung unter Verwendung des angegebenen Formats. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konvertiert den Wert des aktuellen Objekts in eine gleichwertige Zeichenkettendarstellung unter Verwendung des angegebenen Formats und Formatproviders. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Konvertiert einen String in ein gleichwertiges [TimeSpan](./)-Objekt und gibt das Ergebnis der Konvertierung zurück. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konvertiert einen String mithilfe des angegebenen Formatproviders in ein gleichwertiges [TimeSpan](./)-Objekt und gibt das Ergebnis der Konvertierung zurück. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konvertiert einen String mithilfe der angegebenen Formate und des Formatproviders in ein gleichwertiges [TimeSpan](./)-Objekt und gibt das Ergebnis der Konvertierung zurück. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Konvertiert einen String mithilfe des angegebenen Formats, des Formatproviders und der Stile in ein gleichwertiges [TimeSpan](./)-Objekt und gibt das Ergebnis der Konvertierung zurück. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Konvertiert einen String mithilfe der angegebenen Formate, des Formatproviders und der Stile in ein gleichwertiges [TimeSpan](./)-Objekt und gibt das Ergebnis der Konvertierung zurück. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konvertiert einen String mithilfe des angegebenen Formats und des Formatproviders in ein gleichwertiges [TimeSpan](./)-Objekt und gibt das Ergebnis der Konvertierung zurück. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Gibt ein [TypeInfo](../typeinfo/)-Objekt zurück, das die [TimeSpan](./)-Struktur darstellt. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [MaxValue](./maxvalue/) | Das [TimeSpan](./)-Objekt, das das größtmögliche Intervall darstellt. |
| static [MinValue](./minvalue/) | /// Das [TimeSpan](./)-Objekt, das das kürzeste Intervall darstellt. |
| static constexpr [TicksPerDay](./ticksperday/) | Die Anzahl der 100-Nanosekunden-Intervalle in einem Tag (24-Stunden-Intervall). |
| static constexpr [TicksPerHour](./ticksperhour/) | Die Anzahl der 100-Nanosekunden-Intervalle in einer Stunde. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Die Anzahl der 100-Nanosekunden-Intervalle in einer Millisekunde. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Die Anzahl der 100-Nanosekunden-Intervalle in einer Minute. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Die Anzahl der 100-Nanosekunden-Intervalle in einer Sekunde. |
| static [Zero](./zero/) | Das [TimeSpan](./)-Objekt, das ein Null-Intervall darstellt. |

## Bemerkungen

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
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Anzahl der Ticks: 260928000000000
Anzahl der Millisekunden: 0
Gesamte Anzahl der Millisekunden: 2.60928e+10
Anzahl der Minuten: 0
Gesamte Anzahl der Minuten: 434880
Anzahl der Stunden: 0
Gesamte Anzahl der Stunden: 0
Anzahl der Tage: 302
Gesamte Anzahl der Tage: 302
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)