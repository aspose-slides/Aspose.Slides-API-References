---
title: Add
second_title: Справочник по API Aspose.Slides для .NET
description: Добавляет математический элемент в конец коллекции.
type: docs
weight: 40
url: /ru/net/aspose.slides.mathtext/imathelementcollection/add/
---
## IMathElementCollection.Add method

Добавляет математический элемент в конец коллекции.

```csharp
public void Add(IMathElement item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | IMathElement | Элемент IMathElement, добавляемый в конец коллекции. |

### Примеры

Пример:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
collection.Add(new MathematicalText("+"));
collection.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### Смотрите также

* interface [IMathElement](../../imathelement)
* interface [IMathElementCollection](../../imathelementcollection)
* пространство имен [Aspose.Slides.MathText](../../imathelementcollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->