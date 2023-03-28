---
title: ConvertTime()
second_title: Aspose.Slides for C++ API Reference
description: Convert time from one time zone to another.
type: docs
weight: 40
url: /cpp/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime([DateTime](../../datetime/), const [TimeZoneInfoPtr](../../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../../timezoneinfoptr/)\&) method


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

## See Also

* Class [DateTime](../../datetime/)
* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeZoneInfo::ConvertTime(const [DateTimeOffset](../../datetimeoffset/)\&, const [TimeZoneInfoPtr](../../timezoneinfoptr/)\&) method


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

## See Also

* Class [DateTimeOffset](../../datetimeoffset/)
* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeZoneInfo::ConvertTime([DateTime](../../datetime/), const [TimeZoneInfoPtr](../../timezoneinfoptr/)\&) method


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

* Class [DateTime](../../datetime/)
* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
