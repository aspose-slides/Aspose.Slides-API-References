---
title: TrimFromStart
second_title: Aspose.Slides für .NET API Referenz
description: Gibt die Zeitdauer an, die während der Wiedergabe in Millisekunden von Anfang des Mediums entfernt werden soll. Lese-/Schreibzugriff auf Single.
type: docs
weight: 160
url: /de/aspose.slides/audioframe/trimfromstart/
---

## AudioFrame.TrimFromStart-Eigenschaft

Gibt die Zeitdauer an, die von Anfang des Mediums während der Wiedergabe in Millisekunden entfernt werden soll. Lese-/Schreibzugriff auf Single.

```csharp
public float TrimFromStart { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Setze die Anfangs-Trimmzeit auf 1,5 Sekunden
    audioFrame.TrimFromStart = 1500f;
}
```

### Siehe Auch

* Klasse [AudioFrame](../../audioframe)
* Namensraum [Aspose.Slides](../../audioframe)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->