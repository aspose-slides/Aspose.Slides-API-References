---
title: CompareTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체와 지정된 객체를 비교합니다.
type: docs
weight: 27
url: /ko/system/timespan/compareto/
---
## TimeSpan::CompareTo(TimeSpan) const 메서드

현재 객체와 지정된 객체를 비교합니다.

```cpp
constexpr int System::TimeSpan::CompareTo(TimeSpan value) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TimeSpan](../) | 현재 객체와 비교할 [TimeSpan](../) 객체 |

### 반환 값

- 1: 현재 객체가 **value**보다 짧은 구간을 나타내는 경우; 0: 현재 객체가 **value**와 같은 구간을 나타내는 경우; 1: 현재 객체가 **value**보다 긴 구간을 나타내는 경우

## TimeSpan::CompareTo(const SharedPtr\<Object\>\&) const 메서드

현재 객체와 지정된 객체를 비교합니다.

```cpp
int System::TimeSpan::CompareTo(const SharedPtr<Object> &obj) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 현재 객체와 비교할 [TimeSpan](../) 객체 |

### 반환 값

- 1: 현재 객체가 **value**보다 짧은 구간을 나타내는 경우; 0: 현재 객체가 **value**와 같은 구간을 나타내는 경우; 1: 현재 객체가 **value**보다 긴 구간을 나타내는 경우

## 참조

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [TimeSpan](../)
* 클래스 [Object](../../object/)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)