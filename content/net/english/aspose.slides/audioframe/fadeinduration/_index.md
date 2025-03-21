---
title: FadeInDuration
second_title: Aspose.Sildes for .NET API Reference
description: Specifies the time duration for the initial fade-in of the media in milliseconds. Read/write Single.
type: docs
weight: 70
url: /aspose.slides/audioframe/fadeinduration/
---

## AudioFrame.FadeInDuration property

Specifies the time duration for the initial fade-in of the media in milliseconds. Read/write Single.

```csharp
public float FadeInDuration { get; set; }
```

### Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Set the duration of the starting fade for 200ms
    audioFrame.FadeInDuration = 200f;

    pres.Save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
}
```

### See Also

* class [AudioFrame](../../audioframe)
* namespace [Aspose.Slides](../../audioframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
