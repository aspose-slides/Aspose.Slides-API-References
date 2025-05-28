---
title: InsertConnector
second_title: Aspose.Sildes para .NET Referencia de la API
description: Crea un nuevo conector, lo ajusta a partir de la plantilla predeterminada e lo inserta en la colección en el índice especificado.
type: docs
weight: 280
url: /es/aspose.slides/ishapecollection/insertconnector/
---

## InsertConnector(int, ShapeType, float, float, float, float) {#insertconnector}

Crea un nuevo conector, lo ajusta a partir de la plantilla predeterminada e lo inserta en la colección en el índice especificado.

```csharp
public IConnector InsertConnector(int index, ShapeType shapeType, float x, float y, float width, 
    float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el valor. |
| shapeType | ShapeType | Un [`ShapeType`](../../shapetype) de la forma. |
| x | Single | La coordenada X para el lado izquierdo del marco de la forma. |
| y | Single | La coordenada Y para el lado superior del marco de la forma. |
| width | Single | El ancho del marco de la forma. |
| height | Single | La altura del marco de la forma. |

### Valor de Retorno

Objeto Connector creado.

### Véase También

* interfaz [IConnector](../../iconnector)
* enum [ShapeType](../../shapetype)
* interfaz [IShapeCollection](../../ishapecollection)
* espacio de nombres [Aspose.Slides](../../ishapecollection)
* ensamblado [Aspose.Slides](../../../)

---

## InsertConnector(int, ShapeType, float, float, float, float, bool) {#insertconnector_1}

Crea un nuevo conector e lo inserta en la colección en el índice especificado.

```csharp
public IConnector InsertConnector(int index, ShapeType shapeType, float x, float y, float width, 
    float height, bool createFromTemplate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el valor. |
| shapeType | ShapeType | Un [`ShapeType`](../../shapetype) de la forma. |
| x | Single | La coordenada X para el lado izquierdo del marco de la forma. |
| y | Single | La coordenada Y para el lado superior del marco de la forma. |
| width | Single | El ancho del marco de la forma. |
| height | Single | La altura del marco de la forma. |
| createFromTemplate | Boolean | Si es verdadero, entonces la nueva forma se ajustará a partir de la plantilla predeterminada. No se asignará un nombre vacío, estilo sencillo y texto centrado a la nueva forma. Si es falso, entonces todos los valores de las propiedades de la nueva forma tendrán valores predeterminados. |

### Valor de Retorno

Objeto Connector creado.

### Véase También

* interfaz [IConnector](../../iconnector)
* enum [ShapeType](../../shapetype)
* interfaz [IShapeCollection](../../ishapecollection)
* espacio de nombres [Aspose.Slides](../../ishapecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->