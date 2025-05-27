---
title: AfterAnimationColor
second_title: Référence API Aspose.Slides pour .NET
description: Définit une couleur après animation pour l'effet. Lire/écrire IColorFormat aspose.slides/icolorformat.
type: docs
weight: 10
url: /fr/aspose.slides.animation/ieffect/afteranimationcolor/
---

## Propriété IEffect.AfterAnimationColor

Définit une couleur après animation pour l'effet. Lire/écrire [`IColorFormat`](../../../aspose.slides/icolorformat).

```csharp
public IColorFormat AfterAnimationColor { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtenez le premier effet de la première diapositive.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Changez le type d'effet après animation en "Couleur"
    firstSlideEffect.AfterAnimationType = AfterAnimationType.Color;
    
    // Définissez la couleur après animation de l'effet.
    firstSlideEffect.AfterAnimationColor.Color = Color.Green;
}
```

### Voir aussi

* interface [IColorFormat](../../../aspose.slides/icolorformat)
* interface [IEffect](../../ieffect)
* namespace [Aspose.Slides.Animation](../../ieffect)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->