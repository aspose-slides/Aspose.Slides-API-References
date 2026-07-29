---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides för C++ API-referens
description: Mallpredikat som kontrollerar om ett inkapslat objekt ska implementera IComparable-gränssnittet själv.
type: docs
weight: 53
url: /sv/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Mallpredikat som kontrollerar om ett inkapslat objekt ska implementera [IComparable](../../system/icomparable/) gränssnittet själv.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Se också

* Namnrymd [System::BoxedValueDetail](../)
* Bibliotek [Aspose.Slides](../../)