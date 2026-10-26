---
title: TimeSpan
second_title: Aspose.Slides per C++ Riferimento API
description: "Rappresenta un intervallo di tempo. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 1314
url: /it/system/timespan/
---
## TimeSpan classe

Rappresenta un intervallo di tempo. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
class TimeSpan
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Restituisce una nuova istanza della classe [TimeSpan](./) che rappresenta un intervallo di tempo che è la somma degli intervalli di tempo rappresentati dall'oggetto corrente e da quello specificato. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Confronta due oggetti [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Confronta l'oggetto corrente con quello specificato. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Confronta l'oggetto corrente con quello specificato. |
| [TimeSpan](./) [Duration](./duration/)() const | Restituisce una nuova istanza di [TimeSpan](./) il cui valore è il valore assoluto dell'oggetto corrente. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Determina se l'intervallo di tempo rappresentato dall'oggetto corrente è uguale all'intervallo di tempo rappresentato dall'oggetto specificato. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina se l'intervallo di tempo rappresentato dall'oggetto corrente è uguale all'intervallo di tempo rappresentato dall'oggetto specificato. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Restituisce true se gli oggetti specificati rappresentano lo stesso intervallo di tempo, altrimenti false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Restituisce un nuovo oggetto [TimeSpan](./) che rappresenta l'intervallo specificato. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Restituisce un nuovo oggetto [TimeSpan](./) che rappresenta l'intervallo specificato. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Restituisce un nuovo oggetto [TimeSpan](./) che rappresenta l'intervallo specificato. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Restituisce un nuovo oggetto [TimeSpan](./) che rappresenta l'intervallo specificato. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Restituisce un nuovo oggetto [TimeSpan](./) che rappresenta l'intervallo specificato. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Restituisce un nuovo oggetto [TimeSpan](./) che rappresenta l'intervallo specificato. |
| constexpr int [get_Days](./get_days/)() const | Restituisce la componente giorni dell'intervallo di tempo rappresentato dall'oggetto [TimeSpan](./) corrente. |
| constexpr int [get_Hours](./get_hours/)() const | Restituisce la componente ore dell'intervallo di tempo rappresentato dall'oggetto [TimeSpan](./) corrente. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Restituisce la componente millisecondi dell'intervallo di tempo rappresentato dall'oggetto [TimeSpan](./) corrente. |
| constexpr int [get_Minutes](./get_minutes/)() const | Restituisce la componente minuti dell'intervallo di tempo rappresentato dall'oggetto [TimeSpan](./) corrente. |
| constexpr int [get_Seconds](./get_seconds/)() const | Restituisce la componente secondi dell'intervallo di tempo rappresentato dall'oggetto [TimeSpan](./) corrente. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Restituisce il numero di intervalli di 100 nanosecondi che costituiscono l'intervallo di tempo rappresentato dall'oggetto [TimeSpan](./) corrente. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Restituisce il valore dell'oggetto [TimeSpan](./) corrente espresso in giorni interi e frazionari. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Restituisce il valore dell'oggetto [TimeSpan](./) corrente espresso in ore intere e frazionarie. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Restituisce il valore dell'oggetto [TimeSpan](./) corrente espresso in millisecondi interi e frazionari. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Restituisce il valore dell'oggetto [TimeSpan](./) corrente espresso in minuti interi e frazionari. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Restituisce il valore dell'oggetto [TimeSpan](./) corrente espresso in secondi interi e frazionari. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Restituisce una nuova istanza di [TimeSpan](./) che rappresenta il valore negato dell'oggetto [TimeSpan](./) corrente. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Determina se l'intervallo di tempo rappresentato dall'oggetto corrente non è uguale all'intervallo di tempo rappresentato dall'oggetto specificato. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Restituisce una nuova istanza della classe [TimeSpan](./) che rappresenta un intervallo di tempo che è la somma degli intervalli di tempo rappresentati dall'oggetto corrente e da quello specificato. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Restituisce se stesso. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Assegna all'oggetto corrente l'intervallo di tempo che è la somma dell'intervallo di tempo rappresentato dall'oggetto corrente e da quello specificato. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Restituisce una nuova istanza della classe [TimeSpan](./) che rappresenta un intervallo di tempo risultato della sottrazione dell'intervallo di tempo rappresentato dall'oggetto specificato dall'intervallo di tempo rappresentato dall'oggetto corrente. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Restituisce una nuova istanza di [TimeSpan](./) che rappresenta il valore negato dell'oggetto [TimeSpan](./) corrente. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Assegna all'oggetto corrente l'intervallo di tempo risultato della sottrazione dell'intervallo di tempo rappresentato dall'oggetto specificato dall'intervallo di tempo rappresentato dall'oggetto corrente. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Determina se l'intervallo di tempo rappresentato dall'oggetto corrente è più breve dell'intervallo di tempo rappresentato dall'oggetto specificato. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Determina se l'intervallo di tempo rappresentato dall'oggetto corrente è più breve o uguale all'intervallo di tempo rappresentato dall'oggetto specificato. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Imposta l'intervallo di tempo rappresentato dall'oggetto [TimeSpan](./) specificato sull'oggetto [TimeSpan](./) corrente. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Determina se l'intervallo di tempo rappresentato dall'oggetto corrente è uguale all'intervallo di tempo rappresentato dall'oggetto specificato. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Determina se l'intervallo di tempo rappresentato dall'oggetto corrente è più lungo dell'intervallo di tempo rappresentato dall'oggetto specificato. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Determina se l'intervallo di tempo rappresentato dall'oggetto corrente è più lungo o uguale all'intervallo di tempo rappresentato dall'oggetto specificato. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Converte una stringa in un oggetto [TimeSpan](./) equivalente. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte una stringa in un oggetto [TimeSpan](./) equivalente usando il provider di formato specificato. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Converte una stringa in un oggetto [TimeSpan](./) equivalente usando i formati specificati, il provider di formato e gli stili. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Converte una stringa in un oggetto [TimeSpan](./) equivalente usando il formato specificato, il provider di formato e gli stili. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Restituisce una nuova istanza della classe [TimeSpan](./) che rappresenta un intervallo di tempo risultato della sottrazione dell'intervallo di tempo rappresentato dall'oggetto specificato dall'intervallo di tempo rappresentato dall'oggetto corrente. |
| constexpr [TimeSpan](./timespan/)() | Costruisce un oggetto [TimeSpan](./) che rappresenta un intervallo di tempo zero. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Costruisce un'istanza della classe [TimeSpan](./) che rappresenta l'intervallo di tempo specificato. |
|  [TimeSpan](./timespan/)(int, int, int) | Costruisce un'istanza della classe [TimeSpan](./) che rappresenta l'intervallo di tempo risultante dalla somma del numero specificato di ore, minuti e secondi. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Costruisce un'istanza della classe [TimeSpan](./) che rappresenta l'intervallo di tempo risultante dalla somma del numero specificato di ore, minuti, secondi e millisecondi. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Costruisce un oggetto [TimeSpan](./) che rappresenta l'intervallo di tempo uguale all'intervallo di tempo rappresentato dall'oggetto [TimeSpan](./) specificato. |
| [String](../string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa dell'intervallo di tempo rappresentato dall'oggetto corrente. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converte il valore dell'oggetto corrente in una rappresentazione stringa equivalente, usando il formato specificato. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte il valore dell'oggetto corrente in una rappresentazione stringa equivalente, usando il formato e il provider di formato specificati. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Converte una stringa in un oggetto [TimeSpan](./) equivalente e restituisce il risultato della conversione. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converte una stringa in un oggetto [TimeSpan](./) equivalente usando il provider di formato specificato e restituisce il risultato della conversione. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converte una stringa in un oggetto [TimeSpan](./) equivalente usando i formati specificati e il provider di formato, e restituisce il risultato della conversione. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Converte una stringa in un oggetto [TimeSpan](./) equivalente usando il formato specificato, il provider di formato e gli stili, e restituisce il risultato della conversione. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Converte una stringa in un oggetto [TimeSpan](./) equivalente usando i formati specificati, il provider di formato e gli stili, e restituisce il risultato della conversione. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converte una stringa in un oggetto [TimeSpan](./) equivalente usando il formato e il provider di formato specificati, e restituisce il risultato della conversione. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Restituisce un oggetto [TypeInfo](../typeinfo/) che rappresenta la struttura [TimeSpan](./). |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [MaxValue](./maxvalue/) | L'oggetto [TimeSpan](./) che rappresenta l'intervallo più lungo possibile. |
| static [MinValue](./minvalue/) | /// L'oggetto [TimeSpan](./) che rappresenta l'intervallo più breve possibile. |
| static constexpr [TicksPerDay](./ticksperday/) | Il numero di intervalli di 100 nanosecondi in un giorno (intervallo di 24 ore). |
| static constexpr [TicksPerHour](./ticksperhour/) | Il numero di intervalli di 100 nanosecondi in un'ora. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Il numero di intervalli di 100 nanosecondi in un millisecondo. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Il numero di intervalli di 100 nanosecondi in un minuto. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Il numero di intervalli di 100 nanosecondi in un secondo. |
| static [Zero](./zero/) | L'oggetto [TimeSpan](./) che rappresenta l'intervallo zero. |

## Osservazioni

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
Questo esempio di codice produce il seguente output:
Numero di tick: 260928000000000
Numero di millisecondi: 0
Numero totale di millisecondi: 2.60928e+10
Numero di minuti: 0
Numero totale di minuti: 434880
Numero di ore: 0
Numero totale di ore: 0
Numero di giorni: 302
Numero totale di giorni: 302
*/
```

## Vedi anche

* Namespace [System](../)
* Library [Aspose.Slides](../../)