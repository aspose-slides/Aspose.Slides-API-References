---
title: Superscript
second_title: Aspose.Sildes для .NET API Справочник
description: Аргумент верхнего индекса
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/
---

## MathRightSubSuperscriptElement.Superscript свойство

Аргумент верхнего индекса

```csharp
public IMathElement Superscript { get; }
```

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sup = subsuperscript.Superscript;
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* класс [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* пространство имен [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->