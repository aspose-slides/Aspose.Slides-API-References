---
title: DateTimeOffset()
second_title: Referencia de API de Aspose.Slides para C++
description: Constructor predeterminado.
type: docs
weight: 1
url: /es/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() constructor

Constructor predeterminado.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) constructor

Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Fecha y hora. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) constructor

Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ticks | **int64_t** | Número de ticks. |
| offset | [TimeSpan](../../timespan/) | Desplazamiento de tiempo respecto a UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) constructor

Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Fecha y hora. |
| offset | [TimeSpan](../../timespan/) | Desplazamiento de tiempo respecto a UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) constructor

Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | Año (1 a 9999). |
| month | int | Mes (1 a 12). |
| day | int | Día (1 al número de días del mes). |
| hour | int | Hora (0 a 23). |
| minute | int | Minuto (0 a 59). |
| second | int | Segundo (0 a 59). |
| offset | [TimeSpan](../../timespan/) | Desplazamiento de tiempo respecto a UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) constructor

Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | Año (1 a 9999). |
| month | int | Mes (1 a 12). |
| day | int | Día (1 al número de días del mes). |
| hour | int | Hora (0 a 23). |
| minute | int | Minuto (0 a 59). |
| second | int | Segundo (0 a 59). |
| millisecond | int | Milisegundo (0 a 999). |
| offset | [TimeSpan](../../timespan/) | Desplazamiento de tiempo respecto a UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) constructor

Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| year | int | Año. |
| month | int | Mes (1 a 12). |
| day | int | Día (1 al número de días del mes). |
| hour | int | Hora (0 a 23). |
| minute | int | Minuto (0 a 59). |
| second | int | Segundo (0 a 59). |
| millisecond | int | Milisegundo (0 a 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Calendario usado para interpretar el año, mes y día. |
| offset | [TimeSpan](../../timespan/) | Desplazamiento de tiempo respecto a UTC. |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [DateTimeOffset](../)
* Clase [DateTime](../../datetime/)
* Clase [TimeSpan](../../timespan/)
* Clase [Calendar](../../../system.globalization/calendar/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)