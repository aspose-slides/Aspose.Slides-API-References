---
title: ShowBackground
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient ou définit une valeur qui spécifie si le Zoom utilisera l'arrière-plan de la diapositive de destination. Booléen en lecture/écriture. Valeur par défaut true
type: docs
weight: 30
url: /fr/aspose.slides/zoomobject/showbackground/
---

## Propriété ZoomObject.ShowBackground

Obtient ou définit une valeur qui spécifie si le Zoom utilisera l'arrière-plan de la diapositive de destination. Booléen en lecture/écriture. Valeur par défaut : true

```csharp
public bool ShowBackground { get; set; }
```

### Exemples

L'exemple démontre la suppression de l'arrière-plan d'une image d'un objet Zoom :

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.ShowBackground = false;
}
```

### Voir aussi

* classe [ZoomObject](../../zoomobject)
* espace de noms [Aspose.Slides](../../zoomobject)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->