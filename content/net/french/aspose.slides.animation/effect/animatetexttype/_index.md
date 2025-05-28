---
title: AnimateTextType
second_title: Référence de l'API Aspose.Slides pour .NET
description: Définit un type de texte animé pour un effet. Le texte de la forme peut être animé lettre par lettre, mot par mot ou en une seule fois. Lire/écrire AnimateTextType aspose.slides.animation/effect/animatetexttype.
type: docs
weight: 30
url: /fr/aspose.slides.animation/effect/animatetexttype/
---

## Propriété Effect.AnimateTextType

Définit un type de texte animé pour un effet. Le texte de la forme peut être animé lettre par lettre, mot par mot ou en une seule fois. Lire/écrire `AnimateTextType`.

```csharp
public AnimateTextType AnimateTextType { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtenez le premier effet de la première diapositive.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Changez le type de texte animé de l'effet en "Par lettre"
    firstSlideEffect.AnimateTextType = AnimateTextType.ByLetter;
}
```

### Voir Aussi

* enum [AnimateTextType](../../animatetexttype)
* class [Effect](../../effect)
* namespace [Aspose.Slides.Animation](../../effect)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITEZ : généré par xmldocmd pour Aspose.Slides.dll -->