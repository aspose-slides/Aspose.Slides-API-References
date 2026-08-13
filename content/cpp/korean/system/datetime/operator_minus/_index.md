---
title: operator-()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 값에서 지정된 시간 간격을 빼서 나온 결과인 날짜 및 시간 값을 나타내는 DateTime 클래스의 새 인스턴스를 반환합니다.
type: docs
weight: 651
url: /ko/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const 메서드


현재 객체가 나타내는 값에서 지정된 시간 간격을 빼서 나온 결과인 날짜 및 시간 값을 나타내는 [DateTime](../) 클래스의 새 인스턴스를 반환합니다.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | 빼야 할 시간 간격 |

### 반환 값

현재 객체가 나타내는 값에서 **value**를 빼서 나온 결과인 날짜 및 시간 값을 나타내는 [DateTime](../) 클래스의 새 인스턴스를 반환합니다.

## DateTime::operator-(DateTime) const 메서드


현재 객체와 지정된 객체가 나타내는 날짜 및 시간 값 사이의 시간 간격을 나타내는 [TimeSpan](../../timespan/) 클래스의 인스턴스를 반환합니다.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../) | 계산될 간격의 한 끝을 나타내는 [DateTime](../) 클래스의 인스턴스 |

### 반환 값

현재 객체와 **value**가 나타내는 날짜 및 시간 값 사이의 시간 간격을 나타내는 [TimeSpan](../../timespan/) 클래스의 인스턴스를 반환합니다.

## 참조

* 클래스 [DateTime](../)
* 클래스 [TimeSpan](../../timespan/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)