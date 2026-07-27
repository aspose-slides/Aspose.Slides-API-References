---
title: TryGetLast()
second_title: Referencia de API de Aspose.Slides para C++
description: Intenta obtener el último elemento de la colección.
type: docs
weight: 261
url: /es/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) function

Intenta obtener el último elemento de la colección.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la colección. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La colección de la cual se adquirirá un elemento. |
| found | **bool**\& | El parámetro de salida. Devuelve true cuando la colección contiene algún elemento. De lo contrario se devuelve false. |

### Valor devuelto

Devuelve el último elemento de la colección. Se devolverá el valor predeterminado del tipo cuando la colección esté vacía.

## Ver también

* Clase [IEnumerable](../../system.collections.generic/ienumerable/)
* Espacio de nombres [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)