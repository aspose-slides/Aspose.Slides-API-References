---
title: ConvertTimeBySystemTimeZoneId()
second_title: Riferimento API di Aspose.Slides per C++
description: Converti l'ora al fuso orario specificato.
type: docs
weight: 53
url: /it/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) method


[Convert](../../convert/) Converti l'ora al fuso orario specificato.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e ora da convertire. |
| destination_time_zone_id | const [String](../../string/)\& | Identificatore del fuso orario di destinazione. |

### Valore restituito

Data e ora convertite.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) method


[Convert](../../convert/) Converti l'ora al fuso orario specificato.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Data e ora da convertire. |
| destination_time_zone_id | const [String](../../string/)\& | Identificatore del fuso orario di destinazione. |

### Valore restituito

Data e ora convertite.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) method


[Convert](../../convert/) Converti l'ora al fuso orario specificato.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e ora da convertire. |
| source_time_zone_id | const [String](../../string/)\& | Identificatore del fuso orario di origine. |
| destination_time_zone_id | const [String](../../string/)\& | Identificatore del fuso orario di destinazione. |

### Valore restituito

Data e ora convertite.

## Vedi anche

* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)