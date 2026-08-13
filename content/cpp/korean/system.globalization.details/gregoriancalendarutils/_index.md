---
title: GregorianCalendarUtils
second_title: Aspose.Slides for C++ API 레퍼런스
description: 그레고리안 캘린더 유틸리티 함수.
type: docs
weight: 1
url: /ko/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils 클래스

Gregorian calendar utility functions.

```cpp
class GregorianCalendarUtils
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) ICU UDate 로. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate 를 [DateTime](../../system/datetime/) 로. |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | 그레고리안 ICU 캘린더를 생성합니다. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | 스레드 로컬 그레고리안 ICU 캘린더를 가져옵니다. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | 특정 월의 일 수를 가져옵니다. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | 특정 연도의 일 수를 가져옵니다. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | 해당 일이 윤년인지 확인합니다. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | 해당 연도가 윤년인지 확인합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | 지원되는 최대 그레고리안 연도. |
| static constexpr [MinYear](./minyear/) | 지원되는 최소 그레고리안 연도. |
## 참고

* 네임스페이스 [System::Globalization::Details](../)
* 라이브러리 [Aspose.Slides](../../)