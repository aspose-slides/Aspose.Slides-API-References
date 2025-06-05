---
title: Base
second_title: Aspose.Sildes для .NET API Справочник
description: Базовый аргумент
type: docs
weight: 20
url: /ru/aspose.slides.mathtext/imathsuperscriptelement/base/
---

## IMathSuperscriptElement.Base свойство

Базовый аргумент

```csharp
public IMathElement Base { get; }
```

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement superscript = new MathematicalText("i");
IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
IMathElement baseElem = superscriptElement.Base;
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* интерфейс [IMathSuperscriptElement](../../imathsuperscriptelement)
* пространство имен [Aspose.Slides.MathText](../../imathsuperscriptelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->