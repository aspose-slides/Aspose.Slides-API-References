---
title: operator<=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 지정된 DateTimeOffset 객체가 나타내는 값보다 이전이거나 동일한 날짜 및 시간 값을 나타내는지 확인합니다.
type: docs
weight: 586
url: /ko/system/datetimeoffset/operator_less_equal/
---
## DateTimeOffset::operator<=(const DateTimeOffset\&) const 메서드


현재 객체가 지정된 [DateTimeOffset](../) 객체가 나타내는 값보다 이전이거나 동일한 날짜 및 시간 값을 나타내는지 확인합니다.

```cpp
bool System::DateTimeOffset::operator<=(const DateTimeOffset &other) const
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 현재 객체와 비교할 [DateTimeOffset](../) 객체 |

### 반환값

True if the date and time value represented by the current object is earlier than or the same as the value represented by **other**, otherwise - false

## DateTimeOffset::operator<=(std::nullptr_t) const 메서드




```cpp
constexpr bool System::DateTimeOffset::operator<=(std::nullptr_t) const
```

## 참고

* 클래스 [DateTimeOffset](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)