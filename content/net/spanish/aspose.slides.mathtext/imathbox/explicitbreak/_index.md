---
title: ExplicitBreak
second_title: Referencia de API de Aspose.Slides para .NET
description: El salto explícito especifica si hay un salto de línea al comienzo del objeto Box de tal manera que la línea se ajuste al comienzo del objeto de caja. Especifica el número del operador en la línea anterior de texto matemático que se utilizará como punto de alineación para la línea actual de texto matemático valores posibles 1..255 Predeterminado 0 sin salto explícito
type: docs
weight: 50
url: /es/aspose.slides.mathtext/imathbox/explicitbreak/
---

## IMathBox.ExplicitBreak property

El salto explícito especifica si hay un salto de línea al comienzo del objeto Box, de tal manera que la línea se ajuste al comienzo del objeto de caja. Especifica el número del operador en la línea anterior de texto matemático que se utilizará como punto de alineación para la línea actual de texto matemático valores posibles: 1..255 Predeterminado: 0 (sin salto explícito)

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

### Ver también

* interfaz [IMathBox](../../imathbox)
* espacio de nombres [Aspose.Slides.MathText](../../imathbox)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->