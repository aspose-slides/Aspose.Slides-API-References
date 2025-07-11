---
title: ISmartArtNode
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un nodo de un diagrama SmartArt.
type: docs
weight: 10240
url: /es/aspose.slides.smartart/ismartartnode/
---

## Interfaz ISmartArtNode

Representa un nodo de un diagrama SmartArt.

```csharp
public interface ISmartArtNode
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BulletFillFormat](../../aspose.slides.smartart/ismartartnode/bulletfillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para un viñeta de nodo. Nota: puede devolver null para ciertos tipos de diseño de SmartArt que no proporcionan viñetas para nodos. Solo lectura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [ChildNodes](../../aspose.slides.smartart/ismartartnode/childnodes) { get; } | Devuelve colecciones de todos los nodos hijos del nodo actual. Solo lectura [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [IsAssistant](../../aspose.slides.smartart/ismartartnode/isassistant) { get; set; } | Devuelve o establece el nodo como asistente. Lectura/escritura Booleano. |
| [IsHidden](../../aspose.slides.smartart/ismartartnode/ishidden) { get; } | Devuelve true si este nodo es un nodo oculto en el modelo de datos. Solo lectura Booleano. |
| [Level](../../aspose.slides.smartart/ismartartnode/level) { get; } | Devuelve el nivel de anidación del nodo. Solo lectura Int32. |
| [OrganizationChartLayout](../../aspose.slides.smartart/ismartartnode/organizationchartlayout) { get; set; } | Devuelve o establece el tipo de diseño de organigrama asociado con el nodo actual. Lectura/escritura [`OrganizationChartLayoutType`](../organizationchartlayouttype). |
| [Position](../../aspose.slides.smartart/ismartartnode/position) { get; set; } | Devuelve o establece la posición basada en cero del nodo entre nodos hermanos. Lectura/escritura Int32. |
| [Shapes](../../aspose.slides.smartart/ismartartnode/shapes) { get; } | Devuelve colecciones de todas las formas asociadas con el nodo. Solo lectura [`ISmartArtShapeCollection`](../ismartartshapecollection). |
| [TextFrame](../../aspose.slides.smartart/ismartartnode/textframe) { get; } | Devuelve o establece el texto del nodo. Solo lectura [`ITextFrame`](../../aspose.slides/itextframe). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Remove](../../aspose.slides.smartart/ismartartnode/remove)() | Elimina el nodo actual. |

### Véase también

* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->