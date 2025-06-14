---
title: ParentShape
second_title: Aspose.Sildes для .NET API Справочник
description: Возвращает родительскую фигуру или null, если родительский объект не реализует интерфейс IShape Только для чтения IShapeaspose.slides/ishape.
type: docs
weight: 40
url: /ru/aspose.slides/textframe/parentshape/
---

## TextFrame.ParentShape свойство

Возвращает родительскую фигуру или null, если родительский объект не реализует интерфейс IShape Только для чтения [`IShape`](../../ishape).

```csharp
public IShape ParentShape { get; }
```

### Примеры

Следующий кодовый пример показывает

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
    AutoShape autoShape = (AutoShape)presentation.Slides[0].Shapes[0];
    
    Assert.IsTrue(autoShape.TextFrame.ParentShape == autoShape);
    // ...
}
```

### Также смотрите

* интерфейс [IShape](../../ishape)
* класс [TextFrame](../../textframe)
* пространство имен [Aspose.Slides](../../textframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->