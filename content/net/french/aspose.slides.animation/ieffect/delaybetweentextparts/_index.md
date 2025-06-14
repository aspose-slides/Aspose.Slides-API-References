---
title: DelayBetweenTextParts
second_title: Référence de l'API Aspose.Slides pour .NET
description: Définit un délai entre les parties de texte animées mots ou lettres. Une valeur positive spécifie le pourcentage de la durée de l'effet. Une valeur négative spécifie le délai en secondes. Lecture/écriture Single.
type: docs
weight: 50
url: /fr/aspose.slides.animation/ieffect/delaybetweentextparts/
---

## IEffect.DelayBetweenTextParts propriété

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
    
    // Changez le type d'animation de texte de l'effet en "Par mot"
    firstSlideEffect.AnimateTextType = AnimateTextType.ByWord;
    
    // Définissez le délai entre les parties de texte animées à 20 % de la durée de l'effet.
    firstSlideEffect.DelayBetweenTextParts = 20f;
}
```

### Voir aussi

* interface [IEffect](../../ieffect)
* namespace [Aspose.Slides.Animation](../../ieffect)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->