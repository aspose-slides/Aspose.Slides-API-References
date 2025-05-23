---
title: Sound
second_title: Référence de l'API Aspose.Slides pour .NET
description: Son intégré défini pour leffet. Lecture/écritureIAudioaspose.slides/iaudio .
type: docs
weight: 40
url: /fr/aspose.slides.animation/ieffect/sound/
---
## IEffect.Sound property

Son intégré défini pour l'effet. Lecture/écriture[`IAudio`](../../../aspose.slides/iaudio) .

```csharp
public IAudio Sound { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation presentation = new Presentation(path + "demo.pptx"))
{
    ISlide slide = presentation.Slides[0];
    
    // Obtient la séquence d'effets pour la diapositive
    ISequence effectsSequence = slide.Timeline.MainSequence;
       
    foreach (IEffect effect in effectsSequence)
    {
        if (effect.Sound == null)
            continue;
        
        // Extrait le son de l'effet dans un tableau d'octets
        byte[] audio = effect.Sound.BinaryData;
    }
}
```

### Voir également

* interface [IAudio](../../../aspose.slides/iaudio)
* interface [IEffect](../../ieffect)
* espace de noms [Aspose.Slides.Animation](../../ieffect)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
