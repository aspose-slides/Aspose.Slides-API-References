---
title: EndingCharacter
second_title: Referencia de API de Aspose.Slides para .NET
description: El carácter de finalización del delimitador especifica el carácter delimitador de finalización o cierre. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado.
type: docs
weight: 50
url: /es/aspose.slides.mathtext/imathdelimiter/endingcharacter/
---

## Propiedad IMathDelimiter.EndingCharacter

El carácter de finalización del delimitador especifica el carácter delimitador de finalización o cierre. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

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

* interfaz [IMathDelimiter](../../imathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../imathdelimiter)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->