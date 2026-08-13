---
title: LINQ_OrderByDescending()
second_title: C++용 Aspose.Slides API 레퍼런스
description: keySelector가 선택한 키 값에 따라 시퀀스의 요소를 내림차순으로 정렬합니다.
type: docs
weight: 222
url: /ko/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) 메서드

시퀀스의 요소를 keySelector가 선택한 키값에 따라 내림차순으로 정렬합니다.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| keySelector | 요소에서 키를 추출하는 함수. |

### 반환 값

키의 내림차순으로 정렬된 요소를 가진 IOrderedEnumerable

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) 메서드




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)