---
title: InsertClone()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado.
type: docs
weight: 560
url: /es/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) método

Crea una copia de la forma especificada e la inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se debe insertar la forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |
| width | **float** | El ancho del marco de la forma clonada, en puntos. |
| height | **float** | La altura del marco de la forma clonada, en puntos. |

### Valor devuelto

El [IShape](../../ishape/) recién creado.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) método

Crea una copia de la forma especificada e la inserta en la colección de formas en el índice especificado. La nueva forma conserva el ancho y la altura del *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se debe insertar la forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |

### Valor devuelto

El [IShape](../../ishape/) recién creado.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) método

Crea una copia de la forma especificada e la inserta en la colección de formas en el índice especificado. La forma clonada conserva la posición y el tamaño del original.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se debe insertar la forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a clonar. |

### Valor devuelto

El [IShape](../../ishape/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShape](../../ishape/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)