---
title: FadeInDuration
second_title: Aspose.Slides pour l'API .NET Référence
description: Spécifie la durée en millisecondes pour le fondu initial du média. Lecture/écriture Single.
type: docs
weight: 70
url: /fr/aspose.slides/audioframe/fadeinduration/
---

## Propriété AudioFrame.FadeInDuration

Spécifie la durée en millisecondes pour le fondu initial du média. Lecture/écriture Single.

```csharp
public float FadeInDuration { get; set; }
```

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Définir la durée du fondu de départ à 200ms
    audioFrame.FadeInDuration = 200f;

    pres.Save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
}
```

### Voir Aussi

* classe [AudioFrame](../../audioframe)
* espace de noms [Aspose.Slides](../../audioframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->