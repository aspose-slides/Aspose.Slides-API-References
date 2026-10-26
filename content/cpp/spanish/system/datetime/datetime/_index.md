---
title: DateTime()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una instancia que representa el valor de fecha y hora más pequeño posible, igual a MinValue.
type: docs
weight: 1
url: /es/system/datetime/datetime/
---
## DateTime::DateTime() constructor

Construye una instancia que representa el valor de fecha y hora más pequeño posible, igual a MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un año, mes y día determinados.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| day | int | El día del **month** que será representado por la instancia que se está construyendo. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un año, mes y día determinados en el calendario especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| day | int | El día del **month** que será representado por la instancia que se está construyendo. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | El calendario usado para interpretar el **year**, **month** y **day** especificados. |

## DateTime::DateTime(int, int, int, int, int, int) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo determinados.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| day | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hour | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minute | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| second | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo determinados.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| day | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hour | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minute | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| second | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |
| kind | [DateTimeKind](../../datetimekind/) | El valor que indica si los parámetros de fecha y hora proporcionados especifican una hora local, hora UTC o ninguno. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo determinados en el calendario especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| day | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hour | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minute | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| second | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | El calendario usado para interpretar el **year**, **month** y **day** especificados. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto, segundo y milisegundo determinados.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| day | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hour | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minute | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| second | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |
| millisecond | int | El milisegundo del **second** que será representado por la instancia que se está construyendo. |
| kind | [DateTimeKind](../../datetimekind/) | El valor que indica si los parámetros de fecha y hora proporcionados especifican una hora local, hora UTC o ninguno. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto, segundo y milisegundo determinados en el calendario especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | El año que será representado por la instancia que se está construyendo. |
| month | int | El mes del **year** que será representado por la instancia que se está construyendo. |
| day | int | El día del **month** que será representado por la instancia que se está construyendo. |
| hour | int | La hora del **day** que será representado por la instancia que se está construyendo. |
| minute | int | El minuto de la **hour** que será representado por la instancia que se está construyendo. |
| second | int | El segundo del **minute** que será representado por la instancia que se está construyendo. |
| millisecond | int | El milisegundo del **second** que será representado por la instancia que se está construyendo. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | El valor que indica si los parámetros de fecha y hora proporcionados especifican una hora local, hora UTC o ninguno. |
| calendar | [DateTimeKind](../../datetimekind/) | El calendario usado para interpretar el **year**, **month** y **day** especificados. |

## DateTime::DateTime(int64_t, DateTimeKind) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un número de ticks.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ticks | **int64_t** | El número de intervalos de 100 ns que han transcurrido desde el 1 de enero de 0001 00:00:00.000 en el calendario georgiano. |
| kind | [DateTimeKind](../../datetimekind/) | El valor que indica si el parámetro **ticks** especifica una hora local, hora UTC o ninguno. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) constructor

Construye una instancia que representa un valor de fecha y hora especificado como un número de ticks. PARA USO INTERNO.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ticks | **int64_t** | El número de intervalos de 100 ns que han transcurrido desde el 1 de enero de 0001 00:00:00.000 en el calendario georgiano. |
| kind | [DateTimeKind](../../datetimekind/) | El valor que indica si el parámetro **ticks** especifica una hora local, hora UTC o ninguno. |
| is_ambiguous_local_dst | **bool** | True si la fecha y hora especificadas son ambiguas y pueden mapearse a muchas horas UTC. |

## DateTime::DateTime(const DateTime\&) constructor

Construye una copia de una instancia.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Una instancia de la clase [DateTime](../) de la cual copiar el valor de fecha y hora representado. |

## Ver también

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)