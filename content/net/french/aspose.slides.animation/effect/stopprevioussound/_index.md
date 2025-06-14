---
title: StopPreviousSound
second_title: Aspose.Slides pour .NET Référence API
description: Cet attribut spécifie si l'effet d'animation arrête le son précédent. Booléen en lecture/écriture.
type: docs
weight: 90
url: /fr/aspose.slides.animation/effect/stopprevioussound/
---

## Propriété Effect.StopPreviousSound

Cet attribut spécifie si l'effet d'animation arrête le son précédent. Booléen en lecture/écriture.

```csharp
public bool StopPreviousSound { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtenir le premier effet de la première diapositive.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Obtenir le premier effet de la deuxième diapositive.
    IEffect secondSlideEffect = presentation.Slides[1].Timeline.MainSequence[0];
       
    if (firstSlideEffect.Sound != null)
    {
        // Changer le deuxième effet Améliorations/Son en "Arrêter le son précédent"
        secondSlideEffect.StopPreviousSound = true;
    }
}
```

### Voir aussi

* classe [Effect](../../effect)
* espace de noms [Aspose.Slides.Animation](../../effect)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->