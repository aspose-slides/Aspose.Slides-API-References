---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides para C++ Referência da API
description: Predicado de modelo que verifica se o objeto encapsulado deve implementar a interface IComparable por si mesmo.
type: docs
weight: 53
url: /pt/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct

Predicado de modelo que verifica se o objeto encapsulado deve implementar a interface [IComparable](../../system/icomparable/) por si mesmo.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Veja Também

* Espaço de nomes [System::BoxedValueDetail](../)
* Biblioteca [Aspose.Slides](../../)