---
title: MakeConstRef
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제네릭 타입이 String이거나 SmartPtr<> 타입인 경우 \"const reference\"를 만들기 위한 트레이트입니다.
type: docs
weight: 1769
url: /ko/system/makeconstref/
---
## MakeConstRef struct

제네릭 타입 \"const reference\"를 만들기 위한 트레이트이며, [String](../string/)이거나 SmartPtr<> 타입인 경우.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)