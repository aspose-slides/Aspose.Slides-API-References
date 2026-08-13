---
title: cend()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하위 컬렉션의 cend() 메서드에 대한 접근자입니다. SmartPtr_이 cend() 메서드를 갖는 특수화 타입인 경우에만 컴파일됩니다.
type: docs
weight: 417
url: /ko/system/smartptr/cend/
---
## SmartPtr::cend() const 메서드

하위 컬렉션의 [cend()](./) 메서드에 대한 접근자입니다. SmartPtr_이 [cend()](./) 메서드를 갖는 특수화 타입인 경우에만 컴파일됩니다.

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### 반환 값

컬렉션 끝을 가리키는 iterator

## 참고

* 클래스 [SmartPtr](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)