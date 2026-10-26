---
title: MakeConstRef
second_title: Referencia de API de Aspose.Slides para C++
description: Rasgo para crear un tipo genérico \"referencia constante\" si es String o un tipo SmartPtr<>.
type: docs
weight: 1769
url: /es/system/makeconstref/
---
## MakeConstRef struct

Rasgo para crear un tipo genérico \"referencia constante\" si es [String](../string/) o un tipo SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)