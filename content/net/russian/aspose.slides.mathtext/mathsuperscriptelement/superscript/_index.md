---
title: Superscript
second_title: Aspose.Sildes для .NET API Справка
description: Надстрочный текст
type: docs
weight: 20
url: /ru/aspose.slides.mathtext/mathsuperscriptelement/superscript/
---

## MathSuperscriptElement.Superscript свойство

Надстрочный текст

```csharp
public IMathElement Superscript { get; }
```

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement superscript = new MathematicalText("i");
MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
IMathElement super = superscriptElement.Superscript;
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* класс [MathSuperscriptElement](../../mathsuperscriptelement)
* пространство имен [Aspose.Slides.MathText](../../mathsuperscriptelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
