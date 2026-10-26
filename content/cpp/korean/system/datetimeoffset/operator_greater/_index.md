---
title: operator>()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 현재 객체가 지정된 DateTimeOffset 객체가 나타내는 값보다 나중인 날짜 및 시간 값을 나타내는지 판단합니다.
type: docs
weight: 573
url: /ko/system/datetimeoffset/operator_greater/
---
## DateTimeOffset::operator>(const DateTimeOffset\&) const method

현재 객체가 지정된 [DateTimeOffset](../) 객체가 나타내는 값보다 나중인 날짜 및 시간 값을 나타내는지 확인합니다.

```cpp
bool System::DateTimeOffset::operator>(const DateTimeOffset &other) const
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 현재 객체와 비교할 [DateTimeOffset](../) 객체 |

### 반환 값

True if the date and time value represented by the current object is later than the value represented by **other**, otherwise - false

## DateTimeOffset::operator>(std::nullptr_t) const method

```cpp
constexpr bool System::DateTimeOffset::operator>(std::nullptr_t) const
```

## 참고

* 클래스 [DateTimeOffset](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)