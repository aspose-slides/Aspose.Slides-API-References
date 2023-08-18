---
title: ConvertTime()
second_title: Aspose.Slides for C++ API Reference
description: Convert time from one time zone to another.
type: docs
weight: 40
url: /system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) method


[Convert](../../convert/) time from one time zone to another.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Source time zone. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Return Value

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) method


[Convert](../../convert/) time to the time in a specified time zone.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Return Value

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) method


[Convert](../../convert/) time to the time in a specified time zone.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Return Value

Converted date and time.

## See Also

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [DateTime](../../datetime/)
* Class [TimeZoneInfo](../)
* Class [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)