---
title: SetEmbeddedData
second_title: Aspose.Sildes pour la référence API .NET
description: Définit les informations sur les données incorporées OLE.
type: docs
weight: 150
url: /fr/aspose.slides/ioleobjectframe/setembeddeddata/
---

## IOleObjectFrame.SetEmbeddedData method

Définit les informations sur les données incorporées OLE.

```csharp
public void SetEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| embeddedData | IOleEmbeddedDataInfo | Données incorporées [`IOleEmbeddedDataInfo`](../../ioleembeddeddatainfo) |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre embeddedData est nul. |

### Remarques

Cette méthode change les propriétés de l'objet pour refléter les nouvelles données et définit le drapeau IsObjectLink sur false, indiquant que l'objet OLE est incorporé.

### Exemples

L'exemple suivant démontre comment changer les données OLE incorporées et son type pour un objet [`IOleObjectFrame`](../../ioleobjectframe) existant.

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentation.pptx"))
{
    OleObjectFrame oof = pres.Slides[0].Shapes[0] as OleObjectFrame;
    if (oof != null)
    {
        IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(File.ReadAllBytes("Picture.png"), "png");
        oof.SetEmbeddedData(newData);
    }
}
```

### See Also

* interface [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo)
* interface [IOleObjectFrame](../../ioleobjectframe)
* namespace [Aspose.Slides](../../ioleobjectframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->