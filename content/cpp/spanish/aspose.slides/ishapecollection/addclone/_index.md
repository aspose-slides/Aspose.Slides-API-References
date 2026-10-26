---
title: AddClone()
second_title: Referencia de la API Aspose.Slides para C++
description: Crea una copia de la forma especificada y la agrega al final de la colección de formas.
type: docs
weight: 495
url: /es/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Crea una copia de la forma especificada y la agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | La forma a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |
| width | **float** | El ancho del marco de la forma clonada, en puntos. |
| height | **float** | La altura del marco de la forma clonada, en puntos. |

### Valor devuelto

El [IShape](../../ishape/) recién creado.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

Crea una copia de la forma especificada y la agrega al final de la colección de formas. La nueva forma conserva el ancho y la altura de *sourceShape*.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |

### Valor devuelto

El [IShape](../../ishape/) recién creado.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

Crea una copia de la forma especificada y la agrega al final de la colección de formas. La forma clonada conserva la posición y el tamaño del original.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a clonar. |

### Valor devuelto

El [IShape](../../ishape/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShape](../../ishape/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)