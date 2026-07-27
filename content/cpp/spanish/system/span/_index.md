---
title: Span
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa una región contigua de memoria arbitraria similar a std::span de C++20."
type: docs
weight: 1262
url: /es/system/span/
---
## Clase Span


Representa una región contigua de memoria arbitraria similar a std::span de C++20.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span. Esta clase proporciona una forma tipada de trabajar con secuencias contiguas de objetos. Puede usarse para envolver matrices, matrices de pila o punteros sin procesar mientras se mantiene la comprobación de límites. El [Span](./) no posee la memoria a la que apunta, solo es una vista de la memoria existente. |
## Métodos

| Método | Descripción |
| --- | --- |
| void [Clear](./clear/)() const | Borra el contenido del span estableciendo todos los elementos al valor predeterminado. |
| void [Fill](./fill/)(const T\&) const | Rellena el span con el valor especificado. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Convierte una matriz a un [Span](./). |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)