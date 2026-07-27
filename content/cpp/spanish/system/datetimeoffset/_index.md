---
title: DateTimeOffset
second_title: Aspose.Slides para C++ Referencia de API
description: "Contiene la fecha y la hora del día relativa al Tiempo Universal Coordinado. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 235
url: /es/system/datetimeoffset/
---
## DateTimeOffset clase

Contiene la fecha y la hora del día relativa al Tiempo Universal Coordinado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class DateTimeOffset
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Agrega un intervalo de tiempo especificado al objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Agrega un número especificado de días al objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Agrega un número especificado de horas al objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Agrega un número especificado de milisegundos al objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Agrega un número especificado de minutos al objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Agrega un número especificado de meses al objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Agrega un número especificado de segundos al objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Agrega un número especificado de ticks al objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Agrega un número especificado de años al objeto [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Compara dos objetos [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Compara dos objetos [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Compara dos objetos [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Constructor predeterminado. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Constructor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal y tienen el mismo desfase. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal y tienen el mismo desfase. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) tiempo de archivo a fecha y hora con desfase horario local. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time a objeto [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time a objeto [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Obtiene el componente de fecha del objeto actual. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Obtiene el valor [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Obtiene el día del mes del objeto actual. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Obtiene el día de la semana del objeto actual. |
| int [get_DayOfYear](./get_dayofyear/)() const | Obtiene el día del año del objeto actual. |
| int [get_Hour](./get_hour/)() const | Obtiene el componente de hora del objeto actual. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Obtiene el valor [DateTime](../datetime/) que representa la fecha y hora local. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Obtiene el componente de milisegundos del objeto actual. |
| int [get_Minute](./get_minute/)() const | Obtiene el componente de minutos del objeto actual. |
| int [get_Month](./get_month/)() const | Obtiene el componente de mes del objeto actual. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Obtiene [DateTimeOffset](./) cuya fecha y hora se establecen a la hora local actual y cuyo desfase se establece al desfase de la hora local. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Obtiene el desfase respecto a UTC. |
| constexpr int [get_Second](./get_second/)() const | Obtiene el componente de segundos del objeto actual. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Obtiene el número de ticks del objeto actual. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Obtiene la hora del día del objeto actual. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Obtiene el valor [DateTime](../datetime/) que representa la fecha y hora UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Obtiene [DateTimeOffset](./) cuya fecha y hora se establecen a la hora UTC actual y cuyo desfase es [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Obtiene el número de ticks del objeto actual en tiempo UTC. |
| int [get_Year](./get_year/)() const | Obtiene el componente de año del objeto actual. |
| int [GetHashCode](./gethashcode/)() const | Obtiene el código hash para el objeto [DateTimeOffset](./) actual. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Determina si el objeto actual y el objeto [DateTimeOffset](./) especificado representan valores de fecha y hora distintos. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Devuelve una nueva instancia de la clase [DateTimeOffset](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el intervalo de tiempo especificado. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Devuelve una nueva instancia de la clase [DateTimeOffset](./) que representa el valor de fecha y hora que es el resultado de restar el intervalo de tiempo especificado del valor representado por el objeto actual. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Devuelve una instancia de la clase [TimeSpan](../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por los objetos actual y el especificado. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Determina si el objeto actual representa el valor de fecha y hora que es anterior al valor representado por el objeto [DateTimeOffset](./) especificado. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Determina si el objeto actual representa el valor de fecha y hora que es anterior o igual al valor representado por el objeto [DateTimeOffset](./) especificado. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Determina si el objeto actual y el objeto [DateTimeOffset](./) especificado representan el mismo valor de fecha y hora. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Determina si el objeto actual representa el valor de fecha y hora que es posterior al valor representado por el objeto [DateTimeOffset](./) especificado. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Determina si el objeto actual representa el valor de fecha y hora que es posterior o igual al valor representado por el objeto [DateTimeOffset](./) especificado. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Convierte la cadena especificada al equivalente [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convierte la cadena especificada a un objeto [DateTimeOffset](./) usando el proveedor de formato y el estilo de formato especificados. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convierte la cadena especificada a un objeto [DateTimeOffset](./) usando el formato, el proveedor de formato y el estilo de formato especificados. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convierte la cadena especificada a un objeto [DateTimeOffset](./) usando los formatos, el proveedor de formato y el estilo de formato especificados. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Resta un intervalo de tiempo especificado del objeto actual. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Resta un valor [DateTimeOffset](./) especificado del objeto actual. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Convierte el objeto actual al tiempo de archivo [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Convierte el objeto actual a un objeto que representa la hora local. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Reemplaza el desfase del objeto actual por el desfase especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convierte el objeto actual a una cadena usando el formato y el proveedor de formato especificados. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convierte el objeto actual a una cadena usando el proveedor de formato especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Convierte el objeto actual a una cadena usando el formato especificado. |
| [String](../string/) [ToString](./tostring/)() const | Convierte el objeto actual a una cadena. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Convierte el objeto actual a un objeto que representa la hora UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Obtiene los milisegundos transcurridos desde el inicio de la época Unix. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Obtiene los segundos transcurridos desde el inicio de la época Unix. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Intenta convertir la cadena especificada al objeto [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Intenta convertir la cadena especificada al objeto [DateTimeOffset](./) usando el proveedor de formato y el estilo de formato especificados. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Intenta convertir la cadena especificada al objeto [DateTimeOffset](./) usando los formatos, el proveedor de formato y el estilo de formato especificados. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Intenta convertir la cadena especificada al objeto [DateTimeOffset](./) usando el formato, el proveedor de formato y el estilo de formato especificados. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Devuelve un objeto [TypeInfo](../typeinfo/) que representa la estructura [TimeSpan](../timespan/). |

## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Obtiene el desfase máximo en ticks. |
| static [MaxValue](./maxvalue/) | Obtiene el mayor valor [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Obtiene el desfase mínimo en ticks. |
| static [MinValue](./minvalue/) | Obtiene el valor [DateTimeOffset](./) más temprano. |
| static [UnixEpoch](./unixepoch/) | Obtiene el inicio de la época Unix. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)