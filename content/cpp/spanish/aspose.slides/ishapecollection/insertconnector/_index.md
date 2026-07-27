---
title: InsertConnector()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando el estilo de plantilla predeterminado.
type: docs
weight: 391
url: /es/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method

Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando el estilo de plantilla predeterminado.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la forma de conector. |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma de conector a insertar. |
| x | **float** | La coordenada x del marco del conector\u2019s, en puntos. |
| y | **float** | La coordenada y del marco del conector\u2019s, en puntos. |
| width | **float** | El ancho del marco del conector\u2019s, en puntos. |
| height | **float** | La altura del marco del conector\u2019s, en puntos. |

### Valor devuelto

El [IConnector](../../iconnector/) recién creado.

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method

Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando opcionalmente el estilo de plantilla predeterminado.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la forma de conector. |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma de conector a insertar. |
| x | **float** | La coordenada x del marco del conector\u2019s, en puntos. |
| y | **float** | La coordenada y del marco del conector\u2019s, en puntos. |
| width | **float** | El ancho del marco del conector\u2019s, en puntos. |
| height | **float** | La altura del marco del conector\u2019s, en puntos. |
| createFromTemplate | **bool** | True para aplicar el estilo de plantilla predeterminado (nombre no vacío, estilo simple); false para crear el conector con los valores predeterminados de sus propiedades. |

### Valor devuelto

El [IConnector](../../iconnector/) recién creado.

## Ver también

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)