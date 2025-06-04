---
title: Subscript
second_title: Aspose.Sildes для .NET API Справка
description: Указывает аргумент подстрочного текста, который, например, в случае интеграла задает нижний предел
type: docs
weight: 80
url: /ru/aspose.slides.mathtext/mathnaryoperator/subscript/
---

## MathNaryOperator.Subscript property

Указывает аргумент подстрочного текста, который, например, в случае интеграла, задает нижний предел

```csharp
public IMathElement Subscript { get; }
```

### Примеры

Пример:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
IMathElement subscriptArg = naryOperator.Subscript;
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* класс [MathNaryOperator](../../mathnaryoperator)
* пространство имен [Aspose.Slides.MathText](../../mathnaryoperator)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->