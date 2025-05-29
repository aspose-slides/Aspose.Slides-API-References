---
title: Enclose
second_title: Aspose.Slides para .NET Referencia de la API
description: Encierra elementos secundarios de este bloque en caracteres especificados como paréntesis u otros como marco y delimita con un carácter separador
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathblock/enclose/
---

## IMathBlock.Enclose método

Encierra elementos secundarios de este bloque en caracteres especificados como paréntesis u otros como marco y delimita con un carácter separador

```csharp
public IMathDelimiter Enclose(char beginningCharacter, char endingCharacter, 
    char separatorCharacter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | Char | Carácter inicial (generalmente corchete izquierdo) |
| endingCharacter | Char | Carácter final (generalmente corchete derecho) |
| separatorCharacter | Char | Carácter separador |

### Valor de Retorno

El elemento matemático de tipo [`IMathDelimiter`](../../imathdelimiter) que incluye caracteres especificados como marco y delimitador

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Enclose('{', '}', '%');
```

### Ver También

* interfaz [IMathDelimiter](../../imathdelimiter)
* interfaz [IMathBlock](../../imathblock)
* espacio de nombres [Aspose.Slides.MathText](../../imathblock)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->