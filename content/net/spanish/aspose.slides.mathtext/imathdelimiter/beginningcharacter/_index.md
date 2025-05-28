---
title: BeginningCharacter
second_title: Referencia de API de Aspose.Slides para .NET
description: El carácter delimitador de inicio especifica el carácter delimitador de inicio o apertura. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado.
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imathdelimiter/beginningcharacter/
---

## Propiedad IMathDelimiter.BeginningCharacter

El carácter delimitador de inicio especifica el carácter delimitador de inicio o apertura. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: '('.

```csharp
public char BeginningCharacter { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.BeginningCharacter = '[';
```

### Véase también

* interfaz [IMathDelimiter](../../imathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../imathdelimiter)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->