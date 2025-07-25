---
title: AlignScripts
second_title: Aspose.Slides для .NET API Справочник
description: Указывает выравнивание нижнего/верхнего индекса. Если значение true, нижний и верхний индексы выровнены горизонтально друг относительно друга. Если значение false, они размещаются в соответствии с формой основы. Значение по умолчанию - false.
type: docs
weight: 20
url: /ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts/
---

## MathRightSubSuperscriptElement.AlignScripts свойство

Указывает выравнивание нижнего/верхнего индекса. Если значение true, нижний и верхний индексы выровнены горизонтально друг относительно друга. Если значение false, они размещаются в соответствии с формой основы. Значение по умолчанию - false.

```csharp
public bool AlignScripts { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
subsuperscript.AlignScripts = true;
```

### Также см.

* класс [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* пространство имен [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->