---
title: VolumeValue
second_title: Aspose.Sildes for .NET API Reference
description: 返回或设置音频音量（以百分比表示）。可读/写单精度浮点数。
type: docs
weight: 180
url: /zh/aspose.slides/audioframe/volumevalue/
---

## AudioFrame.VolumeValue 属性

返回或设置音频音量（以百分比表示）。可读/写单精度浮点数。

```csharp
public float VolumeValue { get; set; }
```

### 示例

示例：

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // 将音频音量设置为85%
    audioFrame.VolumeValue = 85f;

    pres.Save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
}
```

### 参见

* class [AudioFrame](../../audioframe)
* namespace [Aspose.Slides](../../audioframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->