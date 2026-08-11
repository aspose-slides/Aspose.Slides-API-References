---
title: ConvertTime()
second_title: Aspose.Slides برای C++ - مرجع API
description: تبدیل زمان از یک منطقه زمانی به منطقه زمانی دیگر.
type: docs
weight: 40
url: /fa/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) متد

[Convert](../../convert/) زمان را از یک منطقه زمانی به منطقه زمانی دیگر تبدیل می‌کند.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | تاریخ و زمان برای تبدیل. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | منطقه زمانی منبع. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | منطقه زمانی مقصد. |

### مقدار بازگشت

تاریخ و زمان تبدیل‌شده.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) متد

[Convert](../../convert/) زمان را به زمان در یک منطقه زمانی مشخص تبدیل می‌کند.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | تاریخ و زمان برای تبدیل. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | منطقه زمانی مقصد. |

### مقدار بازگشت

تاریخ و زمان تبدیل‌شده.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) متد

[Convert](../../convert/) زمان را به زمان در یک منطقه زمانی مشخص تبدیل می‌کند.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | تاریخ و زمان برای تبدیل. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | منطقه زمانی مقصد. |

### مقدار بازگشت

تاریخ و زمان تبدیل‌شده.

## مراجع

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* کلاس [DateTime](../../datetime/)
* کلاس [TimeZoneInfo](../)
* کلاس [DateTimeOffset](../../datetimeoffset/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)