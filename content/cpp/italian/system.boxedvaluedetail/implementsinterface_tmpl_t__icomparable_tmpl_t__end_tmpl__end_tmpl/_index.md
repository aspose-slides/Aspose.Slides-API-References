---
title: ImplementsInterface< T, IComparable< T > >
second_title: Riferimento API di Aspose.Slides per C++
description: Predicato di modello che verifica se l'oggetto incapsulato deve implementare l'interfaccia IComparable da solo.
type: docs
weight: 53
url: /it/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct

Predicato di modello che verifica se l'oggetto incapsulato deve implementare l'interfaccia [IComparable](../../system/icomparable/) da solo.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Vedi anche

* Spazio dei nomi [System::BoxedValueDetail](../)
* Libreria [Aspose.Slides](../../)