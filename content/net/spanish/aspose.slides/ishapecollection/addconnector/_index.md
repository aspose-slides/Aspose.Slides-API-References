---
title: AddConnector
second_title: Aspose.Sildes para .NET Referencia de API
description: Crea un nuevo conector, lo ajusta a partir de una plantilla predeterminada y lo añade al final de la colección.
type: docs
weight: 90
url: /es/aspose.slides/ishapecollection/addconnector/
---

## AddConnector(ShapeType, float, float, float, float) {#addconnector}

Crea un nuevo conector, lo ajusta a partir de una plantilla predeterminada y lo añade al final de la colección.

```csharp
public IConnector AddConnector(ShapeType shapeType, float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | ShapeType | El [`ShapeType`](../../shapetype) de la forma. |
| x | Single | La coordenada X para el lado izquierdo del marco de la forma. |
| y | Single | La coordenada Y para la parte superior del marco de la forma. |
| width | Single | El ancho del marco de la forma. |
| height | Single | La altura del marco de la forma. |

### Valor de Retorno

El índice basado en cero de la forma creada.

Objeto Connector creado.

### Véase También

* interfaz [IConnector](../../iconnector)
* enum [ShapeType](../../shapetype)
* interfaz [IShapeCollection](../../ishapecollection)
* espacio de nombres [Aspose.Slides](../../ishapecollection)
* ensamblado [Aspose.Slides](../../../)

---

## AddConnector(ShapeType, float, float, float, float, bool) {#addconnector_1}

Crea un nuevo conector y lo añade al final de la colección.

```csharp
public IConnector AddConnector(ShapeType shapeType, float x, float y, float width, float height, 
    bool createFromTemplate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | ShapeType | El [`ShapeType`](../../shapetype) de la forma. |
| x | Single | La coordenada X para el lado izquierdo del marco de la forma. |
| y | Single | La coordenada Y para la parte superior del marco de la forma. |
| width | Single | El ancho del marco de la forma. |
| height | Single | La altura del marco de la forma. |
| createFromTemplate | Boolean | Si es verdadero, entonces la nueva forma se ajustará a partir de la plantilla predeterminada. Un nombre no vacío, estilo simple y texto centrado se asignarán a la nueva forma. Si es falso, entonces todos los valores de las propiedades de la nueva forma tendrán valores predeterminados. |

### Valor de Retorno

El índice basado en cero de la forma creada.

Objeto Connector creado.

### Véase También

* interfaz [IConnector](../../iconnector)
* enum [ShapeType](../../shapetype)
* interfaz [IShapeCollection](../../ishapecollection)
* espacio de nombres [Aspose.Slides](../../ishapecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->