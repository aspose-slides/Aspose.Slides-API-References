---
title: Subíndice
second_title: Referencia de la API de Aspose.Slides para .NET
description: Subíndice
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imathsubscriptelement/subscript/
---

## IMathSubscriptElement.Subscript propiedad

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

### Ver También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathSubscriptElement](../../imathsubscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathsubscriptelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->