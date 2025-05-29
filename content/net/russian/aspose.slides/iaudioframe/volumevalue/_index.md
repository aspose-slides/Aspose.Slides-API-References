---
title: VolumeValue
second_title: Aspose.Slides для .NET API Reference
description: Возвращает или устанавливает громкость аудио в процентах. Чтение/запись Single.
type: docs
weight: 190
url: /ru/aspose.slides/iaudioframe/volumevalue/
---

## Свойство IAudioFrame.VolumeValue

Возвращает или устанавливает громкость аудио в процентах. Чтение/запись Single.

```csharp
public float VolumeValue { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Установите громкость аудио на 85%
    audioFrame.VolumeValue = 85f;

    pres.Save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IAudioFrame](../../iaudioframe)
* пространство имен [Aspose.Slides](../../iaudioframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->