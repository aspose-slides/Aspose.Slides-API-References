---
title: Enclose
second_title: Referencia de la API de Aspose.Sildes para .NET
description: Encierra un elemento matemático en caracteres especificados como paréntesis u otros caracteres como marco
type: docs
weight: 90
url: /es/aspose.slides.mathtext/mathdelimiter/enclose/
---

## MathDelimiter.Enclose method

Encierra un elemento matemático en caracteres especificados como paréntesis u otros caracteres como marco

```csharp
public override IMathDelimiter Enclose(char beginningCharacter, char endingCharacter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | Char | Carácter inicial (generalmente corchete izquierdo) |
| endingCharacter | Char | Carácter final (generalmente corchete derecho) |

### Valor de Retorno

Si *beginningCharacter* y *endingCharacter* son nulos, se asignan valores únicamente a las propiedades correspondientes y no se crea un nuevo objeto (devuelve esta instancia). De lo contrario, devuelve un nuevo elemento matemático de tipo Delimiter que incluye caracteres especificados como marco y esta instancia de [`MathDelimiter`](../../mathdelimiter) enmarcada dentro.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathDelimiter innerDelimiter = new MathematicalText("x").Join(",y").Enclose('{', '}');
IMathDelimiter outerDelimiter = innerDelimiter.Enclose('[', ']');
```

### Ver También

* interfaz [IMathDelimiter](../../imathdelimiter)
* clase [MathDelimiter](../../mathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../mathdelimiter)
* ensamblaje [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->