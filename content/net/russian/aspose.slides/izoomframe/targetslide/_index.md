---
title: TargetSlide
second_title: Справочник по API Aspose.Slides для .NET
description: Получает или задает объект слайда на который ссылается объект Масштаб слайда. Чтение/записьISlideaspose.slides/islide.
type: docs
weight: 20
url: /ru/aspose.slides/izoomframe/targetslide/
---
## IZoomFrame.TargetSlide property

Получает или задает объект слайда, на который ссылается объект «Масштаб слайда». Чтение/запись[`ISlide`](../../islide).

```csharp
public ISlide TargetSlide { get; set; }
```

### Примеры

В следующем примере демонстрируется изменение целевого слайда и создание нового изображения для объекта Slide Zoom:

```csharp
[C#]
IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
zoomFrame.TargetSlide = pres.Slides[2];
```

### Смотрите также

* interface [ISlide](../../islide)
* interface [IZoomFrame](../../izoomframe)
* пространство имен [Aspose.Slides](../../izoomframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
