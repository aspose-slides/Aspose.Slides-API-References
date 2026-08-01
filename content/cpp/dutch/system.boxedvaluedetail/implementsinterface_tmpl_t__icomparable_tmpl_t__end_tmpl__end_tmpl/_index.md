---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides voor C++ API-referentie
description: Sjabloon-predikaat dat controleert of een verpakt object zelf de IComparable interface moet implementeren.
type: docs
weight: 53
url: /nl/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Sjabloon-predikaat dat controleert of een verpakt object zelf de [IComparable](../../system/icomparable/) interface moet implementeren.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Zie ook

* Naamruimte [System::BoxedValueDetail](../)
* Bibliotheek [Aspose.Slides](../../)