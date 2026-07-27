---
title: AddConnector()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma de conector con el estilo de plantilla predeterminado y la agrega al final de la colección de formas.
type: docs
weight: 378
url: /es/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) método

Crea una nueva forma de conector con el estilo de plantilla predeterminado y la agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma de conector a agregar. |
| x | **float** | La coordenada x del marco del conector, en puntos. |
| y | **float** | La coordenada y del marco del conector, en puntos. |
| width | **float** | El ancho del marco del conector, en puntos. |
| height | **float** | La altura del marco del conector, en puntos. |

### Valor devuelto

El [IConnector](../../iconnector/) recién creado.

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) método

Crea una nueva forma de conector y la agrega al final de la colección de formas, aplicando opcionalmente el estilo de plantilla predeterminado.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma de conector a crear. |
| x | **float** | La coordenada x del marco del conector, en puntos. |
| y | **float** | La coordenada y del marco del conector, en puntos. |
| width | **float** | El ancho del marco del conector, en puntos. |
| height | **float** | La altura del marco del conector, en puntos. |
| createFromTemplate | **bool** | True para aplicar el estilo de plantilla predeterminado (nombre no vacío, estilo simple); false para crear el conector con valores de propiedad predeterminados. |

### Valor devuelto

El [IConnector](../../iconnector/) recién creado.

## Ver también

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IConnector](../../iconnector/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)