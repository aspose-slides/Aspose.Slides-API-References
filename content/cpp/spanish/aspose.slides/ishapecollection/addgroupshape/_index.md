---
title: AddGroupShape()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas. El marco del grupo se ajustará automáticamente para adaptarse a cualquier forma añadida.
type: docs
weight: 352
url: /es/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() método

Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas. El marco del grupo se ajustará automáticamente para adaptarse a cualquier forma añadida.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### Valor devuelto

El nuevo [IGroupShape](../../igroupshape/) creado.

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) método

Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales y agrega el grupo resultante al final de la colección de formas.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | El [ISvgImage](../../isvgimage/) que contiene contenido vectorial para convertir en formas. |
| x | **float** | La coordenada x del marco del grupo, en puntos. |
| y | **float** | La coordenada y del marco del grupo, en puntos. |
| width | **float** | El ancho del marco del grupo, en puntos. |
| height | **float** | La altura del marco del grupo, en puntos. |

### Valor devuelto

El nuevo [IGroupShape](../../igroupshape/) creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IGroupShape](../../igroupshape/)
* Clase [IShapeCollection](../)
* Clase [ISvgImage](../../isvgimage/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)