---
title: Title
second_title: Référence API Aspose.Sildes pour .NET
description: Renvoie le titre texte de l'objet Section de Zoom Résumé.
type: docs
weight: 20
url: /fr/aspose.slides/summaryzoomsection/title/
---

## Propriété SummaryZoomSection.Title

Renvoie le titre texte de l'objet Section de Zoom Résumé.

```csharp
public string Title { get; set; }
```

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomSection zoomSection = zoomFrame.SummaryZoomCollection[1];
    zoomSection.Title = "Title";
}
```

### Voir aussi

* classe [SummaryZoomSection](../../summaryzoomsection)
* espace de noms [Aspose.Slides](../../summaryzoomsection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->