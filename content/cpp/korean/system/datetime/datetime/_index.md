---
title: DateTime()
second_title: Aspose.Slides for C++ API 레퍼런스
description: MinValue와 동일한 가능한 가장 작은 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system/datetime/datetime/
---
## DateTime::DateTime() 생성자

최소값(MinValue)과 동일한 가능한 가장 작은 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) 생성자

특정 연도, 월, 일로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 구성되는 인스턴스가 나타내는 연도. |
| month | int | 구성되는 인스턴스가 나타내는 **연도**의 월. |
| day | int | 구성되는 인스턴스가 나타내는 **월**의 일. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) 생성자

지정된 달력에서 특정 연도, 월, 일로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 구성되는 인스턴스가 나타내는 연도. |
| month | int | 구성되는 인스턴스가 나타내는 **연도**의 월. |
| day | int | 구성되는 인스턴스가 나타내는 **월**의 일. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 지정된 **연도**, **월**, **일**을 해석할 때 사용하는 달력. |

## DateTime::DateTime(int, int, int, int, int, int) 생성자

특정 연도, 월, 일, 시, 분, 초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 구성되는 인스턴스가 나타내는 연도. |
| month | int | 구성되는 인스턴스가 나타내는 **연도**의 월. |
| day | int | 구성되는 인스턴스가 나타내는 **월**의 일. |
| hour | int | 구성되는 인스턴스가 나타내는 **일**의 시. |
| minute | int | 구성되는 인스턴스가 나타내는 **시**의 분. |
| second | int | 구성되는 인스턴스가 나타내는 **분**의 초. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) 생성자

특정 연도, 월, 일, 시, 분, 초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 구성되는 인스턴스가 나타내는 연도. |
| month | int | 구성되는 인스턴스가 나타내는 **연도**의 월. |
| day | int | 구성되는 인스턴스가 나타내는 **월**의 일. |
| hour | int | 구성되는 인스턴스가 나타내는 **일**의 시. |
| minute | int | 구성되는 인스턴스가 나타내는 **시**의 분. |
| second | int | 구성되는 인스턴스가 나타내는 **분**의 초. |
| kind | [DateTimeKind](../../datetimekind/) | 제공된 날짜 및 시간 매개변수가 로컬 시간, UTC 시간 또는 그 어느 것도 아닌지를 나타내는 값. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) 생성자

지정된 달력에서 특정 연도, 월, 일, 시, 분, 초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 구성되는 인스턴스가 나타내는 연도. |
| month | int | 구성되는 인스턴스가 나타내는 **연도**의 월. |
| day | int | 구성되는 인스턴스가 나타내는 **월**의 일. |
| hour | int | 구성되는 인스턴스가 나타내는 **일**의 시. |
| minute | int | 구성되는 인스턴스가 나타내는 **시**의 분. |
| second | int | 구성되는 인스턴스가 나타내는 **분**의 초. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 지정된 **연도**, **월**, **일**을 해석할 때 사용하는 달력. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) 생성자

특정 연도, 월, 일, 시, 분, 초 및 밀리초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 구성되는 인스턴스가 나타내는 연도. |
| month | int | 구성되는 인스턴스가 나타내는 **연도**의 월. |
| day | int | 구성되는 인스턴스가 나타내는 **월**의 일. |
| hour | int | 구성되는 인스턴스가 나타내는 **일**의 시. |
| minute | int | 구성되는 인스턴스가 나타내는 **시**의 분. |
| second | int | 구성되는 인스턴스가 나타내는 **분**의 초. |
| millisecond | int | 구성되는 인스턴스가 나타내는 **초**의 밀리초. |
| kind | [DateTimeKind](../../datetimekind/) | 제공된 날짜 및 시간 매개변수가 로컬 시간, UTC 시간 또는 그 어느 것도 아닌지를 나타내는 값. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) 생성자

지정된 달력에서 특정 연도, 월, 일, 시, 분, 초 및 밀리초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| year | int | 구성되는 인스턴스가 나타내는 연도. |
| month | int | 구성되는 인스턴스가 나타내는 **연도**의 월. |
| day | int | 구성되는 인스턴스가 나타내는 **월**의 일. |
| hour | int | 구성되는 인스턴스가 나타내는 **일**의 시. |
| minute | int | 구성되는 인스턴스가 나타내는 **시**의 분. |
| second | int | 구성되는 인스턴스가 나타내는 **분**의 초. |
| millisecond | int | 구성되는 인스턴스가 나타내는 **초**의 밀리초. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 제공된 날짜 및 시간 매개변수가 로컬 시간, UTC 시간 또는 그 어느 것도 아닌지를 나타내는 값. |
| calendar | [DateTimeKind](../../datetimekind/) | 지정된 **연도**, **월**, **일**을 해석할 때 사용하는 달력. |

## DateTime::DateTime(int64_t, DateTimeKind) 생성자

틱 수로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ticks | **int64_t** | 그루지아 달력 기준 0001년 1월 1일 00:00:00.000부터 경과한 100ns 간격 수. |
| kind | [DateTimeKind](../../datetimekind/) | **ticks** 매개변수가 로컬 시간, UTC 시간 또는 그 어느 것도 아닌지를 나타내는 값. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) 생성자

틱 수로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. 내부 사용 전용.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ticks | **int64_t** | 그루지아 달력 기준 0001년 1월 1일 00:00:00.000부터 경과한 100ns 간격 수. |
| kind | [DateTimeKind](../../datetimekind/) | **ticks** 매개변수가 로컬 시간, UTC 시간 또는 그 어느 것도 아닌지를 나타내는 값. |
| is_ambiguous_local_dst | **bool** | 지정된 날짜와 시간이 모호하여 여러 UTC 시간에 매핑될 수 있는 경우 true. |

## DateTime::DateTime(const DateTime\&) 생성자

인스턴스를 복사 생성합니다.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dt | const [DateTime](../)\& | 복사할 [DateTime](../) 클래스의 인스턴스. |

## 참고

* 열거형 [DateTimeKind](../../datetimekind/)
* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [DateTime](../)
* 클래스 [Calendar](../../../system.globalization/calendar/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)