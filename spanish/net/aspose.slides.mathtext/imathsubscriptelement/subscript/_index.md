---
title: Subscript
second_title: Referencia de la API de Aspose.Slides para .NET
description: Subíndice
type: docs
weight: 30
url: /es/net/aspose.slides.mathtext/imathsubscriptelement/subscript/
---
## IMathSubscriptElement.Subscript property

Subíndice

```csharp
public IMathElement Subscript { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
IMathElement sub = subscriptElement.Subscript;
```

### Ver también

* interface [IMathElement](../../imathelement)
* interface [IMathSubscriptElement](../../imathsubscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathsubscriptelement)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->