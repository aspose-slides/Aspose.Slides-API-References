---
title: VolumeValue
second_title: Aspose.Sildes for .NET API Reference
description: 返回或设置音频音量的百分比。可读写单精度浮点数。
type: docs
weight: 190
url: /zh/aspose.slides/iaudioframe/volumevalue/
---

## IAudioFrame.VolumeValue 属性

返回或设置音频音量的百分比。可读写单精度浮点数。

```csharp
public float VolumeValue { get; set; }
```

### 示例

示例:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // 设置音频音量为85%
    audioFrame.VolumeValue = 85f;

    pres.Save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
}
```

### 另请参阅

* 接口 [IAudioFrame](../../iaudioframe)
* 命名空间 [Aspose.Slides](../../iaudioframe)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->