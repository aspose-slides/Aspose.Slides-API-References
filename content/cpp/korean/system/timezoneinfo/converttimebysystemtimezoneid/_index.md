---
title: ConvertTimeBySystemTimeZoneId()
second_title: Aspose.Slides for C++ API 참조
description: 시간을 지정된 시간대의 시간으로 변환합니다.
type: docs
weight: 53
url: /ko/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) method

[Convert](../../convert/) 지정된 시간대의 시간으로 변환합니다.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 변환할 날짜 및 시간. |
| destination_time_zone_id | const [String](../../string/)\& | 대상 시간대의 식별자. |

### 반환값

변환된 날짜 및 시간.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) method

[Convert](../../convert/) 지정된 시간대의 시간으로 변환합니다.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 변환할 날짜 및 시간. |
| destination_time_zone_id | const [String](../../string/)\& | 대상 시간대의 식별자. |

### 반환값

변환된 날짜 및 시간.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) method

[Convert](../../convert/) 지정된 시간대의 시간으로 변환합니다.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 변환할 날짜 및 시간. |
| source_time_zone_id | const [String](../../string/)\& | 원본 시간대의 식별자. |
| destination_time_zone_id | const [String](../../string/)\& | 대상 시간대의 식별자. |

### 반환값

변환된 날짜 및 시간.

## 또 보기

* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [TimeZoneInfo](../)
* Class [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)