---
title: IMathRadical
second_title: Aspose.Silides для .NET API Справка
description: Указывает радикальную функцию, состоящую из основания и необязательной степени. Пример радикального объекта - .
type: docs
weight: 8170
url: /ru/aspose.slides.mathtext/imathradical/
---

## Интерфейс IMathRadical

Указывает радикальную функцию, состоящую из основания и необязательной степени. Пример радикального объекта - √𝑥.

```csharp
public interface IMathRadical : IMathElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathradical/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathradical/base) { get; } | Аргумент основания |
| [Degree](../../aspose.slides.mathtext/imathradical/degree) { get; } | Аргумент степени |
| [HideDegree](../../aspose.slides.mathtext/imathradical/hidedegree) { get; set; } | Скрыть степень Когда истинно, степень не отображается, как в √𝑥 |

### Примеры

Пример:

```csharp
[C#]
IMathRadical radical = new MathematicalText("x").Radical("3"); // кубический корень
```

### См. также

* интерфейс [IMathElement](../imathelement)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->