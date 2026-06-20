---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides for C++ API Reference
description: Template predicate that checks if boxed object should implement IComparable interface by itself.
type: docs
weight: 53
url: /system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Template predicate that checks if boxed object should implement [IComparable](../../system/icomparable/) interface by itself.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## See Also

* Namespace [System::BoxedValueDetail](../)
* Library [Aspose.Slides](../../)