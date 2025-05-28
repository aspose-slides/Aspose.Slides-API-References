---
title: SeparatorCharacter
second_title: Referencia de API de Aspose.Slides para .NET
description: El caracter separador de delimitadores especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado es x7C.
type: docs
weight: 70
url: /es/aspose.slides.mathtext/mathdelimiter/separatorcharacter/
---

## Propiedad MathDelimiter.SeparatorCharacter

El caracter separador de delimitadores especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '&#x7C;'.

```csharp
public char SeparatorCharacter { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.SeparatorCharacter = '$';
```

### Véase También

* clase [MathDelimiter](../../mathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../mathdelimiter)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->