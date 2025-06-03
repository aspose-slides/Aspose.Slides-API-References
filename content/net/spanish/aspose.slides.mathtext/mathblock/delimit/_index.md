---
title: Delimit
second_title: Referencia de la API Aspose.Slides para .NET
description: Delimita elementos secundarios con un carácter separador sin los corchetes
type: docs
weight: 90
url: /es/aspose.slides.mathtext/mathblock/delimit/
---

## Método MathBlock.Delimit

Delimita elementos secundarios con un carácter separador (sin los corchetes)

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | Char | Carácter separador |

### Valor de Retorno

El elemento matemático de tipo [`IMathDelimiter`](../../imathdelimiter)

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Delimit('|');
```

### Ver También

* interfaz [IMathDelimiter](../../imathdelimiter)
* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->