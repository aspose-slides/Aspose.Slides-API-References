---
title: ParentCell
second_title: Aspose.Slides для .NET API Reference
description: Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс ICell. Только для чтения ICellaspose.slides/icell.
type: docs
weight: 40
url: /ru/aspose.slides/itextframe/parentcell/
---

## ITextFrame.ParentCell свойство

Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс ICell. Только для чтения [`ICell`](../../icell).

```csharp
public ICell ParentCell { get; }
```

### Примеры

Следующий пример кода показывает

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
    Table table = (Table)presentation.Slides[0].Shapes[0];
    
    Assert.IsTrue(table[0,0].TextFrame.ParentCell == table[0,0]);
    // ...
}
```

### См. также

* интерфейс [ICell](../../icell)
* интерфейс [ITextFrame](../../itextframe)
* пространство имен [Aspose.Slides](../../itextframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->