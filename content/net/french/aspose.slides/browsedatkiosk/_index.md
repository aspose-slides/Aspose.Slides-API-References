---
title: BrowsedAtKiosk
second_title: Référence de l'API Aspose.Slides pour .NET
description: Consulté dans un kiosque en plein écran
type: docs
weight: 960
url: /fr/aspose.slides/browsedatkiosk/
---

## BrowsedAtKiosk class

Consulté dans un kiosque (plein écran)

```csharp
public class BrowsedAtKiosk : SlideShowType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BrowsedAtKiosk](browsedatkiosk)() | Initialise une nouvelle instance de la classe BrowsedAtKiosk. |

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    pres.SlideShowSettings.SlideShowType = new BrowsedAtKiosk();
    pres.Save("pres.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* class [SlideShowType](../slideshowtype)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->