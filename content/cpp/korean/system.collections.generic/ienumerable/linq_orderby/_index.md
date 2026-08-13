---
title: LINQ_OrderBy()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 키 선택기(keySelector)에 의해 선택된 키 값을 기준으로 시퀀스의 요소를 오름차순으로 정렬합니다.
type: docs
weight: 209
url: /ko/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) 메서드

키 선택기(keySelector)에 의해 선택된 키 값을 기준으로 시퀀스의 요소를 오름차순으로 정렬합니다.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| keySelector | 요소에서 키를 추출하는 함수. |

### 반환값

키에 따라 요소가 정렬된 IOrderedEnumerable

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) 메서드

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* 클래스 [Func](../../../system/func/)
* 클래스 [IEnumerable](../)
* 네임스페이스 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)