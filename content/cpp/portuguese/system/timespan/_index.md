---
title: TimeSpan
second_title: Aspose.Slides para C++ Referência da API
description: "Representa um intervalo de tempo. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos deste tipo."
type: docs
weight: 1314
url: /pt/system/timespan/
---
## TimeSpan classe

Representa um intervalo de tempo. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos deste tipo.

```cpp
class TimeSpan
```

## Métodos

| Método | Descrição |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Retorna uma nova instância da [TimeSpan](./) classe que representa um intervalo de tempo que é a soma dos intervalos de tempo representados pelo objeto atual e pelos objetos especificados. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Compara dois [TimeSpan](./) objetos. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Compara o objeto atual e os objetos especificados. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Compara o objeto atual e os objetos especificados. |
| [TimeSpan](./) [Duration](./duration/)() const | Retorna uma nova instância do objeto [TimeSpan](./) cujo valor é o valor absoluto do objeto atual. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Determina se o intervalo de tempo representado pelo objeto atual é igual ao intervalo de tempo representado pelo objeto especificado. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina se o intervalo de tempo representado pelo objeto atual é igual ao intervalo de tempo representado pelo objeto especificado. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Retorna true se os objetos especificados representam o mesmo intervalo de tempo, caso contrário - false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Retorna um novo objeto [TimeSpan](./) que representa o intervalo especificado. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Retorna um novo objeto [TimeSpan](./) que representa o intervalo especificado. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Retorna um novo objeto [TimeSpan](./) que representa o intervalo especificado. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Retorna um novo objeto [TimeSpan](./) que representa o intervalo especificado. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Retorna um novo objeto [TimeSpan](./) que representa o intervalo especificado. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Retorna um novo objeto [TimeSpan](./) que representa o intervalo especificado. |
| constexpr int [get_Days](./get_days/)() const | Retorna o componente de dias do intervalo de tempo representado pelo objeto [TimeSpan](./) atual. |
| constexpr int [get_Hours](./get_hours/)() const | Retorna o componente de horas do intervalo de tempo representado pelo objeto [TimeSpan](./) atual. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Retorna o componente de milissegundos do intervalo de tempo representado pelo objeto [TimeSpan](./) atual. |
| constexpr int [get_Minutes](./get_minutes/)() const | Retorna o componente de minutos do intervalo de tempo representado pelo objeto [TimeSpan](./) atual. |
| constexpr int [get_Seconds](./get_seconds/)() const | Retorna o componente de segundos do intervalo de tempo representado pelo objeto [TimeSpan](./) atual. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Retorna o número de intervalos de 100 nanossegundos que constituem o intervalo de tempo representado pelo objeto [TimeSpan](./) atual. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Retorna o valor do objeto [TimeSpan](./) atual expresso em dias inteiros e fracionários. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Retorna o valor do objeto [TimeSpan](./) atual expresso em horas inteiras e fracionárias. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Retorna o valor do objeto [TimeSpan](./) atual expresso em milissegundos inteiros e fracionários. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Retorna o valor do objeto [TimeSpan](./) atual expresso em minutos inteiros e fracionários. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Retorna o valor do objeto [TimeSpan](./) atual expresso em segundos inteiros e fracionários. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Retorna uma nova instância do objeto [TimeSpan](./) que representa o valor negado representado pelo objeto [TimeSpan](./) atual. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Determina se o intervalo de tempo representado pelo objeto atual não é igual ao intervalo de tempo representado pelo objeto especificado. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Retorna uma nova instância da classe [TimeSpan](./) que representa um intervalo de tempo que é a soma dos intervalos de tempo representados pelo objeto atual e pelos objetos especificados. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Retorna a si mesmo. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Atribui ao objeto atual o intervalo de tempo que é a soma do intervalo de tempo representado pelo objeto atual e pelos objetos especificados. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Retorna uma nova instância da classe [TimeSpan](./) que representa um intervalo de tempo que resulta da subtração do intervalo de tempo representado pelo objeto especificado do intervalo de tempo representado pelo objeto atual. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Retorna uma nova instância do objeto [TimeSpan](./) que representa o valor negado representado pelo objeto [TimeSpan](./) atual. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Atribui ao objeto atual o intervalo de tempo que resulta da subtração do intervalo de tempo representado pelo objeto especificado do intervalo de tempo representado pelo objeto atual. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Determina se o intervalo de tempo representado pelo objeto atual é mais curto que o intervalo de tempo representado pelo objeto especificado. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Determina se o intervalo de tempo representado pelo objeto atual é mais curto ou igual ao intervalo de tempo representado pelo objeto especificado. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Define o intervalo de tempo representado pelo objeto [TimeSpan](./) especificado para o objeto [TimeSpan](./) atual. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Determina se o intervalo de tempo representado pelo objeto atual é igual ao intervalo de tempo representado pelo objeto especificado. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Determina se o intervalo de tempo representado pelo objeto atual é mais longo que o intervalo de tempo representado pelo objeto especificado. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Determina se o intervalo de tempo representado pelo objeto atual é mais longo ou igual ao intervalo de tempo representado pelo objeto especificado. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Converte string para objeto [TimeSpan](./) equivalente. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte string para objeto [TimeSpan](./) equivalente usando o provedor de formato especificado. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Converte string para objeto [TimeSpan](./) equivalente usando os formatos especificados, provedor de formato e estilos. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Converte string para objeto [TimeSpan](./) equivalente usando o formato especificado, provedor de formato e estilos. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Retorna uma nova instância da classe [TimeSpan](./) que representa um intervalo de tempo que é o resultado da subtração do intervalo de tempo representado pelo objeto especificado do intervalo de tempo representado pelo objeto atual. |
| constexpr [TimeSpan](./timespan/)() | Constrói um objeto [TimeSpan](./) que representa um intervalo de tempo zero. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Constrói uma instância da classe [TimeSpan](./) que representa o intervalo de tempo especificado. |
|  [TimeSpan](./timespan/)(int, int, int) | Constrói uma instância da classe [TimeSpan](./) que representa o intervalo de tempo que é igual à soma do número especificado de horas, minutos e segundos. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Constrói uma instância da classe [TimeSpan](./) que representa o intervalo de tempo que é igual à soma do número especificado de horas, minutos, segundos e milissegundos. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Constrói um objeto [TimeSpan](./) que representa o intervalo de tempo igual ao intervalo de tempo representado pelo objeto [TimeSpan](./) especificado. |
| [String](../string/) [ToString](./tostring/)() const | Retorna a representação em string do intervalo de tempo representado pelo objeto atual. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converte o valor do objeto atual para uma representação em string equivalente, usando o formato especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte o valor do objeto atual para uma representação em string equivalente, usando o formato e o provedor de formato especificados. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Converte string para objeto [TimeSpan](./) equivalente e retorna o resultado da conversão. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converte string para objeto [TimeSpan](./) equivalente usando o provedor de formato especificado e retorna o resultado da conversão. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converte string para objeto [TimeSpan](./) equivalente usando os formatos e o provedor de formato especificados, e retorna o resultado da conversão. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Converte string para objeto [TimeSpan](./) equivalente usando o formato, provedor de formato e estilos especificados, e retorna o resultado da conversão. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Converte string para objeto [TimeSpan](./) equivalente usando os formatos, provedor de formato e estilos especificados, e retorna o resultado da conversão. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Converte string para objeto [TimeSpan](./) equivalente usando o formato e o provedor de formato especificados, e retorna o resultado da conversão. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retorna um objeto [TypeInfo](../typeinfo/) que representa a estrutura [TimeSpan](./). |

## Campos

| Campo | Descrição |
| --- | --- |
| static [MaxValue](./maxvalue/) | O objeto [TimeSpan](./) que representa o intervalo mais longo possível. |
| static [MinValue](./minvalue/) | /// O objeto [TimeSpan](./) que representa o intervalo mais curto possível. |
| static constexpr [TicksPerDay](./ticksperday/) | O número de intervalos de 100 nanossegundos em um dia (intervalo de 24 horas). |
| static constexpr [TicksPerHour](./ticksperhour/) | O número de intervalos de 100 nanossegundos em uma hora. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | O número de intervalos de 100 nanossegundos em um milissegundo. |
| static constexpr [TicksPerMinute](./ticksperminute/) | O número de intervalos de 100 nanossegundos em um minuto. |
| static constexpr [TicksPerSecond](./tickspersecond/) | O número de intervalos de 100 nanossegundos em um segundo. |
| static [Zero](./zero/) | O objeto [TimeSpan](./) que representa um intervalo zero. |

## Observações

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
Este exemplo de código produz a seguinte saída:
Número de ticks: 260928000000000
Número de milissegundos: 0
Número total de milissegundos: 2.60928e+10
Número de minutos: 0
Número total de minutos: 434880
Número de horas: 0
Número total de horas: 0
Número de dias: 302
Número total de dias: 302
*/
```

## Veja Também

* namespace [System](../)
* biblioteca [Aspose.Slides](../../)