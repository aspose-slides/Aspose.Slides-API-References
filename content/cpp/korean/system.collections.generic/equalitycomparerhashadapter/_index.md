---
title: EqualityComparerHashAdapter
second_title: C++용 Aspose.Slides API 레퍼런스
description: 해싱에 IEqualityComparer를 사용하기 위한 어댑터입니다. 설정된 경우 비교자 객체를 사용하고, 그렇지 않으면 DictionaryHashSelector 구조체를 사용하여 선택된 사용 가능한 해시 메서드를 사용합니다.
type: docs
weight: 677
url: /ko/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

해싱에 [IEqualityComparer](../iequalitycomparer/)를 사용하기 위한 어댑터입니다. 설정된 경우 비교자 객체를 사용하고, 그렇지 않으면 [DictionaryHashSelector](../dictionaryhashselector/) 구조체를 사용하여 선택된 사용 가능한 해시 메서드를 사용합니다.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Hashed | 형식. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | 사용할 비교자 없이 어댑터를 생성합니다. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 지정된 비교자를 사용하여 어댑터를 생성합니다. |
| std::size_t [operator()](./operator_call/)(const T\&) const | 해시 값을 계산합니다. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 사용할 비교자를 설정합니다. |

## 참조

* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)