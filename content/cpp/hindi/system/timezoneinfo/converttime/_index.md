---
title: ConvertTime()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक समय क्षेत्र से दूसरे समय क्षेत्र में समय बदलें।
type: docs
weight: 40
url: /hi/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) विधि

[Convert](../../convert/) समय को एक समय क्षेत्र से दूसरे में बदलता है।

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Source time zone. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### वापसी मान

परिवर्तित तिथि और समय।

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) विधि

[Convert](../../convert/) समय को निर्दिष्ट समय क्षेत्र में समय में बदलता है।

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### वापसी मान

परिवर्तित तिथि और समय।

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) विधि

[Convert](../../convert/) समय को निर्दिष्ट समय क्षेत्र में समय में बदलता है।

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### वापसी मान

परिवर्तित तिथि और समय।

## संदर्भ

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* क्लास [DateTime](../../datetime/)
* क्लास [TimeZoneInfo](../)
* क्लास [DateTimeOffset](../../datetimeoffset/)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)