---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides for C++ API 레퍼런스
description: 박스된 객체가 IComparable 인터페이스를 자체적으로 구현해야 하는지 확인하는 템플릿 술어입니다.
type: docs
weight: 53
url: /ko/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


박스된 객체가 [IComparable](../../system/icomparable/) 인터페이스를 자체적으로 구현해야 하는지 확인하는 템플릿 술어.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## 참조

* 네임스페이스 [System::BoxedValueDetail](../)
* 라이브러리 [Aspose.Slides](../../)