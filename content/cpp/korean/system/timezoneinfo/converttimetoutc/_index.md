---
title: ConvertTimeToUtc()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시간을 UTC 시간으로 변환합니다.
type: docs
weight: 79
url: /ko/system/timezoneinfo/converttimetoutc/
---
## TimeZoneInfo::ConvertTimeToUtc(DateTime, const TimeZoneInfoPtr&) 메서드

UTC 시간으로 변환합니다.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeToUtc(DateTime date_time, const TimeZoneInfoPtr &source_time_zone)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 변환할 날짜와 시간. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 원본 시간대. |

### 반환값

변환된 날짜와 시간.

## TimeZoneInfo::ConvertTimeToUtc(DateTime) 메서드

UTC 시간으로 변환합니다.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeToUtc(DateTime date_time)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 변환할 날짜와 시간. |

### 반환값

변환된 날짜와 시간.

## 참고

* 타입정의 [TimeZoneInfoPtr](../../timezoneinfoptr/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [TimeZoneInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)