---
title: VerticalJustification
second_title: Referencia de API de Aspose.Slides para .NET
description: Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está por encima del objeto, la justificación vertical de Top significa que la parte superior del objeto cae sobre la línea base; cuando la justificación vertical se establece en Bottom, la parte inferior del objeto está en la línea base. Predeterminado: Bottom para Position=Top, y Top para Position=Bottom
type: docs
weight: 50
url: /es/aspose.slides.mathtext/imathgroupingcharacter/verticaljustification/
---

## Propiedad IMathGroupingCharacter.VerticalJustification

Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está por encima del objeto, la justificación vertical de Top significa que la parte superior del objeto cae sobre la línea base; cuando la justificación vertical se establece en Bottom, la parte inferior del objeto está en la línea base. Predeterminado: Bottom para Position=Top, y Top para Position=Bottom

```csharp
public MathTopBotPositions VerticalJustification { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
groupingCharacter.VerticalJustification = MathTopBotPositions.Top;
```

### Ver También

* enum [MathTopBotPositions](../../mathtopbotpositions)
* interface [IMathGroupingCharacter](../../imathgroupingcharacter)
* namespace [Aspose.Slides.MathText](../../imathgroupingcharacter)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->