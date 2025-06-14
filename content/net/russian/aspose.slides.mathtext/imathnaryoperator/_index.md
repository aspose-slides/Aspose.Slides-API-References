---
title: IMathNaryOperator
second_title: Aspose.Slides для .NET API Reference
description: Указывает на N-арный математический объект, такой как суммирование и интеграл. Он состоит из оператора, базы или операнда и необязательных верхних и нижних пределов. Примеры N-арных операторов суммирование, объединение, пересечение, интеграл
type: docs
weight: 8110
url: /ru/aspose.slides.mathtext/imathnaryoperator/
---

## Интерфейс IMathNaryOperator

Указывает на N-арный математический объект, такой как суммирование и интеграл. Он состоит из оператора, базы (или операнда) и необязательных верхних и нижних пределов. Примеры N-арных операторов: суммирование, объединение, пересечение, интеграл

```csharp
public interface IMathNaryOperator : IMathElement, IMathNaryOperatorProperties
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathnaryoperator/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [AsIMathNaryOperatorProperties](../../aspose.slides.mathtext/imathnaryoperator/asimathnaryoperatorproperties) { get; } | Позволяет получить базовый интерфейс IMathNaryOperatorProperties [`IMathNaryOperatorProperties`](../imathnaryoperatorproperties) |
| [Base](../../aspose.slides.mathtext/imathnaryoperator/base) { get; } | Аргумент базы |
| [Subscript](../../aspose.slides.mathtext/imathnaryoperator/subscript) { get; } | Указывает на аргумент нижнего индекса, который, например, в случае интеграла устанавливает нижний предел |
| [Superscript](../../aspose.slides.mathtext/imathnaryoperator/superscript) { get; } | Указывает на аргумент верхнего индекса, который, например, в случае интеграла устанавливает верхний предел |

### Примеры

Пример:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### См. также

* интерфейс [IMathElement](../imathelement)
* интерфейс [IMathNaryOperatorProperties](../imathnaryoperatorproperties)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->