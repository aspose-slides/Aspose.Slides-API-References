---
title: VolumeValue
second_title: Aspose.Sildes för .NET API-referens
description: Returnerar eller anger den exakta videovolymen som en procentsats. Värdet uttrycks som en procentsats från 0 till 100. Använd den här egenskapen för att läsa eller ange volymvärden som är mer precisa än de fördefinierade nivåerna som finns via Volumeaspose.slides/ivideoframe/volume egenskap. Läs/skriv Single.
type: docs
weight: 130
url: /sv/aspose.slides/ivideoframe/volumevalue/
---
## IVideoFrame.VolumeValue egenskap

Returnerar eller anger den exakta videovolymen som en procentsats. Värdet uttrycks som en procentsats från 0 till 100. Använd den här egenskapen för att läsa eller ange volymvärden som är mer exakta än de fördefinierade nivåerna som finns via [`Volume`](../volume)-egenskapen. Läs/skriv Single.

```csharp
public float VolumeValue { get; set; }
```

### Exempel

Exempel:

```csharp
[C#]
using (Presentation pres = new Presentation("video.pptx"))
{
    IVideoFrame videoFrame = (IVideoFrame)pres.Slides[0].Shapes[0];

    // Läs den aktuella exakta volymen och sätt den till 75.5 procent.
    float currentVolume = videoFrame.VolumeValue;
    videoFrame.VolumeValue = 75.5f;

    pres.Save("video_with_volume.pptx", SaveFormat.Pptx);
}
```

### Se också

* gränssnitt [IVideoFrame](../../ivideoframe)
* namnrymd [Aspose.Slides](../../ivideoframe)
* samling [Aspose.Slides](../../../)