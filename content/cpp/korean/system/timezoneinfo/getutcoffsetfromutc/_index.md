---
title: GetUtcOffsetFromUtc()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 시간대의 UTC 날짜-시간에 대한 UTC 오프셋을 반환하는 내부 도우미 함수입니다. 내부 전용.
type: docs
weight: 144
url: /ko/system/timezoneinfo/getutcoffsetfromutc/
---
## TimeZoneInfo::GetUtcOffsetFromUtc(DateTime, const TimeZoneInfoPtr\&) 메서드

지정된 시간대에서 UTC 날짜-시간에 대한 UTC 오프셋을 반환하는 내부 도우미 함수입니다. 내부 전용.

```cpp
static TimeSpan System::TimeZoneInfo::GetUtcOffsetFromUtc(DateTime time, const TimeZoneInfoPtr &zone)
```
## TimeZoneInfo::GetUtcOffsetFromUtc(DateTime, const TimeZoneInfoPtr\&, bool\&, bool\&) 메서드

지정된 시간대에서 UTC 날짜-시간에 대한 UTC 오프셋을 반환하는 내부 도우미 함수입니다. 내부 전용.

```cpp
static TimeSpan System::TimeZoneInfo::GetUtcOffsetFromUtc(DateTime time, const TimeZoneInfoPtr &zone, bool &is_daylight_savings, bool &is_ambiguous_local_dst)
```
## 참고

* 타입 정의 [TimeZoneInfoPtr](../../timezoneinfoptr/)
* 클래스 [TimeSpan](../../timespan/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [TimeZoneInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)