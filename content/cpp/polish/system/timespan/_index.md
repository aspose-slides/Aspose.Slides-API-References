---
title: TimeSpan
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Reprezentuje przedział czasu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 1314
url: /pl/system/timespan/
---
## TimeSpan klasa

Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class TimeSpan
```

## Metody

| Metoda | Opis |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Zwraca nową instancję klasy [TimeSpan](./), która reprezentuje przedział czasu będący sumą przedziałów czasu reprezentowanych przez bieżący oraz określony obiekt. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Porównuje dwa obiekty [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Porównuje bieżący i określony obiekt. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Porównuje bieżący i określony obiekt. |
| [TimeSpan](./) [Duration](./duration/)() const | Zwraca nową instancję obiektu [TimeSpan](./), którego wartość jest wartością bezwzględną bieżącego obiektu. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Określa, czy przedział czasu reprezentowany przez bieżący obiekt jest równy przedziałowi czasu reprezentowanemu przez określony obiekt. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Określa, czy przedział czasu reprezentowany przez bieżący obiekt jest równy przedziałowi czasu reprezentowanemu przez określony obiekt. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Zwraca true, jeśli określone obiekty reprezentują ten sam przedział czasu, w przeciwnym razie - false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Zwraca nowy obiekt [TimeSpan](./), który reprezentuje określony przedział. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Zwraca nowy obiekt [TimeSpan](./), który reprezentuje określony przedział. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Zwraca nowy obiekt [TimeSpan](./), który reprezentuje określony przedział. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Zwraca nowy obiekt [TimeSpan](./), który reprezentuje określony przedział. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Zwraca nowy obiekt [TimeSpan](./), który reprezentuje określony przedział. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Zwraca nowy obiekt [TimeSpan](./), który reprezentuje określony przedział. |
| constexpr int [get_Days](./get_days/)() const | Zwraca komponent dni przedziału czasu reprezentowanego przez bieżący obiekt [TimeSpan](./). |
| constexpr int [get_Hours](./get_hours/)() const | Zwraca komponent godzin przedziału czasu reprezentowanego przez bieżący obiekt [TimeSpan](./). |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Zwraca komponent milisekund przedziału czasu reprezentowanego przez bieżący obiekt [TimeSpan](./). |
| constexpr int [get_Minutes](./get_minutes/)() const | Zwraca komponent minut przedziału czasu reprezentowanego przez bieżący obiekt [TimeSpan](./). |
| constexpr int [get_Seconds](./get_seconds/)() const | Zwraca komponent sekund przedziału czasu reprezentowanego przez bieżący obiekt [TimeSpan](./). |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Zwraca liczbę interwałów 100-nanosekundowych, które tworzą przedział czasu reprezentowany przez bieżący obiekt [TimeSpan](./). |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Zwraca wartość bieżącego obiektu [TimeSpan](./) wyrażoną w pełnych i ułamkowych dniach. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Zwraca wartość bieżącego obiektu [TimeSpan](./) wyrażoną w pełnych i ułamkowych godzinach. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Zwraca wartość bieżącego obiektu [TimeSpan](./) wyrażoną w pełnych i ułamkowych milisekundach. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Zwraca wartość bieżącego obiektu [TimeSpan](./) wyrażoną w pełnych i ułamkowych minutach. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Zwraca wartość bieżącego obiektu [TimeSpan](./) wyrażoną w pełnych i ułamkowych sekundach. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu (hash) dla bieżącego obiektu. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Zwraca nową instancję obiektu [TimeSpan](./), który reprezentuje zanegowaną wartość reprezentowaną przez bieżący obiekt [TimeSpan](./). |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Określa, czy przedział czasu reprezentowany przez bieżący obiekt nie jest równy przedziałowi czasu reprezentowanemu przez określony obiekt. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Zwraca nową instancję klasy [TimeSpan](./), która reprezentuje przedział czasu będący sumą przedziałów czasu reprezentowanych przez bieżący i określony obiekt. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Zwraca siebie. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Przypisuje bieżącemu obiektowi przedział czasu będący sumą przedziału czasu reprezentowanego przez bieżący i określony obiekt. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Zwraca nową instancję klasy [TimeSpan](./), która reprezentuje przedział czasu będący wynikiem odjęcia przedziału czasu reprezentowanego przez określony obiekt od przedziału czasu reprezentowanego przez bieżący obiekt. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Zwraca nową instancję obiektu [TimeSpan](./), który reprezentuje zanegowaną wartość reprezentowaną przez bieżący obiekt [TimeSpan](./). |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Przypisuje bieżącemu obiektowi przedział czasu będący wynikiem odjęcia przedziału czasu reprezentowanego przez określony obiekt od przedziału czasu reprezentowanego przez bieżący obiekt. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Określa, czy przedział czasu reprezentowany przez bieżący obiekt jest krótszy niż przedział czasu reprezentowany przez określony obiekt. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Określa, czy przedział czasu reprezentowany przez bieżący obiekt jest krótszy lub równy przedziałowi czasu reprezentowanemu przez określony obiekt. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Ustawia przedział czasu reprezentowany przez określony obiekt [TimeSpan](./) na bieżący obiekt [TimeSpan](./). |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Określa, czy przedział czasu reprezentowany przez bieżący obiekt jest równy przedziałowi czasu reprezentowanemu przez określony obiekt. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Określa, czy przedział czasu reprezentowany przez bieżący obiekt jest dłuższy niż przedział czasu reprezentowany przez określony obiekt. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Określa, czy przedział czasu reprezentowany przez bieżący obiekt jest dłuższy lub równy przedziałowi czasu reprezentowanemu przez określony obiekt. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./). |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) przy użyciu określonego dostawcy formatu. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) przy użyciu określonych formatów, dostawcy formatu oraz stylów. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) przy użyciu określonego formatu, dostawcy formatu i stylów. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Zwraca nową instancję klasy [TimeSpan](./), która reprezentuje przedział czasu będący wynikiem odjęcia przedziału czasu reprezentowanego przez określony obiekt od przedziału czasu reprezentowanego przez bieżący obiekt. |
| constexpr [TimeSpan](./timespan/)() | Tworzy obiekt [TimeSpan](./), który reprezentuje zerowy przedział czasu. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Tworzy instancję klasy [TimeSpan](./), która reprezentuje określony przedział czasu. |
|  [TimeSpan](./timespan/)(int, int, int) | Tworzy instancję klasy [TimeSpan](./), która reprezentuje przedział czasu równy sumie określonej liczby godzin, minut i sekund. |
|   [TimeSpan](./timespan/)(int, int, int, int, int) | Tworzy instancję klasy [TimeSpan](./), która reprezentuje przedział czasu równy sumie określonej liczby godzin, minut, sekund i milisekund. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Tworzy obiekt [TimeSpan](./), który reprezentuje przedział czasu równy przedziałowi czasu reprezentowanemu przez określony obiekt [TimeSpan](./). |
| [String](../string/) [ToString](./tostring/)() const | Zwraca tekstową reprezentację przedziału czasu reprezentowanego przez bieżący obiekt. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konwertuje wartość bieżącego obiektu na równoważną reprezentację tekstową, używając określonego formatu. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konwertuje wartość bieżącego obiektu na równoważną reprezentację tekstową, używając określonego formatu i dostawcy formatu. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) i zwraca wynik konwersji. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) przy użyciu określonego dostawcy formatu i zwraca wynik konwersji. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) przy użyciu określonych formatów i dostawcy formatu oraz zwraca wynik konwersji. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) przy użyciu określonego formatu, dostawcy formatu i stylów oraz zwraca wynik konwersji. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) przy użyciu określonych formatów, dostawcy formatu i stylów oraz zwraca wynik konwersji. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](./) przy użyciu określonego formatu i dostawcy formatu oraz zwraca wynik konwersji. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Zwraca obiekt [TypeInfo](../typeinfo/), który reprezentuje strukturę [TimeSpan](./). |

## Pola

| Pole | Opis |
| --- | --- |
| static [MaxValue](./maxvalue/) | Obiekt [TimeSpan](./) reprezentujący najdłuższy możliwy przedział. |
| static [MinValue](./minvalue/) | /// Obiekt [TimeSpan](./) reprezentujący najkrótszy możliwy przedział. |
| static constexpr [TicksPerDay](./ticksperday/) | Liczba interwałów 100-nanosekundowych w dniu (przedział 24-godzinny). |
| static constexpr [TicksPerHour](./ticksperhour/) | Liczba interwałów 100-nanosekundowych w godzinie. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Liczba interwałów 100-nanosekundowych w milisekundzie. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Liczba interwałów 100-nanosekundowych w minucie. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Liczba interwałów 100-nanosekundowych w sekundzie. |
| static [Zero](./zero/) | Obiekt [TimeSpan](./) reprezentujący przedział zerowy. |

## Uwagi

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
Ten przykład kodu generuje następujący wynik:
Liczba tików: 260928000000000
Liczba milisekund: 0
Całkowita liczba milisekund: 2.60928e+10
Liczba minut: 0
Całkowita liczba minut: 434880
Liczba godzin: 0
Całkowita liczba godzin: 0
Liczba dni: 302
Całkowita liczba dni: 302
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)