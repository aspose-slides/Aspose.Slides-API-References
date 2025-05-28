---
title: PlayAcrossSlides
second_title: Aspose.Slides для .NET API Справочник
description: Определяет, воспроизводится ли аудио на слайдах. Читаемое/записываемое логическое значение.
type: docs
weight: 120
url: /ru/aspose.slides/iaudioframe/playacrossslides/
---

## IAudioFrame.PlayAcrossSlides свойство

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

    // Установить аудио для воспроизведения на слайдах
    audioFrame.PlayAcrossSlides = true;

    // Установить аудио для автоматического перемотки в начало после воспроизведения
    audioFrame.RewindAudio = true;

    pres.Save("AudioFrame_out.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IAudioFrame](../../iaudioframe)
* пространство имен [Aspose.Slides](../../iaudioframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->