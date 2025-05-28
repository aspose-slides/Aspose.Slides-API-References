---
title: JoinBlock
second_title: Referencia de API de Aspose.Slides para .NET
description: Une otro bloque matemático con este
type: docs
weight: 50
url: /es/aspose.slides.mathtext/imathblock/joinblock/
---

## Método IMathBlock.JoinBlock

Une otro bloque matemático con este

```csharp
public IMathBlock JoinBlock(IMathBlock other)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | IMathBlock | El bloque a unir |

### Valor de Retorno

este bloque matemático después de unir

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).Join(new MathematicalText("="));
IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).Join(new MathematicalText("+"))
.Join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
IMathBlock block3 = block1.JoinBlock(block2);
```

### Véase También

* interface [IMathBlock](../../imathblock)
* namespace [Aspose.Slides.MathText](../../imathblock)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->