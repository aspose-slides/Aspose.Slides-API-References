---
title: Item
second_title: Aspose.Sildes для .NET API Ссылки
description: Получает элемент по указанному индексу. Только для чтения IMathElementaspose.slides.mathtext/imathelement.
type: docs
weight: 30
url: /ru/aspose.slides.mathtext/imathelementcollection/item/
---

## Индексатор IMathElementCollection

Получает элемент по указанному индексу. Только для чтения [`IMathElement`](../../imathelement).

```csharp
public IMathElement this[int index] { get; }
```

| Параметр | Описание |
| --- | --- |
| index | Нулевой индекс элемента, который нужно получить |

### Примеры

Пример:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
IMathElement firstElem = collection[0];
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* интерфейс [IMathElementCollection](../../imathelementcollection)
* пространство имён [Aspose.Slides.MathText](../../imathelementcollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->