---
title: TransitionFps
second_title: Aspose.Sildes для .NET API Справочник
description: Получает или устанавливает количество FPS для переходов кадров/сек. Значение по умолчанию равно 25.
type: docs
weight: 50
url: /ru/aspose.slides.export/gifoptions/transitionfps/
---

## GifOptions.TransitionFps свойство

Получает или устанавливает количество FPS для переходов [кадров/сек]. Значение по умолчанию равно 25.

```csharp
public int TransitionFps { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { TransitionFps = 60 });
}
```

### См. также

* класс [GifOptions](../../gifoptions)
* пространство имен [Aspose.Slides.Export](../../gifoptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->