---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides pro C++ API Reference
description: Šablonový predikát, který kontroluje, zda má zabalený objekt sám implementovat rozhraní IComparable.
type: docs
weight: 53
url: /cs/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Šablonový predikát, který kontroluje, zda má zabalený objekt sám implementovat rozhraní [IComparable](../../system/icomparable/).

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Viz také

* Jmenný prostor [System::BoxedValueDetail](../)
* Knihovna [Aspose.Slides](../../)