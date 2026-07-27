---
title: TrueForAll()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si todos los elementos en la matriz especificada cumplen con las condiciones definidas por el predicado especificado.
type: docs
weight: 677
url: /es/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) method


Determina si todos los elementos en la matriz especificada cumplen con las condiciones definidas por el predicado especificado.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elementos de los cuales se deben comparar con las condiciones |
| match | [System::Predicate](../../predicate/)\<T\> | Un predicado que define las condiciones contra las que comparar los elementos de la matriz |

### Valor devuelto

true si todos los elementos de la matriz arr cumplen con las condiciones definidas por el predicado match, de lo contrario false

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)