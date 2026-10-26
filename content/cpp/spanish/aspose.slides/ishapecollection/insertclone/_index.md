---
title: InsertClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de la forma especificada e inserta la forma en la colección de formas en el índice especificado.
type: docs
weight: 508
url: /es/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) método


Crea una copia de la forma especificada e inserta la forma en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |
| width | **float** | El ancho del marco de la forma clonada, en puntos. |
| height | **float** | La altura del marco de la forma clonada, en puntos. |

### Valor de retorno

El [IShape](../../ishape/) recién creado.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) método


Crea una copia de la forma especificada e inserta la forma en la colección de formas en el índice especificado. La nueva forma conserva el ancho y la altura del *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |

### Valor de retorno

El [IShape](../../ishape/) recién creado.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) método


Crea una copia de la forma especificada e inserta la forma en la colección de formas en el índice especificado. La forma clonada conserva la posición y el tamaño del original.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a clonar. |

### Valor de retorno

El [IShape](../../ishape/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)