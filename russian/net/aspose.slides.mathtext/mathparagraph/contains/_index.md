---
title: Contains
second_title: Справочник по API Aspose.Slides для .NET
description: Определяет содержит ли коллекция определенное значение.
type: docs
weight: 70
url: /ru/net/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph.Contains method

Определяет, содержит ли коллекция определенное значение.

```csharp
public bool Contains(IMathBlock mathBlock)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathBlock | IMathBlock | Объект для поиска в коллекции. |

### Возвращаемое значение

true, если*mathBlock*найден в коллекции; в противном случае ложно.

### Примеры

Пример:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Add(block);
bool contains = mathParagraph.Contains(block);
```

### Смотрите также

* interface [IMathBlock](../../imathblock)
* class [MathParagraph](../../mathparagraph)
* пространство имен [Aspose.Slides.MathText](../../mathparagraph)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->