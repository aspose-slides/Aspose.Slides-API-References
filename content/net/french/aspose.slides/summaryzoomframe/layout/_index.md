---
title: Layout
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient la mise en page des sections de résumé de zoom dans le cadre. La valeur par défaut est GridLayout.
type: docs
weight: 10
url: /fr/aspose.slides/summaryzoomframe/layout/
---

## Propriété SummaryZoomFrame.Layout

Obtient la mise en page des sections de résumé de zoom dans le cadre. La valeur par défaut est GridLayout.

```csharp
public ZoomLayout Layout { get; }
```

### Exemples

L'exemple démontre comment obtenir un élément de section de résumé de zoom par index :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ZoomLayout layout = zoomFrame.Layout;
}
```

### Voir aussi

* enum [ZoomLayout](../../zoomlayout)
* class [SummaryZoomFrame](../../summaryzoomframe)
* namespace [Aspose.Slides](../../summaryzoomframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->