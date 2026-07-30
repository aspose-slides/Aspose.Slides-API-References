---
title: ConvertTime()
second_title: Riferimento API di Aspose.Slides per C++
description: Converti il tempo da un fuso orario a un altro.
type: docs
weight: 40
url: /it/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) metodo


[Convert](../../convert/) tempo da un fuso orario a un altro.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Source time zone. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Valore di ritorno

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) metodo


[Convert](../../convert/) tempo al tempo in un fuso orario specificato.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Valore di ritorno

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) metodo


[Convert](../../convert/) tempo al tempo in un fuso orario specificato.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Valore di ritorno

Converted date and time.

## Vedi anche

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Classe [DateTime](../../datetime/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)