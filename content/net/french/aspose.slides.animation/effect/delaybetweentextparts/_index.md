---
title: DelayBetweenTextParts
second_title: Aspose.Slides pour la référence API .NET
description: Définit un délai entre les parties de texte animées mots ou lettres. Une valeur positive spécifie le pourcentage de la durée de l'effet. Une valeur négative spécifie le délai en secondes. Lecture/écriture Single.
type: docs
weight: 50
url: /fr/aspose.slides.animation/effect/delaybetweentextparts/
---

## Propriété Effect.DelayBetweenTextParts

Définit un délai entre les parties de texte animées (mots ou lettres). Une valeur positive spécifie le pourcentage de la durée de l'effet. Une valeur négative spécifie le délai en secondes. Lecture/écriture Single.

```csharp
public float DelayBetweenTextParts { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtenez le premier effet de la première diapositive.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Changez le type d'effet animer le texte en "Par mot"
    firstSlideEffect.AnimateTextType = AnimateTextType.ByWord;
    
    // Définissez le délai entre les parties de texte animées à 20% de la durée de l'effet.
    firstSlideEffect.DelayBetweenTextParts = 20f;
}
```

### Voir aussi

* classe [Effect](../../effect)
* namespace [Aspose.Slides.Animation](../../effect)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->