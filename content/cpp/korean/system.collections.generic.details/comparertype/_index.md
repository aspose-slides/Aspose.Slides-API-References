---
title: ComparerType
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소를 'less' 의미를 사용하여 비교합니다.
type: docs
weight: 144
url: /ko/system.collections.generic.details/comparertype/
---
## ComparerType struct

요소를 'less' 의미를 사용하여 비교합니다.

```cpp
template<typename T>class ComparerType
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 비교되는 요소 유형. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [IComparable](../../system/icomparable/) 인터페이스를 구현하는 값 유형을 비교합니다. |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [IComparable](../../system/icomparable/) 인터페이스를 구현하지 않는 원시 값 유형 및 객체를 비교합니다. |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | 부동 소수점 유형을 비교합니다. |

## 참고

* 네임스페이스 [System::Collections::Generic::Details](../)
* 라이브러리 [Aspose.Slides](../../)