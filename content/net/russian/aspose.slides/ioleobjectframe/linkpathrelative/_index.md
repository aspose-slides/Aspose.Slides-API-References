---
title: LinkPathRelative
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. Свойство только для чтения типа String.
type: docs
weight: 90
url: /ru/aspose.slides/ioleobjectframe/linkpathrelative/
---

## Свойство IOleObjectFrame.LinkPathRelative

Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. Свойство только для чтения типа String.

```csharp
public string LinkPathRelative { get; }
```

### Примечания

В презентациях Ppt некоторые ссылки на Ole-объекты могут иметь относительное представление.

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.ppt"))
{
    IOleObjectFrame oleFrame = presentation.Slides[0].Shapes[0] as IOleObjectFrame;

    if (oleFrame != null)
    {
        Console.WriteLine("Относительный путь: " + oleFrame.LinkPathRelative);
    } 
}
```

### См. также

* интерфейс [IOleObjectFrame](../../ioleobjectframe)
* пространство имен [Aspose.Slides](../../ioleobjectframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->