---
title: ConvertTime()
second_title: Aspose.Slides för C++ API-referens
description: Konvertera tid från en tidszon till en annan.
type: docs
weight: 40
url: /sv/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) metod


[Convert](../../convert/) tid från en tidszon till en annan.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum och tid att konvertera. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Källtidzon. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Måltidzon. |

### Returvärde

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) metod


[Convert](../../convert/) tid till tiden i en specificerad tidszon.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Datum och tid att konvertera. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Måltidzon. |

### Returvärde

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) metod


[Convert](../../convert/) tid till tiden i en specificerad tidszon.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum och tid att konvertera. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Måltidzon. |

### Returvärde

Converted date and time.

## Se även

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Klass [DateTime](../../datetime/)
* Klass [TimeZoneInfo](../)
* Klass [DateTimeOffset](../../datetimeoffset/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)