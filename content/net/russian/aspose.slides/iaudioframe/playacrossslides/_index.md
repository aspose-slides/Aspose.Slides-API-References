---
title: PlayAcrossSlides
second_title: Aspose.Sildes для справочника API .NET
description: Определяет, воспроизводится ли аудио на слайдах. Читаемое/записываемое логическое значение.
type: docs
weight: 120
url: /ru/aspose.slides/iaudioframe/playacrossslides/
---

## Свойство IAudioFrame.PlayAcrossSlides

Определяет, воспроизводится ли аудио на слайдах. Читаемое/записываемое логическое значение.

```csharp
public bool PlayAcrossSlides { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];

    // Добавить аудио рамку
    IAudioFrame audioFrame = slide.Shapes.AddAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");

    // Установить воспроизведение аудио на слайдах
    audioFrame.PlayAcrossSlides = true;

    // Установить автоматическое перематывание аудио к началу после воспроизведения
    audioFrame.RewindAudio = true;

    pres.Save("AudioFrame_out.pptx", SaveFormat.Pptx);
}
```

### Также см. 

* интерфейс [IAudioFrame](../../iaudioframe)
* пространство имен [Aspose.Slides](../../iaudioframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->