---
title: ConvertTime()
second_title: Aspose.Slides for C++ API referenciája
description: Átalakítja az időt egy időzónából a másikba.
type: docs
weight: 40
url: /hu/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) metódus


[Convert](../../convert/) időt egyik időzónából a másikba.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Source time zone. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Visszatérési érték

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) metódus


[Convert](../../convert/) időt a megadott időzónában lévő időre.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Visszatérési érték

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) metódus


[Convert](../../convert/) időt a megadott időzónában lévő időre.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Visszatérési érték

Converted date and time.

## Lásd még

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Osztály [DateTime](../../datetime/)
* Osztály [TimeZoneInfo](../)
* Osztály [DateTimeOffset](../../datetimeoffset/)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)