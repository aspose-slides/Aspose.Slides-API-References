---
title: ShowBackground
second_title: Aspose.Sildes для .NET API Справочник
description: Получает или задает значение, определяющее, будет ли Zoom использовать фон целевого слайда. Читаемое/записываемое логическое значение. Значение по умолчанию true
type: docs
weight: 30
url: /ru/aspose.slides/zoomobject/showbackground/
---

## ZoomObject.ShowBackground свойство

Получает или задает значение, определяющее, будет ли Zoom использовать фон целевого слайда. Читаемое/записываемое логическое значение. Значение по умолчанию: true

```csharp
public bool ShowBackground { get; set; }
```

### Примеры

пример демонстрирует удаление фона изображения объекта Zoom:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.ShowBackground = false;
}
```

### См. Также

* класс [ZoomObject](../../zoomobject)
* пространство имен [Aspose.Slides](../../zoomobject)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->