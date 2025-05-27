---
title: ExplicitBreak
second_title: Referencia de API de Aspose.Slides para .NET
description: El descanso explícito especifica si hay un salto de línea al inicio del objeto Box, de tal manera que la línea se ajuste al comienzo del objeto de la caja. Especifica el número del operador en la línea anterior del texto matemático que se utilizará como punto de alineación para la línea actual del texto matemático, valores posibles 1..255. Predeterminado 0 sin descanso explícito
type: docs
weight: 50
url: /es/aspose.slides.mathtext/mathbox/explicitbreak/
---

## Propiedad MathBox.ExplicitBreak

El descanso explícito especifica si hay un salto de línea al inicio del objeto Box, de tal manera que la línea se ajuste al comienzo del objeto de la caja. Especifica el número del operador en la línea anterior del texto matemático que se utilizará como punto de alineación para la línea actual del texto matemático, valores posibles: 1..255. Predeterminado: 0 (sin descanso explícito)

```csharp
public byte ExplicitBreak { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
box.ExplicitBreak = 1;
```

### Véase También

* clase [MathBox](../../mathbox)
* espacio de nombres [Aspose.Slides.MathText](../../mathbox)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->