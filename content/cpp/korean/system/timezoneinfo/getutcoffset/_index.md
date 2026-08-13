---
title: GetUtcOffset()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 날짜 및 시간에 대해 이 표준시와 UTC 표준시 간의 차이를 계산합니다.
type: docs
weight: 274
url: /ko/system/timezoneinfo/getutcoffset/
---
## TimeZoneInfo::GetUtcOffset(DateTime) const 메서드

지정된 날짜 및 시간에 대해 이 표준시와 UTC 표준시 사이의 차이를 계산합니다.

```cpp
TimeSpan System::TimeZoneInfo::GetUtcOffset(DateTime date_time) const
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 날짜와 시간. |

### 반환값

시간대 간의 시간 차이.

## TimeZoneInfo::GetUtcOffset(const DateTimeOffset\&) const 메서드

지정된 날짜 및 시간에 대해 이 표준시와 UTC 표준시 사이의 차이를 계산합니다.

```cpp
TimeSpan System::TimeZoneInfo::GetUtcOffset(const DateTimeOffset &date_time_offset) const
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 날짜와 시간. |

### 반환값

시간대 간의 시간 차이.

## 참고

* 클래스 [TimeSpan](../../timespan/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [TimeZoneInfo](../)
* 클래스 [DateTimeOffset](../../datetimeoffset/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)