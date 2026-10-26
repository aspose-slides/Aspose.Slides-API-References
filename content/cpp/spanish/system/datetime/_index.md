---
title: DateTime
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un valor específico de fecha y hora en la continuidad del tiempo. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca utilice la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 222
url: /es/system/datetime/
---
## Clase DateTime

Representa un valor específico de fecha y hora en la línea temporal. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class DateTime
```

## Métodos

| Method | Descripción |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa un valor de fecha y hora que resulta de la suma del intervalo de tiempo especificado al valor de fecha y hora representado por el objeto actual. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de días. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de horas. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de milisegundos. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de minutos. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de meses. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de segundos. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de intervalos de 100 nanosegundos. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa un valor de fecha y hora igual al representado por el objeto actual con el componente de año incrementado en el número especificado. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Compara dos valores representados por las instancias especificadas de la clase [DateTime](./) y devuelve el valor que indica la posición relativa de los valores en la línea temporal. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Compara dos valores de fecha y hora representados por el objeto actual y la instancia especificada de la clase [DateTime](./) y devuelve el valor que indica la posición relativa de los valores en la línea temporal. |
| constexpr [DateTime](./datetime/)() | Construye una instancia que representa la fecha y hora más pequeña posible, igual a MinValue. |
| [DateTime](./datetime/)(int, int, int) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes y día particulares. |
| [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes y día particulares en el calendario especificado. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo particulares. |
| [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo particulares. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo particulares en el calendario especificado. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto, segundo y milisegundo particulares. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto, segundo y milisegundo particulares en el calendario especificado. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Construye una instancia que representa un valor de fecha y hora especificado como un número de ticks. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Construye una instancia que representa un valor de fecha y hora especificado como un número de ticks. PARA USO INTERNO. |
| [DateTime](./datetime/)(const [DateTime](./)\&) | Copia-construye una instancia. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Devuelve el número de días en el mes especificado del año especificado. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Determina si las instancias especificadas de la clase [DateTime](./) representan el mismo valor de fecha y hora. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Determina si la instancia especificada de la clase [DateTime](./) representa el mismo valor de fecha y hora que el objeto actual. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Deserializa el valor de fecha y hora del entero sin signo de 64 bits especificado y establece la nueva instancia de la clase [DateTime](./) a ese valor. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Convierte el tiempo de archivo especificado a una instancia de la clase [DateTime](./) que representa el mismo valor de fecha y hora que la hora local. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Convierte el tiempo de archivo especificado a una instancia de la clase [DateTime](./) que representa el mismo valor de fecha y hora que la hora UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Devuelve una instancia de la clase [DateTime](./) que representa el valor de fecha y hora equivalente a la OLE Automation Date especificada. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Convierte el valor de tiempo Unix especificado a una instancia de la clase [DateTime](./). PARA USO INTERNO. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Devuelve una nueva instancia de la clase [DateTime](./) que representa la porción de fecha del valor de fecha y hora representado por el objeto actual, con cada componente de la porción de tiempo establecido a 0. |
| int [get_Day](./get_day/)() const | Devuelve el número ordinal del día del mes representado por el objeto actual. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Devuelve un valor que representa el día de la semana representado por el objeto actual. |
| int [get_DayOfYear](./get_dayofyear/)() const | Devuelve el número ordinal del día del año representado por el objeto actual. |
| constexpr int [get_Hour](./get_hour/)() const | Devuelve el componente de hora del valor de fecha y hora representado por el objeto actual. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Devuelve el valor que indica si la fecha y hora representada por el objeto actual es local, UTC o ninguno de los dos. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Devuelve el componente de milisegundo del valor de fecha y hora representado por el objeto actual. |
| constexpr int [get_Minute](./get_minute/)() const | Devuelve el componente de minuto del valor de fecha y hora representado por el objeto actual. |
| int [get_Month](./get_month/)() const | Devuelve el número ordinal del mes del año representado por el objeto actual. |
| static [DateTime](./) [get_Now](./get_now/)() | Devuelve una instancia de la clase [DateTime](./) que representa la hora actual como hora local. |
| constexpr int [get_Second](./get_second/)() const | Devuelve el componente de segundo del valor de fecha y hora representado por el objeto actual. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Devuelve un número de intervalos de 100 nanosegundos transcurridos desde 0:00:00 UTC, 1 de enero de 0001, en el calendario gregoriano hasta la fecha y hora representada por el objeto actual. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Devuelve el valor que representa el intervalo de tiempo desde el comienzo del día representado por el objeto actual hasta el valor de fecha y hora representado por el mismo objeto. |
| static [DateTime](./) [get_Today](./get_today/)() | Devuelve una instancia de la clase [DateTime](./) que representa la fecha actual con cada componente de la porción de tiempo del valor representado por el objeto establecido a 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Devuelve una instancia de la clase [DateTime](./) que representa la hora actual como UTC. |
| int [get_Year](./get_year/)() const | Devuelve el año representado por el objeto actual. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Obtiene las partes de la fecha. PARA USO INTERNO. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con uno de los especificadores estándar de formato de fecha y hora. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con el especificador estándar de formato de fecha y hora especificado. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con uno de los especificadores estándar de formato de fecha y hora y con el proveedor de formato especificado. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con el especificador estándar de formato de fecha y hora especificado y el proveedor de formato. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Determina si el valor de fecha y hora representado por el objeto actual se encuentra dentro del rango de horario de verano para la zona horaria actual. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Determina si el año especificado es un año bisiesto. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Determina si el objeto actual y el objeto [DateTime](./) especificado representan valores de fecha y hora distintos. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el intervalo de tiempo especificado. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Establece el objeto actual al valor de fecha y hora que es la suma del valor representado por el objeto actual y el intervalo de tiempo especificado. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que resulta de restar el intervalo de tiempo especificado al valor representado por el objeto actual. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Devuelve una instancia de la clase [TimeSpan](../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por los objetos actual y especificado. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Establece el objeto actual al valor de fecha y hora que resulta de restar el intervalo de tiempo especificado al valor de fecha y hora representado por el objeto actual. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Determina si el objeto actual representa el valor de fecha y hora que es anterior al valor representado por el objeto [DateTime](./) especificado. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Determina si el objeto actual representa el valor de fecha y hora que es anterior o igual al valor representado por el objeto [DateTime](./) especificado. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Asigna el valor representado por la instancia [DateTime](./) especificada al objeto actual. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Determina si el objeto actual y el objeto [DateTime](./) especificado representan el mismo valor de fecha y hora. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Determina si el objeto actual representa el valor de fecha y hora que es posterior al valor representado por el objeto [DateTime](./) especificado. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Determina si el objeto actual representa el valor de fecha y hora que es posterior o igual al valor representado por el objeto [DateTime](./) especificado. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando información de formato específica de la cultura. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando el formato especificado y la información de formato específica de la cultura. El formato de la representación de cadena debe coincidir exactamente con el formato especificado. Lanza una excepción si la conversión falla. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando los formatos especificados, la información de formato específica de la cultura y el estilo. El formato de la representación de cadena debe coincidir exactamente con uno o más de los formatos especificados. Lanza una excepción si la conversión falla. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Construye un nuevo objeto [DateTime](./) que representa el mismo número de ticks que el objeto [DateTime](./) especificado y representa hora local, hora UTC o ninguna, según lo indicado por el argumento **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora resultante de restar el intervalo de tiempo especificado del valor representado por el objeto actual. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Devuelve una instancia de la clase [TimeSpan](../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y los objetos especificados. |
| **int64_t** [ToBinary](./tobinary/)() const | Serializa el objeto actual. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Devuelve un valor que representa el valor de fecha y hora representado por el objeto actual como File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Convierte el valor de fecha y hora representado por el objeto actual a File time UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora representado por el objeto actual como hora local. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Devuelve una cadena que contiene la representación de cadena de fecha larga del objeto actual. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Devuelve una cadena que contiene la representación de cadena de hora larga del objeto actual. |
| **double** [ToOADate](./tooadate/)() const | Devuelve el valor de fecha y hora representado por el objeto actual como OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Devuelve una cadena que contiene la representación de cadena de fecha corta del objeto actual. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Devuelve una cadena que contiene la representación de cadena de hora corta del objeto actual. |
| [String](../string/) [ToString](./tostring/)() const | Devuelve la representación de cadena del valor de fecha y hora representado por el objeto actual usando las convenciones de formato definidas por la cultura actual. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Devuelve una representación de cadena del valor de fecha y hora representado por el objeto actual usando el formato especificado y las convenciones de formato definidas por la cultura actual. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Devuelve una representación de cadena del valor de fecha y hora representado por el objeto actual usando la información de formato especificada. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Devuelve una representación de cadena del valor de fecha y hora representado por el objeto actual usando la información de formato especificada. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora representado por el objeto actual como UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Devuelve un valor que representa el valor de fecha y hora representado por el objeto actual como tiempo Unix. FOR INTERNAL USE. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando la información de formato específica de la cultura y el estilo especificados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando el formato especificado, la información de formato específica de la cultura y el estilo. El formato de la representación de cadena debe coincidir exactamente con el formato especificado. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando los formatos especificados, la información de formato específica de la cultura y el estilo. El formato de la representación de cadena debe coincidir exactamente con uno o más de los formatos especificados. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Devuelve un objeto [TypeInfo](../typeinfo/) que contiene información sobre esta clase. |

## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | El número de intervalos de 100 nanosegundos en el intervalo de tiempo entre el valor [DateTime](./) mínimo posible y el máximo posible. |
| static [MaxValue](./maxvalue/) | Una instancia de la clase [DateTime](./) que representa el valor máximo posible de fecha y hora. |
| static constexpr [MinTicks](./minticks/) | El número mínimo de ticks que una instancia de la clase [DateTime](./) puede representar. |
| static [MinValue](./minvalue/) | Una instancia de la clase [DateTime](./) que representa el valor mínimo posible de fecha y hora. |
| static constexpr [TicksPerDay](./ticksperday/) | El número de ticks en un día. |
| static constexpr [TicksPerHour](./ticksperhour/) | El número de ticks en una hora. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | El número de ticks en un microsegundo. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | El número de ticks en un milisegundo. |
| static constexpr [TicksPerMinute](./ticksperminute/) | El número de ticks en un minuto. |
| static constexpr [TicksPerSecond](./tickspersecond/) | El número de ticks en un segundo. |
| static [UnixEpoch](./unixepoch/) | Una instancia de la clase [DateTime](./) que representa el inicio de la época Unix (1970-01-01 00:00:00). |

## Observaciones



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Crea la instancia de la clase 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Imprime la instancia en varios formatos.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.Slides](../../)