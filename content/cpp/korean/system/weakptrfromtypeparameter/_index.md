---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides for C++ API 레퍼런스
description: 인수 유형을 약한 포인터로 변환하는 트레잇 구조체이며, 인수가 포인터 유형인 경우에만 적용됩니다.
type: docs
weight: 2016
url: /ko/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter 구조체


Trait 구조체는 인수 유형을 약한 포인터로 변환합니다. 인수가 포인터 유형인 경우에만 적용됩니다.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)