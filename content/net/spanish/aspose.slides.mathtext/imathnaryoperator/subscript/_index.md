---
title: Subíndice
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica un argumento de subíndice que, por ejemplo, en el caso de una integral establece el límite inferior
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathnaryoperator/subscript/
---

## IMathNaryOperator.Subscript property

Especifica un argumento de subíndice que, por ejemplo, en el caso de una integral, establece el límite inferior

```csharp
public IMathElement Subscript { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
IMathElement subscriptArg = naryOperator.Subscript;
```

### Véase También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathNaryOperator](../../imathnaryoperator)
* espacio de nombres [Aspose.Slides.MathText](../../imathnaryoperator)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->