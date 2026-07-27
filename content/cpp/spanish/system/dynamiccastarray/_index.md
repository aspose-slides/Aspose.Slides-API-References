---
title: DynamicCastArray()
second_title: Aspose.Slides para la referencia de la API de C++
description: Realiza la conversión de los elementos de la matriz especificada a un tipo diferente.
type: docs
weight: 2991
url: /es/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) función


Realiza la conversión de los elementos de la matriz especificada a un tipo diferente.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que se convierten los elementos de la matriz especificada |
| From | El tipo de los elementos de la matriz cuyos elementos se van a convertir |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Puntero compartido a la matriz que contiene los elementos a convertir |

### Valor devuelto

Un puntero a una nueva matriz que contiene elementos del tipo **To** equivalentes a los elementos de **from**

Obsoleto
:   Añadido por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Clase [Array](../array/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)