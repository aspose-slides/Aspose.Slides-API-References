---
title: ConvertTime()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převést čas z jedné časové zóny do druhé.
type: docs
weight: 40
url: /cs/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr&, const TimeZoneInfoPtr&) metoda


[Convert](../../convert/) čas z jedné časové zóny do druhé.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum a čas k převodu. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Zdrojová časová zóna. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Cílová časová zóna. |

### Vrácená hodnota

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset&, const TimeZoneInfoPtr&) metoda


[Convert](../../convert/) čas do času ve specifikované časové zóně.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)& | Datum a čas k převodu. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Cílová časová zóna. |

### Vrácená hodnota

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr&) metoda


[Convert](../../convert/) čas do času ve specifikované časové zóně.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum a čas k převodu. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Cílová časová zóna. |

### Vrácená hodnota

Converted date and time.

## Viz také

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Třída [DateTime](../../datetime/)
* Třída [TimeZoneInfo](../)
* Třída [DateTimeOffset](../../datetimeoffset/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)