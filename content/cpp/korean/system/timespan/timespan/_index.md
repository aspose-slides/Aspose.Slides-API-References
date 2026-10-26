---
title: TimeSpan()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 0 시간 간격을 나타내는 TimeSpan 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system/timespan/timespan/
---
## TimeSpan::TimeSpan() 생성자

[TimeSpan](../) 개체를 생성하며, 이는 0 시간 간격을 나타냅니다.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) 생성자

[TimeSpan](../) 클래스를 인스턴스화하여 지정된 시간 간격을 나타냅니다.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ticks | **int64_t** | 구축 중인 인스턴스가 나타낼 시간 간격으로, 100나노초 간격 수로 표현됩니다. |

## TimeSpan::TimeSpan(int, int, int) 생성자

[TimeSpan](../) 클래스를 인스턴스화하여 지정된 시간, 분, 초의 합과 같은 시간 간격을 나타냅니다.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hours | int | 구축 중인 인스턴스가 나타낼 시간 간격의 시간 구성 요소에 해당하는 시간 수 |
| minutes | int | 구축 중인 인스턴스가 나타낼 시간 간격의 분 구성 요소에 해당하는 분 수 |
| seconds | int | 구축 중인 인스턴스가 나타낼 시간 간격의 초 구성 요소에 해당하는 초 수 |

## TimeSpan::TimeSpan(int, int, int, int, int) 생성자

[TimeSpan](../) 클래스를 인스턴스화하여 지정된 시간, 분, 초 및 밀리초의 합과 같은 시간 간격을 나타냅니다.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| days | int | 구축 중인 인스턴스가 나타낼 시간 간격의 일 구성 요소에 해당하는 일 수 |
| hours | int | 구축 중인 인스턴스가 나타낼 시간 간격의 시간 구성 요소에 해당하는 시간 수 |
| minutes | int | 구축 중인 인스턴스가 나타낼 시간 간격의 분 구성 요소에 해당하는 분 수 |
| seconds | int | 구축 중인 인스턴스가 나타낼 시간 간격의 초 구성 요소에 해당하는 초 수 |
| milliseconds | int | 구축 중인 인스턴스가 나타낼 시간 간격의 밀리초 구성 요소에 해당하는 밀리초 수 |

## TimeSpan::TimeSpan(const TimeSpan\&) 생성자

[TimeSpan](../) 객체를 생성하며, 이는 지정된 [TimeSpan](../) 객체가 나타내는 시간 간격과 동일합니다.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## 참조

* 클래스 [TimeSpan](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)