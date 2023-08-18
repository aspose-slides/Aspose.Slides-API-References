---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides for C++ API Reference
description: Gets UTC dates and times that a specified date and time can be mapped to.
type: docs
weight: 261
url: /system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const method


Gets UTC dates and times that a specified date and time can be mapped to.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time. |

### Return Value

[Array](../../array/) of UTC dates and times.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const method


Gets UTC dates and times that a specified date and time can be mapped to.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time. |

### Return Value

[Array](../../array/) of UTC dates and times.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [TimeSpan](../../timespan/)
* Class [DateTime](../../datetime/)
* Class [TimeZoneInfo](../)
* Class [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)