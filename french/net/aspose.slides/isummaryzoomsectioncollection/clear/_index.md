---
title: Clear
second_title: Référence de l'API Aspose.Slides pour .NET
description: Supprime tous les objets SummaryZoomSection de la collection.
type: docs
weight: 30
url: /fr/net/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection.Clear method

Supprime tous les objets SummaryZoomSection de la collection.

```csharp
public void Clear()
```

### Exemples

L'exemple montre comment obtenir l'élément Summary Zoom Section par index :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    collection.Clear();
}
```

### Voir également

* interface [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* espace de noms [Aspose.Slides](../../isummaryzoomsectioncollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->