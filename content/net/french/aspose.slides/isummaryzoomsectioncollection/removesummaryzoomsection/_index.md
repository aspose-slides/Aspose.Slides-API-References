---
title: RemoveSummaryZoomSection
second_title: Aspose.Slides pour la référence de l'API .NET
description: Supprimer l'objet Section de Zoom Résumé de la collection.
type: docs
weight: 60
url: /fr/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---

## ISummaryZoomSectionCollection.RemoveSummaryZoomSection méthode

Supprimer l'objet Section de Zoom Résumé de la collection.

```csharp
public void RemoveSummaryZoomSection(ISection section)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| section | ISection | Section pour laquelle l'élément Section de Zoom Résumé doit être supprimé [`ISection`](../../isection). |

### Exemples

L'exemple démontre comment obtenir l'élément Section de Zoom Résumé par index:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    collection.RemoveSummaryZoomSection(pres.Sections[1]);
}
```

### Voir aussi

* interface [ISection](../../isection)
* interface [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* namespace [Aspose.Slides](../../isummaryzoomsectioncollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->