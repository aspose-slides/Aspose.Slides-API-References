---
title: Base
second_title: Справочник по API Aspose.Slides для .NET
description: Базовый аргумент
type: docs
weight: 30
url: /ru/aspose.slides.mathtext/imathrightsubsuperscriptelement/base/
---
## IMathRightSubSuperscriptElement.Base property

Базовый аргумент

```csharp
public IMathElement Base { get; }
```

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement baseElem = subsuperscript.Base;
```

### Смотрите также

* interface [IMathElement](../../imathelement)
* interface [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* пространство имен [Aspose.Slides.MathText](../../imathrightsubsuperscriptelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
