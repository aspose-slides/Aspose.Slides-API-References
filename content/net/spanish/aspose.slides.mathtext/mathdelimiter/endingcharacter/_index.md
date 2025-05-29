---
title: EndingCharacter
second_title: Referencia de API de Aspose.Slides para .NET
description: El carácter delimitador de cierre especifica el carácter de delimitador de cierre. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor por defecto.
type: docs
weight: 50
url: /es/aspose.slides.mathtext/mathdelimiter/endingcharacter/
---

## Propiedad MathDelimiter.EndingCharacter

El carácter delimitador de cierre especifica el carácter de delimitador de cierre. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor por defecto: ')'.

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
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->