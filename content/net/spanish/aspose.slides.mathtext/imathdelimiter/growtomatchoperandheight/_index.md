---
title: GrowToMatchOperandHeight
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es verdadero, los delimitadores crecen verticalmente para coincidir con la altura de su operando. El valor predeterminado es verdadero.
type: docs
weight: 60
url: /es/aspose.slides.mathtext/imathdelimiter/growtomatchoperandheight/
---

## Propiedad IMathDelimiter.GrowToMatchOperandHeight

Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es verdadero, los delimitadores crecen verticalmente para coincidir con la altura de su operando. El valor predeterminado es verdadero.

```csharp
public bool GrowToMatchOperandHeight { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Divide("y").Enclose();
delimiter.GrowToMatchOperandHeight = false;
```

### Véase También

* interfaz [IMathDelimiter](../../imathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../imathdelimiter)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->