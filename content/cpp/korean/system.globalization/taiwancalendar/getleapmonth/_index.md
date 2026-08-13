---
title: GetLeapMonth()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 연도의 윤달을 가져옵니다.
type: docs
weight: 183
url: /ko/system.globalization/taiwancalendar/getleapmonth/
---
## TaiwanCalendar::GetLeapMonth(int, int) const 메서드

지정된 연도에 대한 윤달을 가져옵니다.

```cpp
int System::Globalization::TaiwanCalendar::GetLeapMonth(int year, int era) const override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |
| era | int | 시대. |

### 반환값

지정된 연도와 지정된 시대의 윤달이며, 윤달이 없으면 0을 반환합니다.

## TaiwanCalendar::GetLeapMonth(int) const 메서드

지정된 연도에 대한 윤달을 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |

### 반환값

지정된 연도의 윤달이며, 윤달이 없으면 0을 반환합니다.

## TaiwanCalendar::GetLeapMonth(int, int) const 메서드

지정된 연도에 대한 윤달을 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |
| era | int | 시대. |

### 반환값

지정된 연도와 지정된 시대의 윤달이며, 윤달이 없으면 0을 반환합니다.

## 참조

* 클래스 [TaiwanCalendar](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)