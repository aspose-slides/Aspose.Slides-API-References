---
title: Base
second_title: Aspose.Slides для .NET API Справочник
description: Базовый аргумент
type: docs
weight: 20
url: /ru/aspose.slides.mathtext/imathsubscriptelement/base/
---

## IMathSubscriptElement.Base свойство

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
MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
IMathElement baseElem = subscriptElement.Base;
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* интерфейс [IMathSubscriptElement](../../imathsubscriptelement)
* пространство имен [Aspose.Slides.MathText](../../imathsubscriptelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->