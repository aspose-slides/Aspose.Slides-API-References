---
title: InsertConnector()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando el estilo predeterminado de la plantilla.
type: docs
weight: 430
url: /es/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) método

Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando el estilo predeterminado de la plantilla.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la forma de conector. |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma de conector a insertar. |
| x | **float** | La coordenada x del marco del connector\\u2019s, en puntos. |
| y | **float** | La coordenada y del marco del connector\\u2019s, en puntos. |
| width | **float** | El ancho del marco del connector\\u2019s, en puntos. |
| height | **float** | La altura del marco del connector\\u2019s, en puntos. |

### Valor devuelto

El [IConnector](../../iconnector/) recién creado.

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) método

Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando opcionalmente el estilo predeterminado de la plantilla.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la forma de conector. |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma de conector a insertar. |
| x | **float** | La coordenada x del marco del connector\\u2019s, en puntos. |
| y | **float** | La coordenada y del marco del connector\\u2019s, en puntos. |
| width | **float** | El ancho del marco del connector\\u2019s, en puntos. |
| height | **float** | La altura del marco del connector\\u2019s, en puntos. |
| createFromTemplate | **bool** | True para aplicar el estilo predeterminado de la plantilla (nombre no vacío, estilo simple); false para crear el conector con los valores predeterminados de sus propiedades. |

### Valor devuelto

El [IConnector](../../iconnector/) recién creado.

## Ver también

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IConnector](../../iconnector/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)