---
title: ConvertTime()
second_title: مرجع API Aspose.Slides للـ C++
description: تحويل الوقت من منطقة زمنية إلى أخرى.
type: docs
weight: 40
url: /ar/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) طريقة

[Convert](../../convert/) الوقت من منطقة زمنية إلى أخرى.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | التاريخ والوقت للتحويل. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | منطقة الوقت المصدر. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | منطقة الوقت الوجهة. |

### قيمة الإرجاع

التاريخ والوقت المحول.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) طريقة

[Convert](../../convert/) الوقت إلى الوقت في منطقة زمنية محددة.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | التاريخ والوقت للتحويل. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | منطقة الوقت الوجهة. |

### قيمة الإرجاع

التاريخ والوقت المحول.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) طريقة

[Convert](../../convert/) الوقت إلى الوقت في منطقة زمنية محددة.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | التاريخ والوقت للتحويل. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | منطقة الوقت الوجهة. |

### قيمة الإرجاع

التاريخ والوقت المحول.

## انظر أيضًا

* تعريف نوع [TimeZoneInfoPtr](../../timezoneinfoptr/)
* فئة [DateTime](../../datetime/)
* فئة [TimeZoneInfo](../)
* فئة [DateTimeOffset](../../datetimeoffset/)
* مساحة الأسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)