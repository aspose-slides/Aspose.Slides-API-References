---
title: SummaryZoomCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: ObtientISummaryZoomSectionCollectionaspose.slides/isummaryzoomsectioncollection pour lobjet Summary Zoom Frame.
type: docs
weight: 20
url: /fr/aspose.slides/summaryzoomframe/summaryzoomcollection/
---
## SummaryZoomFrame.SummaryZoomCollection property

Obtient[`ISummaryZoomSectionCollection`](../../isummaryzoomsectioncollection) pour l'objet Summary Zoom Frame.

```csharp
public ISummaryZoomSectionCollection SummaryZoomCollection { get; }
```

### Exemples

L'exemple montre comment obtenir l'élément Summary Zoom Section par index :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
}
```

### Voir également

* interface [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* class [SummaryZoomFrame](../../summaryzoomframe)
* espace de noms [Aspose.Slides](../../summaryzoomframe)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
