---
title: LINQ_GroupBy()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시퀀스의 요소들을 그룹화합니다.
type: docs
weight: 287
url: /ko/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) 메서드


시퀀스의 요소들을 그룹화합니다.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Key | keyPredicate에 의해 반환되는 키의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | 각 요소에 대한 키를 추출하는 함수. |

### 반환 값

객체 시퀀스와 키를 포함하는 [IEnumerable](../)

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) 메서드


시퀀스의 요소들을 그룹화합니다.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Key | keyPredicate에 의해 반환되는 키의 형식 |
| Element | elementSelector에 의해 반환되는 요소의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | 각 요소에 대한 키를 추출하는 함수. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | 각 요소에 대한 값 키를 추출하는 함수. |

### 반환 값

객체 시퀀스와 키를 포함하는 [IEnumerable](../)

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) 메서드




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) 메서드




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IEnumerable](../)
* 클래스 [IGrouping](../../../system.linq/igrouping/)
* 클래스 [Func](../../../system/func/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)