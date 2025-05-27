---
title: FadeInDuration
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie la durée pour l'apparition initiale du média en millisecondes. Lecture/écriture Single.
type: docs
weight: 70
url: /fr/aspose.slides/audioframe/fadeinduration/
---

## Propriété AudioFrame.FadeInDuration

Spécifie la durée pour l'apparition initiale du média en millisecondes. Lecture/écriture Single.

```csharp
public float FadeInDuration { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Définir la durée de l'apparition initiale pour 200 ms
    audioFrame.FadeInDuration = 200f;

    pres.Save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
}
```

### Voir Aussi

* classe [AudioFrame](../../audioframe)
* espace de noms [Aspose.Slides](../../audioframe)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->