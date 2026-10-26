---
title: Equals()
second_title: Aspose.Slides for C++ API 레퍼런스
description: operator==()를 사용하여 지정된 값의 동일성을 결정합니다.
type: docs
weight: 66
url: /ko/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) 함수

지정된 값의 동일성을 [operator==()](../../system/operator_equal_equal/)를 사용하여 결정합니다.

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| The | 비교되는 값들의 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | 첫 번째 피연산자 |
| value2 | T | 두 번째 피연산자 |

### 반환값

지정된 값이 [operator==()](../../system/operator_equal_equal/)에 의해 결정된 대로 동일하면 true, 그렇지 않으면 false

## System::BoxedValueDetail::Equals(T, T) 함수

지정된 값의 동일성을 [System::Object::Equals()](../../system/object/equals/) 메서드를 사용하여 결정합니다.

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| The | 비교되는 값들의 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | 첫 번째 피연산자 |
| value2 | T | 두 번째 피연산자 |

### 반환값

지정된 값이 [Equals()](./) 메서드에 의해 결정된 대로 동일하면 true, 그렇지 않으면 false

## 관련 항목

* Namespace [System::BoxedValueDetail](../)
* Library [Aspose.Slides](../../)