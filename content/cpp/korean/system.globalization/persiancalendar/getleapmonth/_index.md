---
title: GetLeapMonth()
second_title: Aspose.Slides용 C++ API 레퍼런스
description: 지정된 연도의 윤달을 반환합니다.
type: docs
weight: 118
url: /ko/system.globalization/persiancalendar/getleapmonth/
---
## PersianCalendar::GetLeapMonth(int, int) const 메서드

지정된 연도의 윤달을 반환합니다.

```cpp
int System::Globalization::PersianCalendar::GetLeapMonth(int year, int era) const override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |
| era | int | 시대. |

### 반환값

지정된 시대의 지정된 연도에 대한 윤달이며, 연도에 윤달이 없으면 0을 반환합니다.

## PersianCalendar::GetLeapMonth(int) const 메서드

지정된 연도의 윤달을 반환합니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |

### 반환값

지정된 연도에 대한 윤달이며, 연도에 윤달이 없으면 0을 반환합니다.

## PersianCalendar::GetLeapMonth(int, int) const 메서드

지정된 연도의 윤달을 반환합니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |
| era | int | 시대. |

### 반환값

지정된 시대의 지정된 연도에 대한 윤달이며, 연도에 윤달이 없으면 0을 반환합니다.

## 참조

* 클래스 [PersianCalendar](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)