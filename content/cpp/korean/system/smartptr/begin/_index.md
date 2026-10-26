---
title: begin()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하위 컬렉션의 begin() 메서드에 대한 접근자입니다. SmartPtr_이 begin() 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다.
type: docs
weight: 378
url: /ko/system/smartptr/begin/
---
## SmartPtr::begin() 메서드


하위 컬렉션의 [begin()](./) 메서드에 대한 접근자입니다. SmartPtr_이 [begin()](./) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### 반환 값

컬렉션의 시작을 가리키는 iterator

## SmartPtr::begin() const 메서드


하위 컬렉션의 [begin()](./) 메서드에 대한 접근자입니다. SmartPtr_이 [begin()](./) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### 반환 값

컬렉션의 시작을 가리키는 iterator

## 참고

* 클래스 [SmartPtr](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)