---
title: TimeSpan
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa un intervalo de tiempo. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para administrar objetos de este tipo."
type: docs
weight: 1314
url: /es/system/timespan/
---
## TimeSpan clase

Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class TimeSpan
```

## Métodos

| Método | Descripción |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Devuelve una nueva instancia de la clase [TimeSpan](./) que representa un intervalo de tiempo que es la suma de los intervalos de tiempo representados por el objeto actual y los objetos especificados. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Compara dos objetos [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Compara el actual y los objetos especificados. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Compara el actual y los objetos especificados. |
| [TimeSpan](./) [Duration](./duration/)() const | Devuelve una nueva instancia del objeto [TimeSpan](./) cuyo valor es el valor absoluto del objeto actual. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Determina si el intervalo de tiempo representado por el objeto actual es igual al intervalo de tiempo representado por el objeto especificado. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina si el intervalo de tiempo representado por el objeto actual es igual al intervalo de tiempo representado por el objeto especificado. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Devuelve true si los objetos especificados representan el mismo intervalo de tiempo, de lo contrario, false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| constexpr int [get_Days](./get_days/)() const | Returns the days component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr int [get_Hours](./get_hours/)() const | Returns the hours component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Returns the milliseconds component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr int [get_Minutes](./get_minutes/)() const | Returns the minutes component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr int [get_Seconds](./get_seconds/)() const | Returns the seconds component of the time interval represented by the current [TimeSpan](./) object. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Returns the number of 100-nanoseconds intervals that constitute the time interval represented by the current [TimeSpan](./) object. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional days. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional hours. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional milliseconds. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional minutes. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional seconds. |
| int [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Devuelve una nueva instancia del objeto [TimeSpan](./) que representa el valor negado representado por el objeto [TimeSpan](./) actual. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Determina si el intervalo de tiempo representado por el objeto actual no es igual al intervalo de tiempo representado por el objeto especificado. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Devuelve una nueva instancia de la clase [TimeSpan](./) que representa un intervalo de tiempo que es la suma de los intervalos de tiempo representados por el objeto actual y los objetos especificados. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Devuelve a sí mismo. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Asigna al objeto actual el intervalo de tiempo que es la suma del intervalo representado por el objeto actual y los objetos especificados. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Devuelve una nueva instancia de la clase [TimeSpan](./) que representa un intervalo de tiempo que es el resultado de restar el intervalo de tiempo representado por el objeto especificado del intervalo representado por el objeto actual. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Devuelve una nueva instancia del objeto [TimeSpan](./) que representa el valor negado representado por el objeto [TimeSpan](./) actual. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Asigna al objeto actual el intervalo de tiempo que es el resultado de restar el intervalo representado por el objeto especificado del intervalo representado por el objeto actual. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Determina si el intervalo de tiempo representado por el objeto actual es más corto que el intervalo representado por el objeto especificado. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Determina si el intervalo de tiempo representado por el objeto actual es más corto o igual al intervalo representado por el objeto especificado. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Establece el intervalo de tiempo representado por el objeto [TimeSpan](./) especificado al objeto [TimeSpan](./) actual. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Determina si el intervalo de tiempo representado por el objeto actual es igual al intervalo representado por el objeto especificado. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Determina si el intervalo de tiempo representado por el objeto actual es más largo que el intervalo representado por el objeto especificado. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Determina si el intervalo de tiempo representado por el objeto actual es más largo o igual al intervalo representado por el objeto especificado. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando el proveedor de formato especificado. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando los formatos especificados, el proveedor de formato y los estilos. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando el formato especificado, el proveedor de formato y los estilos. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Devuelve una nueva instancia de la clase [TimeSpan](./) que representa un intervalo de tiempo que es el resultado de restar el intervalo representado por el objeto especificado del intervalo representado por el objeto actual. |
| constexpr [TimeSpan](./timespan/)() | Construye un objeto [TimeSpan](./) que representa un intervalo de tiempo cero. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Construye una instancia de la clase [TimeSpan](./) que representa el intervalo de tiempo especificado. |
|  [TimeSpan](./timespan/)(int, int, int) | Construye una instancia de la clase [TimeSpan](./) que representa el intervalo de tiempo que es igual a la suma del número especificado de horas, minutos y segundos. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Construye una instancia de la clase [TimeSpan](./) que representa el intervalo de tiempo que es igual a la suma del número especificado de horas, minutos, segundos y milisegundos. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Construye un objeto [TimeSpan](./) que representa el intervalo de tiempo igual al intervalo representado por el objeto [TimeSpan](./) especificado. |
| [String](../string/) [ToString](./tostring/)() const | Devuelve la representación en cadena del intervalo de tiempo representado por el objeto actual. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Convierte el valor del objeto actual a su representación en cadena equivalente, usando el formato especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convierte el valor del objeto actual a su representación en cadena equivalente, usando el formato y el proveedor de formato especificados. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente y devuelve el resultado de la conversión. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando el proveedor de formato especificado y devuelve el resultado de la conversión. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando los formatos y el proveedor de formato especificados, y devuelve el resultado de la conversión. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando el formato, el proveedor de formato y los estilos especificados, y devuelve el resultado de la conversión. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando los formatos, el proveedor de formato y los estilos especificados, y devuelve el resultado de la conversión. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando el formato y el proveedor de formato especificados, y devuelve el resultado de la conversión. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Devuelve un objeto [TypeInfo](../typeinfo/) que representa la estructura [TimeSpan](./). |

## Campos

| Campo | Descripción |
| --- | --- |
| static [MaxValue](./maxvalue/) | El objeto [TimeSpan](./) que representa el intervalo más largo posible. |
| static [MinValue](./minvalue/) | /// El objeto [TimeSpan](./) que representa el intervalo más corto posible. |
| static constexpr [TicksPerDay](./ticksperday/) | El número de intervalos de 100 nanosegundos en un día (intervalo de 24 horas). |
| static constexpr [TicksPerHour](./ticksperhour/) | El número de intervalos de 100 nanosegundos en una hora. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | El número de intervalos de 100 nanosegundos en un milisegundo. |
| static constexpr [TicksPerMinute](./ticksperminute/) | El número de intervalos de 100 nanosegundos en un minuto. |
| static constexpr [TicksPerSecond](./tickspersecond/) | El número de intervalos de 100 nanosegundos en un segundo. |
| static [Zero](./zero/) | El objeto [TimeSpan](./) que representa un intervalo cero. |

## Observaciones

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
Este ejemplo de código produce la siguiente salida:
Number of ticks: 260928000000000
Number of milliseconds: 0
Total number of milliseconds: 2.60928e+10
Number of minutes: 0
Total number of minutes: 434880
Number of hours: 0
Total number of hours: 0
Number of days: 302
Total number of days: 302
*/
```

## Véase también

* Namespace [System](../)
* Library [Aspose.Slides](../../)