---
title: IsAmbiguousTime()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 날짜와 시간이 모호한지 확인하고 여러 UTC 시간에 매핑될 수 있는지 검사합니다.
type: docs
weight: 313
url: /ko/system/timezoneinfo/isambiguoustime/
---
## TimeZoneInfo::IsAmbiguousTime(DateTime) const 메서드

지정된 날짜와 시간이 모호한지, 그리고 여러 UTC 시간에 매핑될 수 있는지 확인합니다.

```cpp
bool System::TimeZoneInfo::IsAmbiguousTime(DateTime date_time) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 날짜와 시간. |

### 반환값

date_time이 모호하면 True를 반환합니다.

## TimeZoneInfo::IsAmbiguousTime(const DateTimeOffset\&) const 메서드

지정된 날짜와 시간이 모호한지, 그리고 여러 UTC 시간에 매핑될 수 있는지 확인합니다.

```cpp
bool System::TimeZoneInfo::IsAmbiguousTime(const DateTimeOffset &date_time_offset) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 날짜와 시간. |

### 반환값

date_time이 모호하면 True를 반환합니다.

## 참고

* 클래스 [DateTime](../../datetime/)
* 클래스 [TimeZoneInfo](../)
* 클래스 [DateTimeOffset](../../datetimeoffset/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)