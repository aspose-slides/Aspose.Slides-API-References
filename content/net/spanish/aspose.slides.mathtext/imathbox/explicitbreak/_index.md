---
title: ExplicitBreak
second_title: Referencia de API de Aspose.Slides para .NET
description: La ruptura explícita especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelve al inicio del objeto Box. Especifica el número del operador en la línea anterior de texto matemático que se utilizará como punto de alineación para la línea actual de texto matemático. Valores posibles 1..255. Predeterminado 0 sin ruptura explícita.
type: docs
weight: 50
url: /es/aspose.slides.mathtext/imathbox/explicitbreak/
---

## Propiedad IMathBox.ExplicitBreak

La ruptura explícita especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelve al inicio del objeto Box. Especifica el número del operador en la línea anterior de texto matemático que se utilizará como punto de alineación para la línea actual de texto matemático. Valores posibles: 1..255. Predeterminado: 0 (sin ruptura explícita).

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

* interfaz [IMathBox](../../imathbox)
* espacio de nombres [Aspose.Slides.MathText](../../imathbox)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->