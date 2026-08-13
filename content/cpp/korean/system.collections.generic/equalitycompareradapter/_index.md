---
title: EqualityComparerAdapter
second_title: Aspose.Slides for C++ API 참조
description: "IEqualityComparer를 사용하여 STL 스타일 컬렉션 및 알고리즘을 사용할 수 있게 하는 어댑터입니다. 설정된 경우 IEqualityComparer를 사용합니다. 설정되지 않은 경우 operator ==, Object::Equals 또는 T::Equals 중 사용 가능한 것을 사용합니다."
type: docs
weight: 664
url: /ko/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter 구조체


STL 스타일 컬렉션 및 알고리즘과 함께 [IEqualityComparer](../iequalitycomparer/)을 사용할 수 있도록 하는 어댑터입니다. 설정된 경우 [IEqualityComparer](../iequalitycomparer/)를 사용합니다. 설정되지 않은 경우 operator ==, [Object::Equals](../../system/object/equals/) 또는 T::Equals 중 사용 가능한 것을 사용합니다.

```cpp
template<class T>class EqualityComparerAdapter
```


### Template parameters

| 매개변수 | 설명 |
| --- | --- |
| T | 비교되는 타입. |
## Methods

| 메서드 | 설명 |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | 비교자를 사용하지 않는 어댑터를 생성합니다. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 주어진 비교자를 사용하여 어댑터를 생성합니다. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | 두 객체를 비교합니다. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 비교자를 설정합니다. |

## 참조

* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)