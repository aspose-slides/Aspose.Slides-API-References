---
title: ConvertTimeBySystemTimeZoneId()
second_title: Aspose.Slides pro C++ Referenční dokumentace API
description: Převádí čas na čas v určeném časovém pásmu.
type: docs
weight: 53
url: /cs/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) metoda

[Convert](../../convert/) převádí čas na čas v určeném časovém pásmu.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum a čas k převodu. |
| destination_time_zone_id | const [String](../../string/)\& | Identifikátor cílového časového pásma. |

### Návratová hodnota

Převedené datum a čas.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) metoda

[Convert](../../convert/) převádí čas na čas v určeném časovém pásmu.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Datum a čas k převodu. |
| destination_time_zone_id | const [String](../../string/)\& | Identifikátor cílového časového pásma. |

### Návratová hodnota

Převedené datum a čas.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) metoda

[Convert](../../convert/) převádí čas na čas v určeném časovém pásmu.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum a čas k převodu. |
| source_time_zone_id | const [String](../../string/)\& | Identifikátor zdrojového časového pásma. |
| destination_time_zone_id | const [String](../../string/)\& | Identifikátor cílového časového pásma. |

### Návratová hodnota

Převedené datum a čas.

## Viz také

* Třída [DateTime](../../datetime/)
* Třída [String](../../string/)
* Třída [TimeZoneInfo](../)
* Třída [DateTimeOffset](../../datetimeoffset/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)