---
title: SeparatorCharacter
second_title: Referencia de API de Aspose.Slides para .NET
description: El carácter separador delimitador especifica el carácter que separa los argumentos en el objeto delimitador. El predeterminado es x7C.
type: docs
weight: 70
url: /es/aspose.slides.mathtext/imathdelimiter/separatorcharacter/
---

## Propiedad IMathDelimiter.SeparatorCharacter

El carácter separador delimitador especifica el carácter que separa los argumentos en el objeto delimitador. El predeterminado: '&#x7C;'.

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

* interfaz [IMathDelimiter](../../imathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../imathdelimiter)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITES: generado por xmldocmd para Aspose.Slides.dll -->
