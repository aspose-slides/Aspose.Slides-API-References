---
title: ConvertTime()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시간대를 하나에서 다른 시간대로 변환합니다.
type: docs
weight: 40
url: /ko/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) 메서드

[Convert](../../convert/) 시간을 한 시간대에서 다른 시간대로 변환합니다.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 변환할 날짜와 시간입니다. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 원본 시간대입니다. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 대상 시간대입니다. |

### 반환값

변환된 날짜와 시간입니다.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) 메서드

[Convert](../../convert/) 지정된 시간대의 시간으로 변환합니다.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 변환할 날짜와 시간입니다. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 대상 시간대입니다. |

### 반환값

변환된 날짜와 시간입니다.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) 메서드

[Convert](../../convert/) 지정된 시간대의 시간으로 변환합니다.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 변환할 날짜와 시간입니다. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 대상 시간대입니다. |

### 반환값

변환된 날짜와 시간입니다.

## 또 보기

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [TimeZoneInfo](../)
* 클래스 [DateTimeOffset](../../datetimeoffset/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)