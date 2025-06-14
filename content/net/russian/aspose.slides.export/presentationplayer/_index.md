---
title: PresentationPlayer
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет игрока анимаций, связанных с Presentationaspose.slides/aspose.slides/presentation.
type: docs
weight: 4200
url: /ru/aspose.slides.export/presentationplayer/
---

## Класс PresentationPlayer

Представляет игрока анимаций, связанных с [`Presentation`](../../aspose.slides/presentation).

```csharp
public class PresentationPlayer : IDisposable
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [PresentationPlayer](presentationplayer)(PresentationAnimationsGenerator, double) | Создает новый экземпляр [`PresentationPlayer`](../presentationplayer). |

## Свойства

| Название | Описание |
| --- | --- |
| [FrameIndex](../../aspose.slides.export/presentationplayer/frameindex) { get; } | Получает индекс кадра. |

## Методы

| Название | Описание |
| --- | --- |
| [Dispose](../../aspose.slides.export/presentationplayer/dispose)() | Освобождает экземпляр [`PresentationPlayer`](../presentationplayer). |

## Прочие члены

| Название | Описание |
| --- | --- |
| delegate [FrameTickHandler](presentationplayer.frametickhandler) |  |

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(pres))
    {
        // Воспроизведение анимации с 33 FPS
        using (var player = new PresentationPlayer(animationsGenerator, 33))
        {
            player.FrameTick += (sender, args) =>
            {
                args.GetFrame().Save(Path.Combine("33fps", $"frame_{sender.FrameIndex}.png"));
            };

            animationsGenerator.Run(pres.Slides);
        }
        
        // Воспроизведение анимации с 45 FPS
        using (var player = new PresentationPlayer(animationsGenerator, 45))
        {
            player.FrameTick += (sender, args) =>
            {
                args.GetFrame().Save(Path.Combine("45fps", $"frame_{sender.FrameIndex}.png"));
            };

            animationsGenerator.Run(pres.Slides);
        }
    }
}
```

### Смотрите также

* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->