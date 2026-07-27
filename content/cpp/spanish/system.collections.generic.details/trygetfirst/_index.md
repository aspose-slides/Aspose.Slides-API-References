---
title: TryGetFirst()
second_title: Referencia de la API de Aspose.Slides para C++
description: Intenta obtener el primer elemento de la colección.
type: docs
weight: 248
url: /es/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) función

Intenta obtener el primer elemento de la colección.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la colección. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La colección de la cual se va a adquirir un elemento. |
| found | **bool**\& | El parámetro de salida. Devuelve true cuando la colección contiene algún elemento. De lo contrario se devuelve false. |

### Valor de retorno

Devuelve el primer elemento de la colección. Se devolverá el valor predeterminado del tipo cuando la colección esté vacía.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) función

Intenta obtener el primer elemento de la colección que satisface la función predicado.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la colección. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La colección de la cual se va a adquirir un elemento. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | La función predicado. |
| found | **bool**\& | El parámetro de salida. Devuelve true cuando la colección contiene algún elemento. De lo contrario se devuelve false. |

### Valor de retorno

Devuelve el primer elemento de la colección. Se devolverá el valor predeterminado del tipo cuando no se encuentre ningún elemento que satisfaga la función predicado especificada.

## Véase también

* Clase [IEnumerable](../../system.collections.generic/ienumerable/)
* Clase [Func](../../system/func/)
* Espacio de nombres [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)