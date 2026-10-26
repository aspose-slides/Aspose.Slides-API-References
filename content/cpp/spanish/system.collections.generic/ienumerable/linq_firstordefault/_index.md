---
title: LINQ_FirstOrDefault()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el primer elemento de una secuencia, o un valor predeterminado si la secuencia está vacía.
type: docs
weight: 66
url: /es/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() método

Devuelve el primer elemento de una secuencia, o un valor predeterminado si la secuencia está vacía.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### Valor de retorno

Primer elemento de la secuencia o valor construido por defecto si la secuencia está vacía.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) método

Devuelve el primer elemento de la secuencia que satisface una condición o un valor predeterminado si no se encuentra tal elemento.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Una función para probar cada elemento con una condición. |

### Valor de retorno

default(T) si la fuente está vacía o si ningún elemento pasa la prueba especificada por predicate; de lo contrario, el primer elemento en source que pasa la prueba especificada por predicate.

## Ver también

* Clase [IEnumerable](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)