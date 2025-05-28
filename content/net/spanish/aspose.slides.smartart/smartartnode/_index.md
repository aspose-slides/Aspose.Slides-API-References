---
title: SmartArtNode
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un nodo de un objeto SmartArt
type: docs
weight: 10320
url: /es/aspose.slides.smartart/smartartnode/
---

## Clase SmartArtNode

Representa un nodo de un objeto SmartArt

```csharp
public sealed class SmartArtNode : ISmartArtNode
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BulletFillFormat](../../aspose.slides.smartart/smartartnode/bulletfillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para un viñeta de nodo. Nota: puede devolver null para ciertos tipos de diseño de SmartArt que no proporcionan viñetas para los nodos. Solo lectura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [ChildNodes](../../aspose.slides.smartart/smartartnode/childnodes) { get; } | Devuelve colecciones de todos los nodos hijos del nodo actual. Solo lectura [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [IsAssistant](../../aspose.slides.smartart/smartartnode/isassistant) { get; set; } | Devuelve o establece el nodo como asistente. Lectura/escritura booleano. |
| [IsHidden](../../aspose.slides.smartart/smartartnode/ishidden) { get; } | Devuelve true si este nodo es un nodo oculto en el modelo de datos. Solo lectura booleano. |
| [Level](../../aspose.slides.smartart/smartartnode/level) { get; } | Devuelve el nivel de anidación del nodo. Solo lectura Int32. |
| [OrganizationChartLayout](../../aspose.slides.smartart/smartartnode/organizationchartlayout) { get; set; } | Devuelve o establece el tipo de diseño del organigrama asociado con el nodo actual. Lectura/escritura [`OrganizationChartLayoutType`](../organizationchartlayouttype). |
| [Position](../../aspose.slides.smartart/smartartnode/position) { get; set; } | Devuelve o establece la posición basada en cero del nodo entre nodos hermanos. Lectura/escritura Int32. |
| [Shapes](../../aspose.slides.smartart/smartartnode/shapes) { get; } | Devuelve colecciones de todas las formas asociadas con el nodo. Solo lectura [`ISmartArtShapeCollection`](../ismartartshapecollection). |
| [TextFrame](../../aspose.slides.smartart/smartartnode/textframe) { get; } | Devuelve el marco de texto del nodo. Solo lectura [`ITextFrame`](../../aspose.slides/itextframe). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Remove](../../aspose.slides.smartart/smartartnode/remove)() | Elimina el nodo actual. |

### Véase También

* interface [ISmartArtNode](../ismartartnode)
* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->