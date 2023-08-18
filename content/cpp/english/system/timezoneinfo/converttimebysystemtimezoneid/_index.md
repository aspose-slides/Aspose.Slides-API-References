---
title: ConvertTimeBySystemTimeZoneId()
second_title: Aspose.Slides for C++ API Reference
description: Convert time to the time in a specified time zone.
type: docs
weight: 53
url: /system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) method


[Convert](../../convert/) time to the time in a specified time zone.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| destination_time_zone_id | const [String](../../string/)\& | Identifier of the destination time zone. |

### Return Value

Converted date and time.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) method


[Convert](../../convert/) time to the time in a specified time zone.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time to convert. |
| destination_time_zone_id | const [String](../../string/)\& | Identifier of the destination time zone. |

### Return Value

Converted date and time.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) method


[Convert](../../convert/) time to the time in a specified time zone.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| source_time_zone_id | const [String](../../string/)\& | Identifier of the source time zone. |
| destination_time_zone_id | const [String](../../string/)\& | Identifier of the destination time zone. |

### Return Value

Converted date and time.

## See Also

* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [TimeZoneInfo](../)
* Class [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)