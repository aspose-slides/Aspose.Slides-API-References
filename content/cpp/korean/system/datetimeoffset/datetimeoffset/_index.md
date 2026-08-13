---
title: DateTimeOffset()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 생성자.
type: docs
weight: 1
url: /ko/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() 생성자

기본 생성자.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) 생성자

생성자.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 날짜 및 시간. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) 생성자

생성자.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ticks | **int64_t** | 틱 수. |
| offset | [TimeSpan](../../timespan/) | UTC 기준 시간 오프셋. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) 생성자

생성자.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 날짜 및 시간. |
| offset | [TimeSpan](../../timespan/) | UTC 기준 시간 오프셋. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) 생성자

생성자.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 연도 (1 ~ 9999). |
| month | int | 월 (1 ~ 12). |
| day | int | 일 (1 ~ 해당 월의 일 수). |
| hour | int | 시 (0 ~ 23). |
| minute | int | 분 (0 ~ 59). |
| second | int | 초 (0 ~ 59). |
| offset | [TimeSpan](../../timespan/) | UTC 기준 시간 오프셋. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) 생성자

생성자.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 연도 (1 ~ 9999). |
| month | int | 월 (1 ~ 12). |
| day | int | 일 (1 ~ 해당 월의 일 수). |
| hour | int | 시 (0 ~ 23). |
| minute | int | 분 (0 ~ 59). |
| second | int | 초 (0 ~ 59). |
| millisecond | int | 밀리초 (0 ~ 999). |
| offset | [TimeSpan](../../timespan/) | UTC 기준 시간 오프셋. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) 생성자

생성자.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 연도. |
| month | int | 월 (1 ~ 12). |
| day | int | 일 (1 ~ 해당 월의 일 수). |
| hour | int | 시 (0 ~ 23). |
| minute | int | 분 (0 ~ 59). |
| second | int | 초 (0 ~ 59). |
| millisecond | int | 밀리초 (0 ~ 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 년, 월, 일을 해석하는 데 사용되는 캘린더. |
| offset | [TimeSpan](../../timespan/) | UTC 기준 시간 오프셋. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [DateTimeOffset](../)
* 클래스 [DateTime](../../datetime/)
* 클래스 [TimeSpan](../../timespan/)
* 클래스 [Calendar](../../../system.globalization/calendar/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)