---
title: operator-()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 값에서 지정된 시간 간격을 빼서 얻은 결과인 날짜 및 시간 값을 나타내는 DateTimeOffset 클래스의 새 인스턴스를 반환합니다.
type: docs
weight: 521
url: /ko/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const 메서드

현재 객체가 나타내는 값에서 지정된 시간 간격을 빼는 결과인 날짜 및 시간 값을 나타내는 [DateTimeOffset](../) 클래스를 새 인스턴스로 반환합니다.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | 빼야 할 시간 간격 |

### 반환값

현재 객체가 나타내는 값에서 **value**를 빼는 결과인 날짜 및 시간 값을 나타내는 [DateTimeOffset](../) 클래스의 새 인스턴스를 반환합니다.

## DateTimeOffset::operator-(const DateTimeOffset\&) const 메서드

현재 객체와 지정된 객체가 나타내는 날짜 및 시간 값 사이의 시간 간격을 나타내는 [TimeSpan](../../timespan/) 클래스의 인스턴스를 반환합니다.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 계산될 구간의 한쪽 끝을 표시하는 [DateTime](../../datetime/) 클래스의 인스턴스 |

### 반환값

현재 객체와 **other**가 나타내는 날짜 및 시간 값 사이의 시간 간격을 나타내는 [TimeSpan](../../timespan/) 클래스의 인스턴스를 반환합니다.

## 참고

* 클래스 [DateTimeOffset](../)
* 클래스 [TimeSpan](../../timespan/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)