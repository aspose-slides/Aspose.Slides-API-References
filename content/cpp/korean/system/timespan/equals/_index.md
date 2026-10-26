---
title: Equals()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격과 같은지 여부를 판단합니다.
type: docs
weight: 40
url: /ko/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const 메서드

현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격과 같은지 여부를 판단합니다.

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TimeSpan](../) | 현재 객체와 비교할 [TimeSpan](../) 객체 |

### 반환값

현재 객체와 지정된 객체가 동일한 시간 간격을 나타내면 true, 그렇지 않으면 false

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const 메서드

현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격과 같은지 여부를 판단합니다.

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 현재 객체와 비교할 [TimeSpan](../) 객체 |

### 반환값

현재 객체와 지정된 객체가 동일한 시간 간격을 나타내면 true, 그렇지 않으면 false

## TimeSpan::Equals(TimeSpan, TimeSpan) 메서드

지정된 객체들이 동일한 시간 간격을 나타내면 true, 그렇지 않으면 false.

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## 또한 보기

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [TimeSpan](../)
* 클래스 [Object](../../object/)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)