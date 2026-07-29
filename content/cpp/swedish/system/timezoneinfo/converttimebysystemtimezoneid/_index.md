---
title: ConvertTimeBySystemTimeZoneId()
second_title: Aspose.Slides för C++ API-referens
description: Konvertera tid till tiden i en specificerad tidszon.
type: docs
weight: 53
url: /sv/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) method


[Convert](../../convert/) tid till tiden i en specificerad tidszon.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum och tid att konvertera. |
| destination_time_zone_id | const [String](../../string/)\& | Identifierare för destinationstidszonen. |

### Returvärde

Konverterat datum och tid.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) method


[Convert](../../convert/) tid till tiden i en specificerad tidszon.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Datum och tid att konvertera. |
| destination_time_zone_id | const [String](../../string/)\& | Identifierare för destinationstidszonen. |

### Returvärde

Konverterat datum och tid.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) method


[Convert](../../convert/) tid till tiden i en specificerad tidszon.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum och tid att konvertera. |
| source_time_zone_id | const [String](../../string/)\& | Identifierare för källtidszonen. |
| destination_time_zone_id | const [String](../../string/)\& | Identifierare för destinationstidszonen. |

### Returvärde

Konverterat datum och tid.

## Se även

* Klass [DateTime](../../datetime/)
* Klass [String](../../string/)
* Klass [TimeZoneInfo](../)
* Klass [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)