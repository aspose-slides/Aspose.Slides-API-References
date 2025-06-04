---
title: ZoomImage
second_title: Aspose.Sildes для .NET API Справочник
description: Получает или устанавливает изображение для объекта увеличения. Чтение/запись IPPImageaspose.slides/ippimage.
type: docs
weight: 50
url: /ru/aspose.slides/zoomobject/zoomimage/
---

## ZoomObject.ZoomImage свойство

Получает или устанавливает изображение для объекта увеличения. Чтение/запись [`IPPImage`](../../ippimage).

```csharp
public IPPImage ZoomImage { get; set; }
```

### Примеры

Пример демонстрирует изменение изображения объекта увеличения:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    zoomFrame.Image = image;
}
```

### См. также

* интерфейс [IPPImage](../../ippimage)
* класс [ZoomObject](../../zoomobject)
* пространство имен [Aspose.Slides](../../zoomobject)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->
