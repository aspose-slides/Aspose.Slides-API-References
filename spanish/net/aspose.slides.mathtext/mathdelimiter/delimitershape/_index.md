---
title: DelimiterShape
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered los delimitadores se centran alrededor del eje matemático del texto matemático y todavía se ajustan a la altura completa de su contenido. Cuando es MathDelimiterShape.Match su altura y forma se modifican para que coincidan exactamente con su contenido .
type: docs
weight: 40
url: /es/net/aspose.slides.mathtext/mathdelimiter/delimitershape/
---
## MathDelimiter.DelimiterShape property

Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered, los delimitadores se centran alrededor del eje matemático del texto matemático y todavía se ajustan a la altura completa de su contenido. Cuando es MathDelimiterShape.Match, su altura y forma se modifican para que coincidan exactamente con su contenido .

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

### Ver también

* enum [MathDelimiterShape](../../mathdelimitershape)
* class [MathDelimiter](../../mathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../mathdelimiter)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->