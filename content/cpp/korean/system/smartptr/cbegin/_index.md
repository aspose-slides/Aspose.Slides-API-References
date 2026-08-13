---
title: cbegin()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하위 컬렉션의 cbegin() 메서드에 대한 접근자입니다. SmartPtr_가 cbegin() 메서드를 갖는 특수화 타입인 경우에만 컴파일됩니다.
type: docs
weight: 404
url: /ko/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const 메서드

하위 컬렉션의 [cbegin()](./) 메서드에 대한 접근자입니다. SmartPtr_가 [cbegin()](./) 메서드를 갖는 특수화 타입인 경우에만 컴파일됩니다.

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### 반환 값

컬렉션 시작 부분에 대한 iterator

## 참조

* 클래스 [SmartPtr](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)