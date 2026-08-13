---
title: operator()()
second_title: Aspose.Slides C++ API 레퍼런스
description: IComparable 인터페이스를 구현하는 값 형식을 비교합니다.
type: docs
weight: 1
url: /ko/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const method

[IComparable](../../../system/icomparable/) 인터페이스를 구현하는 값 형식을 비교합니다.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| Q | 비교할 형식. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | 좌변 값. |
| b | const Q\& | 우변 값. |

### 반환 값

**a**가 **b**보다 작다고 판단되면 true, 그렇지 않으면 false.

## ComparerType::operator()(const Q\&, const Q\&) const method

[IComparable](../../../system/icomparable/) 인터페이스를 구현하지 않는 원시 값 형식 및 객체를 비교합니다.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| Q | 비교할 형식. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | 좌변 값. |
| b | const Q\& | 우변 값. |

### 반환 값

**a**가 **b**보다 작다고 판단되면 true, 그렇지 않으면 false.

## ComparerType::operator()(const Q\&, const Q\&) const method

부동 소수점 형식을 비교합니다.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| Q | 비교할 형식. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | 좌변 값. |
| b | const Q\& | 우변 값. |

### 반환 값

**a**가 **b**보다 작다고 판단되면 true, 그렇지 않으면 false.

## 관련 항목

* 클래스 [IComparable](../../../system/icomparable/)
* 구조체 [has_method_compareto](../../has_method_compareto/)
* 구조체 [ComparerType](../)
* 네임스페이스 [System::Collections::Generic::Details](../../)
* 라이브러리 [Aspose.Slides](../../../)