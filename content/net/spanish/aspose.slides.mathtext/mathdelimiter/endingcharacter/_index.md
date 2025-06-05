---
title: EndingCharacter
second_title: Referencia de API de Aspose.Slides para .NET
description: El carácter delimitador de cierre especifica el carácter delimitador de cierre o final. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado.
type: docs
weight: 50
url: /es/aspose.slides.mathtext/mathdelimiter/endingcharacter/
---

## Propiedad MathDelimiter.EndingCharacter

El carácter delimitador de cierre especifica el carácter delimitador de cierre o final. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

```csharp
public char EndingCharacter { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.EndingCharacter = ']';
```

### Ver También

* clase [MathDelimiter](../../mathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../mathdelimiter)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->