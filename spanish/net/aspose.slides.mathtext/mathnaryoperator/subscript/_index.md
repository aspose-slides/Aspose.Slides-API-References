---
title: Subscript
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica un argumento de subíndice que por ejemplo en el caso de una integral establece el límite inferior
type: docs
weight: 80
url: /es/net/aspose.slides.mathtext/mathnaryoperator/subscript/
---
## MathNaryOperator.Subscript property

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

### Ver también

* interface [IMathElement](../../imathelement)
* class [MathNaryOperator](../../mathnaryoperator)
* espacio de nombres [Aspose.Slides.MathText](../../mathnaryoperator)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->