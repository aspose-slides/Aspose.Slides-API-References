---
title: IMathSubscriptElement
second_title: Справочник по API Aspose.Slides для .NET
description: Определяет объект нижнего индекса который состоит из базового и нижнего индекса уменьшенного размера расположенного ниже и правее.
type: docs
weight: 7750
url: /ru/aspose.slides.mathtext/imathsubscriptelement/
---
## IMathSubscriptElement interface

Определяет объект нижнего индекса, который состоит из базового и нижнего индекса уменьшенного размера, расположенного ниже и правее.

```csharp
public interface IMathSubscriptElement : IMathElement
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathsubscriptelement/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathsubscriptelement/base) { get; } | Базовый аргумент |
| [Subscript](../../aspose.slides.mathtext/imathsubscriptelement/subscript) { get; } | Нижний индекс |

### Примеры

Пример:

```csharp
[C#]
IMathSubscriptElement subscriptElement = new MathematicalText("N").SetSubscript("i");
```

### Смотрите также

* interface [IMathElement](../imathelement)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
