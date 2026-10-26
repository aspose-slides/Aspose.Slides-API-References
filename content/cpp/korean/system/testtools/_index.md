---
title: TestTools
second_title: Aspose.Slides for C++ API 참조
description: 다양한 유형 및 함수의 기본 속성을 확인하는 유용한 메서드 집합을 제공합니다.
type: docs
weight: 1925
url: /ko/system/testtools/
---
## TestTools struct

다양한 유형 및 함수의 기본 속성을 확인하는 유용한 메서드 집합을 제공합니다.

```cpp
class TestTools
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | 함수가 어떤 유형의 예외든 발생하는지 확인합니다. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | 문자열이 비어 있는지 확인합니다. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 컬렉션이 비어 있는지 확인합니다. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | 특정 값이 null인지 확인합니다. [Version](../version/) 산술 및 열거형 타입에 대해. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | 특정 값이 null인지 확인합니다. [Version](../version/) 비산술 및 비열거형 값 타입에 대해. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 특정 값이 null인지 확인합니다. [Version](../version/) 비산술 값 타입에 대해. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | 특정 값이 null인지 확인합니다. [Version](../version/) 키-값 쌍에 대해. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | 문자열이 null인지 확인합니다. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 컬렉션이 null이거나 비어 있는지 확인합니다. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | 문자열이 null이거나 비어 있는지 확인합니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)