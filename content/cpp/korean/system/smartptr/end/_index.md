---
title: end()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하위 컬렉션의 end() 메서드에 대한 액세서이며, SmartPtr_이 end() 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다.
type: docs
weight: 391
url: /ko/system/smartptr/end/
---
## SmartPtr::end() 메서드

하위 컬렉션의 [end()](./) 메서드에 대한 액세서이며, SmartPtr_이 [end()](./) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### 반환값

컬렉션 끝을 가리키는 iterator

## SmartPtr::end() const 메서드

하위 컬렉션의 [end()](./) 메서드에 대한 액세서이며, SmartPtr_이 [end()](./) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### 반환값

컬렉션 끝을 가리키는 iterator

## 참고

* 클래스 [SmartPtr](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)