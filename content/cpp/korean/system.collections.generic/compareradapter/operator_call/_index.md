---
title: operator()()
second_title: Aspose.Slides for C++ API 참조
description: operator < 를 사용할 수 있는 타입에 대한 비교 함수입니다.
type: docs
weight: 27
url: /ko/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const 메서드

[Comparison](../../../system/comparison/) 함수는 operator < 가 사용 가능한 타입에 대해 제공됩니다.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 비교되는 타입; 타입 변환 가능성을 위한 템플릿. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | const Q\& | 비교할 첫 번째 값. |
| y | const Q\& | 비교할 두 번째 값. |

### 반환값

True이면 **x**가 **y**보다 작다고 간주되며, 그렇지 않으면 false입니다.

## ComparerAdapter::operator()(const Q\&, const Q\&) const 메서드

[Comparison](../../../system/comparison/) 함수는 operator < 가 사용 불가능한 타입에 대해 제공됩니다.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 비교되는 타입; 타입 변환 가능성을 위한 템플릿. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | const Q\& | 비교할 첫 번째 값. |
| y | const Q\& | 비교할 두 번째 값. |

### 반환값

True이면 비교기가 설정되어 있고 **x**가 **y**보다 작다고 간주되며, 그렇지 않으면 false입니다.

## 관련 항목

* 구조체 [ComparerAdapter](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)