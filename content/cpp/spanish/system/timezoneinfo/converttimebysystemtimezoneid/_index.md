---
title: ConvertTimeBySystemTimeZoneId()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la hora al tiempo en una zona horaria especificada.
type: docs
weight: 53
url: /es/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String&) método

[Convert](../../convert/) convierte la hora al tiempo en una zona horaria especificada.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Fecha y hora a convertir. |
| destination_time_zone_id | const [String](../../string/)\& | Identificador de la zona horaria de destino. |

### Valor devuelto

Fecha y hora convertidas.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset&, const String&) método

[Convert](../../convert/) convierte la hora al tiempo en una zona horaria especificada.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Fecha y hora a convertir. |
| destination_time_zone_id | const [String](../../string/)\& | Identificador de la zona horaria de destino. |

### Valor devuelto

Fecha y hora convertidas.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String&, const String&) método

[Convert](../../convert/) convierte la hora al tiempo en una zona horaria especificada.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Fecha y hora a convertir. |
| source_time_zone_id | const [String](../../string/)\& | Identificador de la zona horaria de origen. |
| destination_time_zone_id | const [String](../../string/)\& | Identificador de la zona horaria de destino. |

### Valor devuelto

Fecha y hora convertidas.

## Véase también

* Clase [DateTime](../../datetime/)
* Clase [String](../../string/)
* Clase [TimeZoneInfo](../)
* Clase [DateTimeOffset](../../datetimeoffset/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)