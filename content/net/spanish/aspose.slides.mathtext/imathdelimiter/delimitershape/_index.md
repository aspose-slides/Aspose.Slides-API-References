---
title: DelimiterShape
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered, los delimitadores están centrados alrededor del eje matemático del texto matemático y aún se pueden ajustar para que se adapten a toda la altura de su contenido. Cuando es MathDelimiterShape.Match, su altura y forma se alteran para coincidir exactamente con su contenido.
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathdelimiter/delimitershape/
---

## Propiedad IMathDelimiter.DelimiterShape

Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered, los delimitadores están centrados alrededor del eje matemático del texto matemático y aún se pueden ajustar para que se adapten a toda la altura de su contenido. Cuando es MathDelimiterShape.Match, su altura y forma se alteran para coincidir exactamente con su contenido.

```csharp
public MathDelimiterShape DelimiterShape { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Divide("y").Enclose();
delimiter.DelimiterShape = MathDelimiterShape.Match;
```

### Véase También

* enum [MathDelimiterShape](../../mathdelimitershape)
* interface [IMathDelimiter](../../imathdelimiter)
* namespace [Aspose.Slides.MathText](../../imathdelimiter)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->