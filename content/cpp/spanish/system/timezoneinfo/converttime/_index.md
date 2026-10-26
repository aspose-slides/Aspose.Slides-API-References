---
title: ConvertTime()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convertir tiempo de una zona horaria a otra.
type: docs
weight: 40
url: /es/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr&, const TimeZoneInfoPtr&) método


[Convert](../../convert/) tiempo de una zona horaria a otra.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Source time zone. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Destination time zone. |

### Valor devuelto

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset&, const TimeZoneInfoPtr&) método


[Convert](../../convert/) tiempo a la hora en una zona horaria especificada.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)& | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Destination time zone. |

### Valor devuelto

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr&) método


[Convert](../../convert/) tiempo a la hora en una zona horaria especificada.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Destination time zone. |

### Valor devuelto

Converted date and time.

## Ver también

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Clase [DateTime](../../datetime/)
* Clase [TimeZoneInfo](../)
* Clase [DateTimeOffset](../../datetimeoffset/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)