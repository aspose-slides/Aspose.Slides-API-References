---
title: crend()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido.
type: docs
weight: 300
url: /es/system.collections.specialized/stringcollection/crend/
---
## StringCollection::crend() const método

Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior.

```cpp
const_reverse_iterator System::Collections::Specialized::StringCollection::crend() const noexcept
```

### Valor de retorno

An iterator pointing to the theoretical const-qualified element preceding the first element of the container.

## Ver también

* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* Clase [StringCollection](../)
* Espacio de nombres [System::Collections::Specialized](../../)
* Biblioteca [Aspose.Slides](../../../)