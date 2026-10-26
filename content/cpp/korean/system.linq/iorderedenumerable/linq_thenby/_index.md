---
title: LINQ_ThenBy()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 키에 따라 시퀀스의 요소들을 오름차순으로 후속 정렬합니다.
type: docs
weight: 27
url: /ko/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) 메서드


키에 따라 시퀀스의 요소들을 오름차순으로 후속 정렬합니다.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| Key | keySelector가 반환하는 키의 타입입니다. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | 각 요소에서 키를 추출하는 함수입니다. |

### 반환 값

[System::Linq::IOrderedEnumerable](../) 그 요소들이 키에 따라 정렬된.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) 메서드




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IOrderedEnumerable](../)
* 클래스 [Func](../../../system/func/)
* 네임스페이스 [System::Linq](../../)
* Library [Aspose.Slides](../../../)