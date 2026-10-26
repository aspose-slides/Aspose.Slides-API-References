---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides für C++ API-Referenz
description: Template-Prädikat, das prüft, ob das geboxte Objekt selbst die IComparable-Schnittstelle implementieren soll.
type: docs
weight: 53
url: /de/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct

Template-Prädikat, das prüft, ob das geboxte Objekt selbst die [IComparable](../../system/icomparable/) Schnittstelle implementieren soll.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Siehe auch

* Namensraum [System::BoxedValueDetail](../)
* Bibliothek [Aspose.Slides](../../)