---
title: Subtract()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 값에서 지정된 시간 간격을 빼서 얻은 날짜와 시간 값을 나타내는 DateTime 클래스의 새 인스턴스를 반환합니다.
type: docs
weight: 326
url: /ko/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const 메서드

현재 객체가 나타내는 값에서 지정된 시간 간격을 빼서 얻은 날짜와 시간 값을 나타내는 [DateTime](../) 클래스의 새 인스턴스를 반환합니다.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | 뺄 시간 간격 |

### 반환값

현재 객체가 나타내는 값에서 **duration**을(를) 빼서 얻은 날짜와 시간 값을 나타내는 [DateTime](../) 클래스의 새 인스턴스를 반환합니다.

## DateTime::Subtract(DateTime) const 메서드

현재 객체와 지정된 객체가 나타내는 날짜 및 시간 값 사이의 시간 간격을 나타내는 [TimeSpan](../../timespan/) 클래스의 인스턴스를 반환합니다.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../) | [DateTime](../) 클래스의 인스턴스로, 계산될 간격의 한쪽 끝을 표시합니다 |

### 반환값

현재 객체와 **value**가 나타내는 날짜 및 시간 값 사이의 시간 간격을 나타내는 [TimeSpan](../../timespan/) 클래스의 인스턴스를 반환합니다.

## 참조

* 클래스 [DateTime](../)
* 클래스 [TimeSpan](../../timespan/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)