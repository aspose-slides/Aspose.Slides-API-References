---
title: Delimit
second_title: Aspose.Sildes para .NET Referencia de API
description: Delimita elementos hijos con carácter separador sin los corchetes
type: docs
weight: 90
url: /es/aspose.slides.mathtext/mathblock/delimit/
---

## MathBlock.Delimit método

Delimita elementos hijos con carácter separador (sin los corchetes)

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | Char | Carácter separador |

### Valor de retorno

El elemento matemático de tipo [`IMathDelimiter`](../../imathdelimiter)

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Delimit('|');
```

### Ver también

* interfaz [IMathDelimiter](../../imathdelimiter)
* clase [MathBlock](../../mathblock)
* namespace [Aspose.Slides.MathText](../../mathblock)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->