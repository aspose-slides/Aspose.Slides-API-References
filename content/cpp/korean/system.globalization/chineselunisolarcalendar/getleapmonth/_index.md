---
title: GetLeapMonth()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 연도에 대한 윤달을 가져옵니다.
type: docs
weight: 92
url: /ko/system.globalization/chineselunisolarcalendar/getleapmonth/
---
## ChineseLunisolarCalendar::GetLeapMonth(int, int) const method

지정된 연도에 해당하는 윤달을 가져옵니다.

```cpp
int System::Globalization::ChineseLunisolarCalendar::GetLeapMonth(int year, int era) const override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |
| era | int | 시대. |

### 반환 값

지정된 시대와 연도에 해당하는 윤달, 윤달이 없을 경우 0을 반환합니다.

## ChineseLunisolarCalendar::GetLeapMonth(int) const method

지정된 연도에 해당하는 윤달을 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |

### 반환 값

지정된 연도에 해당하는 윤달, 윤달이 없을 경우 0을 반환합니다.

## ChineseLunisolarCalendar::GetLeapMonth(int, int) const method

지정된 연도에 해당하는 윤달을 가져옵니다.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 윤달을 가져올 연도. |
| era | int | 시대. |

### 반환 값

지정된 시대와 연도에 해당하는 윤달, 윤달이 없을 경우 0을 반환합니다.

## 참조

* 클래스 [ChineseLunisolarCalendar](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)