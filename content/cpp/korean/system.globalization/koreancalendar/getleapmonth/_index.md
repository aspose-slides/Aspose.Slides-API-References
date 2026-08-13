---
title: GetLeapMonth()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 연도의 윤달을 가져옵니다.
type: docs
weight: 183
url: /ko/system.globalization/koreancalendar/getleapmonth/
---
## KoreanCalendar::GetLeapMonth(int, int) const method

지정된 연도의 윤달을 가져옵니다.

```cpp
int System::Globalization::KoreanCalendar::GetLeapMonth(int year, int era) const override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |
| era | int | 시대. |

### 반환값

지정된 시대의 지정된 연도에 해당하는 윤달이며, 해당 연도에 윤달이 없으면 0을 반환합니다.

## KoreanCalendar::GetLeapMonth(int) const method

지정된 연도의 윤달을 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |

### 반환값

지정된 연도에 해당하는 윤달이며, 해당 연도에 윤달이 없으면 0을 반환합니다.

## KoreanCalendar::GetLeapMonth(int, int) const method

지정된 연도의 윤달을 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |
| era | int | 시대. |

### 반환값

지정된 시대의 지정된 연도에 해당하는 윤달이며, 해당 연도에 윤달이 없으면 0을 반환합니다.

## 참조

* 클래스 [KoreanCalendar](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)