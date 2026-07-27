---
title: AddClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de la forma especificada y la agrega al final de la colección de formas.
type: docs
weight: 547
url: /es/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) método

Crea una copia de la forma especificada y la agrega al final de la colección de formas.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | La forma a clonar. |
| x | **float** | La coordenada x del marco de la nueva forma, en puntos. |
| y | **float** | La coordenada y del marco de la nueva forma, en puntos. |
| width | **float** | El ancho del marco de la nueva forma, en puntos. |
| height | **float** | La altura del marco de la nueva forma, en puntos. |

### Valor devuelto

El [IShape](../../ishape/) recién creado.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) método

Crea una copia de la forma especificada y la agrega al final de la colección de formas. La nueva forma conserva el ancho y la altura de la *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | La forma a clonar. |
| x | **float** | La coordenada x del marco de la nueva forma, en puntos. |
| y | **float** | La coordenada y del marco de la nueva forma, en puntos. |

### Valor devuelto

El [IShape](../../ishape/) recién creado.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) método

Crea una copia de la forma especificada y la agrega al final de la colección de formas. La forma clonada conserva la posición y el tamaño del original.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
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
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)