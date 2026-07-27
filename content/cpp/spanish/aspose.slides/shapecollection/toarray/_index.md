---
title: ToArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea y devuelve una matriz que contiene todas las formas.
type: docs
weight: 326
url: /es/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() método

Crea y devuelve una matriz que contiene todas las formas.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Valor devuelto

Una matriz de [IShape](../../ishape/) objetos.

## ShapeCollection::ToArray(int32_t, int32_t) método

Crea y devuelve una matriz que contiene todas las formas en el rango especificado.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **int32_t** | El índice de la primera forma a devolver. |
| count | **int32_t** | El número de formas a devolver. |

### Valor devuelto

Una matriz de [IShape](../../ishape/) objetos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShape](../../ishape/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)