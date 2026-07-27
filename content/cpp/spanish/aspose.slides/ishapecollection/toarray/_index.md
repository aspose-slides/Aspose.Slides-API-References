---
title: ToArray()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea y devuelve una matriz que contiene todas las formas.
type: docs
weight: 287
url: /es/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() method


Crea y devuelve una matriz que contiene todas las formas.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Valor de retorno

Una matriz de [IShape](../../ishape/) objetos.

## IShapeCollection::ToArray(int32_t, int32_t) method


Crea y devuelve una matriz que contiene todas las formas en el rango especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **int32_t** | El índice de la primera forma a devolver. |
| count | **int32_t** | El número de formas a devolver. |

### Valor de retorno

Una matriz de [IShape](../../ishape/) objetos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShape](../../ishape/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)