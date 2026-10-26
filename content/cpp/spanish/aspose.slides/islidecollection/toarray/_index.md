---
title: ToArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea y devuelve una matriz con todas las diapositivas.
type: docs
weight: 92
url: /es/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() método

Crea y devuelve una matriz con todas las diapositivas.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### Valor devuelto

Matriz de [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) método

Crea y devuelve una matriz con todas las diapositivas del rango especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **int32_t** | Un índice de la primera diapositiva a añadir. |
| count | **int32_t** | Un número de diapositivas a añadir. |

### Valor devuelto

Matriz de [ISlide](../../islide/)

## Véase también

* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [ISlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)