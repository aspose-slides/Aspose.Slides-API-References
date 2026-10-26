---
title: ImplementsInterface< T, IComparable< T > >
second_title: Referencia de API de Aspose.Slides para C++
description: Predicado de plantilla que verifica si un objeto en caja debe implementar la interfaz IComparable por sí mismo.
type: docs
weight: 53
url: /es/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct

Predicado de plantilla que verifica si un objeto en caja debe implementar la interfaz [IComparable](../../system/icomparable/) por sí mismo.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Ver también

* Espacio de nombres [System::BoxedValueDetail](../)
* Biblioteca [Aspose.Slides](../../)