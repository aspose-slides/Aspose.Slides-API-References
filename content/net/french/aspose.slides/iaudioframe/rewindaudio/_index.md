---
title: RewindAudio
second_title: Référence API Aspose.Sildes pour .NET
description: Détermine si un audio est automatiquement rembobiné au début après avoir été joué. Booléen en lecture/écriture.
type: docs
weight: 150
url: /fr/aspose.slides/iaudioframe/rewindaudio/
---

## Propriété IAudioFrame.RewindAudio

Détermine si un audio est automatiquement rembobiné au début après avoir été joué. Booléen en lecture/écriture.

```csharp
public bool RewindAudio { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];

    // Ajouter un cadre audio
    IAudioFrame audioFrame = slide.Shapes.AddAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");

    // Définir l'audio pour jouer à travers les diapositives
    audioFrame.PlayAcrossSlides = true;

    // Définir l'audio pour rembobiner automatiquement au début après avoir été joué
    audioFrame.RewindAudio = true;

    pres.Save("AudioFrame_out.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IAudioFrame](../../iaudioframe)
* namespace [Aspose.Slides](../../iaudioframe)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->