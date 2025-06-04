---
title: Delimit
second_title: Referencia de la API de Aspose.Slides para .NET
description: Delimita todos los elementos secundarios con un carácter separador sin los corchetes
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imathblock/delimit/
---

## IMathBlock.Delimit método

Delimita todos los elementos secundarios con un carácter separador (sin los corchetes)

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | Char | Carácter utilizado como separador |

### Valor de Retorno

Instancia del elemento IMathDelimiter

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Delimit('|');
```

### Ver También

* interfaz [IMathDelimiter](../../imathdelimiter)
* interfaz [IMathBlock](../../imathblock)
* espacio de nombres [Aspose.Slides.MathText](../../imathblock)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->