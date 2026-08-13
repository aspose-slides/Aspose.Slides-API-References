---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 날짜 및 시간에 매핑될 수 있는 UTC 날짜와 시간을 가져옵니다.
type: docs
weight: 261
url: /ko/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const 메서드

지정된 날짜 및 시간에 매핑될 수 있는 UTC 날짜 및 시간을 가져옵니다.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 날짜 및 시간. |

### 반환값

[Array](../../array/) UTC 날짜 및 시간.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const 메서드

지정된 날짜 및 시간에 매핑될 수 있는 UTC 날짜 및 시간을 가져옵니다.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 날짜 및 시간. |

### 반환값

[Array](../../array/) UTC 날짜 및 시간.

## 또 보기

* 타입정의 [ArrayPtr](../../arrayptr/)
* 클래스 [TimeSpan](../../timespan/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [TimeZoneInfo](../)
* 클래스 [DateTimeOffset](../../datetimeoffset/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)