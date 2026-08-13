---
title: GetLeapMonth()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 연도에 대한 윤달을 가져옵니다.
type: docs
weight: 209
url: /ko/system.globalization/gregoriancalendar/getleapmonth/
---
## GregorianCalendar::GetLeapMonth(int, int) const 메서드

지정된 연도에 대한 윤달을 가져옵니다.

```cpp
int System::Globalization::GregorianCalendar::GetLeapMonth(int year, int era) const override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도입니다. |
| era | int | 시대입니다. |

### 반환 값

지정된 시대의 지정된 연도에 해당하는 윤달이며, 윤달이 없는 연도인 경우 0입니다.

## GregorianCalendar::GetLeapMonth(int) const 메서드

지정된 연도에 대한 윤달을 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도입니다. |

### 반환 값

지정된 연도에 해당하는 윤달이며, 윤달이 없는 연도인 경우 0입니다.

## GregorianCalendar::GetLeapMonth(int, int) const 메서드

지정된 연도에 대한 윤달을 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도입니다. |
| era | int | 시대입니다. |

### 반환 값

지정된 시대의 지정된 연도에 해당하는 윤달이며, 윤달이 없는 연도인 경우 0입니다.

## 참고

* 클래스 [GregorianCalendar](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)