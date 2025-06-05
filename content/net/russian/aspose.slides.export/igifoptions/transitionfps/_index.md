---
title: TransitionFps
second_title: Aspose.Sildes для .NET API Справочник
description: Получает или устанавливает FPS перехода кадры/сек. Значение по умолчанию равно 25.
type: docs
weight: 50
url: /ru/aspose.slides.export/igifoptions/transitionfps/
---

## IGifOptions.TransitionFps свойство

Получает или устанавливает FPS перехода [кадры/сек]. Значение по умолчанию равно 25.

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

### Также см.

* интерфейс [IGifOptions](../../igifoptions)
* пространство имен [Aspose.Slides.Export](../../igifoptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->