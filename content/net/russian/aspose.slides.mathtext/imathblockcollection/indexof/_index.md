---
title: IndexOf
second_title: Aspose.Slides для .NET API Справочник
description: Определяет индекс конкретного IMathBlock в коллекции.
type: docs
weight: 70
url: /ru/aspose.slides.mathtext/imathblockcollection/indexof/
---

## Метод IMathBlockCollection.IndexOf

Определяет индекс конкретного IMathBlock в коллекции.

```csharp
public int IndexOf(IMathBlock item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | IMathBlock | Элемент, который нужно найти в коллекции. |

### Возвращаемое значение

Индекс *item*, если он найден в коллекции; в противном случае, -1.

### Примеры

Пример:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
int index = blockCollection.IndexOf(block);
```

### См. также

* интерфейс [IMathBlock](../../imathblock)
* интерфейс [IMathBlockCollection](../../imathblockcollection)
* пространство имен [Aspose.Slides.MathText](../../imathblockcollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->