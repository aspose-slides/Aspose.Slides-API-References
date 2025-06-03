---
title: Contains
second_title: Справочник по API Aspose.Slides для .NET
description: Определяет, содержит ли коллекция определенное значение.
type: docs
weight: 70
url: /ru/aspose.slides.mathtext/mathblock/contains/
---

## Метод MathBlock.Contains

Определяет, содержит ли коллекция определенное значение.

```csharp
public bool Contains(IMathElement item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | IMathElement | Объект, который необходимо найти в коллекции. |

### Возвращаемое значение

true, если *item* найден в коллекции; в противном случае — false.

### Примеры

Пример:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
bool contains = mathBlock.Contains(plusElement);
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* класс [MathBlock](../../mathblock)
* пространство имен [Aspose.Slides.MathText](../../mathblock)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->