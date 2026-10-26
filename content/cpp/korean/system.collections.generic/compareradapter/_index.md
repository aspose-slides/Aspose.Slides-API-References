---
title: ComparerAdapter
second_title: Aspose.Slides for C++ API 레퍼런스
description: STL 환경에서 IComparer를 사용하기 위한 어댑터입니다. IComparer가 설정되어 있으면 사용하고, 그렇지 않으면 operator < (가능한 경우)를 사용하거나 사용 불가능한 경우 false를 반환합니다.
type: docs
weight: 638
url: /ko/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

STL 환경에서 [IComparer](../icomparer/)를 사용하기 위한 어댑터입니다. [IComparer](../icomparer/)가 설정되어 있으면 사용하고, 그렇지 않으면 operator < (가능한 경우) 를 사용하거나 사용할 수 없으면 false를 반환합니다.

```cpp
template<class T>class ComparerAdapter
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 비교되는 타입. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | 비교자가 제공되지 않은 상태에서 어댑터를 생성합니다. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | 어댑터를 생성합니다. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) 함수는 operator < 를 사용할 수 있는 타입에 대해 사용됩니다. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) 함수는 operator < 를 사용할 수 없는 타입에 대해 사용됩니다. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | 비교자 객체를 설정합니다. |

## 참고

* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)