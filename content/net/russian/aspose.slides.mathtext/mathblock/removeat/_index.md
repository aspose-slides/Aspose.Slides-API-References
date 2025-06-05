---
title: RemoveAt
second_title: Aspose.Sildes для .NET API Справочник
description: Удаляет элемент по указанному индексу коллекции.
type: docs
weight: 170
url: /ru/aspose.slides.mathtext/mathblock/removeat/
---

## MathBlock.RemoveAt метод

Удаляет элемент по указанному индексу коллекции.

```csharp
public void RemoveAt(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Нулевой индекс элемента, который нужно удалить. |

### Примеры

Пример:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
mathBlock.RemoveAt(2);
```

### См. Также

* класс [MathBlock](../../mathblock)
* пространство имен [Aspose.Slides.MathText](../../mathblock)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->