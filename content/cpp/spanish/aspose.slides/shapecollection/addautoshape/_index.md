---
title: AddAutoShape()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma automática con formato predeterminado y la agrega al final de la colección de formas.
type: docs
weight: 352
url: /es/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) método


Crea una nueva forma automática con formato predeterminado y la agrega al final de la colección de formas.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma automática a agregar. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |

### Valor devuelto

El [IAutoShape](../../iautoshape/) recién creado.

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) método


Crea una nueva forma automática y la agrega al final de la colección de formas, opcionalmente inicializándola con el formato de plantilla predeterminado.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma automática a agregar. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |
| createFromTemplate | **bool** | True para aplicar el estilo de plantilla predeterminado (estilo simple, texto centrado y nombre no vacío) a la nueva forma; false para crear la forma con todas las propiedades establecidas en sus valores predeterminados. |

### Valor devuelto

El [IAutoShape](../../iautoshape/) recién creado.

## Ver también

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)