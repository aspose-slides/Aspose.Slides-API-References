---
title: WriteAsEmf
second_title: Aspose.Sildes для .NET API Справочник
description: Сохраняет изображение SVG в файл EMF.
type: docs
weight: 50
url: /ru/aspose.slides/isvgimage/writeasemf/
---

## ISvgImage.WriteAsEmf method

Сохраняет изображение SVG в файл EMF.

```csharp
public void WriteAsEmf(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Целевой поток |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Целевой поток является **null** |

### Примеры

Следующий пример демонстрирует, как сохранить изображение SVG в метафайл.

```csharp
[C#]
// Создает новое изображение SVG
ISvgImage svgImage = new SvgImage(System.IO.File.ReadAllText("content.svg"));

// Сохраняет изображение SVG в метафайл
using (var fileStream = System.IO.File.OpenWrite("SvgAsEmf.emf"))
    svgImage.WriteAsEmf(fileStream);
```

Этот пример демонстрирует, как добавить изображение SVG в качестве метафайла в коллекцию изображений презентации.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    // Создает новое изображение SVG
    ISvgImage svgImage = new SvgImage(System.IO.File.ReadAllText("content.svg"));
    using (var memStream = new MemoryStream())
    {
        // Сохраняет изображение SVG в метафайл
        svgImage.WriteAsEmf(memStream);
        // Добавляет метафайл в коллекцию изображений
        pres.Images.AddImage(memStream.ToArray());
    }
}
```

### См. также

* интерфейс [ISvgImage](../../isvgimage)
* пространство имен [Aspose.Slides](../../isvgimage)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->