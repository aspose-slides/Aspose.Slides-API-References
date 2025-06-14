---
title: ReturnToParent
second_title: Aspose.Sildes pour la référence API .NET
description: Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture Booléen. Valeur par défaut false
type: docs
weight: 20
url: /fr/aspose.slides/zoomobject/returntoparent/
---

## ZoomObject.ReturnToParent propriété

Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture Booléen. Valeur par défaut : false

```csharp
public bool ReturnToParent { get; set; }
```

### Remarques

La valeur vraie de la propriété spécifie un comportement de retour à la navigation vers le parent dans le diaporama.

### Exemples

Exemple :

```csharp
[C#]
IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
zoomFrame.ReturnToParent = true;
```

### Voir Aussi

* classe [ZoomObject](../../zoomobject)
* espace de noms [Aspose.Slides](../../zoomobject)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->