---
title: GetWeekOfYear()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 시점에 대한 연도의 주 번호를 가져옵니다.
type: docs
weight: 352
url: /ko/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const 메서드

지정된 시점에 대한 연도의 주 번호를 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | 데이터를 추출할 시간 및 날짜. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | 연도의 첫 번째 주를 결정하는 방법을 정의합니다. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | 주 첫 번째 요일을 정의합니다. |

### 반환 값

전달된 시점의 연도 주 번호입니다.

## 참고

* 열거형 [CalendarWeekRule](../../calendarweekrule/)
* 열거형 [DayOfWeek](../../../system/dayofweek/)
* 클래스 [DateTime](../../../system/datetime/)
* 클래스 [Calendar](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)