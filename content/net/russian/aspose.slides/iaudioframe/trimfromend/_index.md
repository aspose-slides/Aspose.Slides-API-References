---
title: TrimFromEnd
second_title: Aspose.Sildes для справки по API .NET
description: Указывает продолжительность времени, которое должно быть удалено с конца медиафайла во время воспроизведения в миллисекундах. Чтение/запись Float.
type: docs
weight: 160
url: /ru/aspose.slides/iaudioframe/trimfromend/
---

## Свойство IAudioFrame.TrimFromEnd

Указывает продолжительность времени, которое должно быть удалено с конца медиафайла во время воспроизведения, в миллисекундах. Чтение/запись Float.

```csharp
public float TrimFromEnd { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Установите время отсечки в конце 2 секунды
    audioFrame.TrimFromEnd = 2000f;
}
```

### Смотрите также

* интерфейс [IAudioFrame](../../iaudioframe)
* пространство имен [Aspose.Slides](../../iaudioframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->