---
title: ReadOnlySpan
second_title: Referencia de la API de Aspose.Slides para C++
description: Reenvío para usar dentro de la clase Span.
type: docs
weight: 1210
url: /es/system/readonlyspan/
---
## Clase ReadOnlySpan

Reenvío para usar dentro de la clase [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span. Esta clase proporciona una forma segura de tipos para trabajar con secuencias contiguas de objetos de manera de solo lectura. Puede usarse para envolver matrices, matrices de pila o punteros sin procesar manteniendo la comprobación de límites. El [ReadOnlySpan](./) no posee la memoria a la que apunta; solo es una vista de la memoria existente. |

## Métodos

| Método | Descripción |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Construye un span de solo lectura a partir de un span regular. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Convierte una matriz a un [ReadOnlySpan](./). |

## Observaciones

Representa una región contigua de solo lectura de memoria arbitraria.

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)