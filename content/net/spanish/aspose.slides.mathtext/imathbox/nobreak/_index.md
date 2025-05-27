---
title: NoBreak
second_title: Aspose.Slides para .NET Referencia de API
description: Sin salto. Esta propiedad especifica la propiedad "ininterrumpible" en el cuadro de objeto. Cuando es verdadero, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para emuladores de operadores que consisten en más de un operador binario. Cuando este elemento no está especificado, pueden ocurrir saltos dentro del cuadro. Predeterminado: verdadero
type: docs
weight: 60
url: /es/aspose.slides.mathtext/imathbox/nobreak/
---

## IMathBox.NoBreak propiedad

Sin salto. Esta propiedad especifica la propiedad "ininterrumpible" en el cuadro de objeto. Cuando es verdadero, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para emuladores de operadores que consisten en más de un operador binario. Cuando este elemento no está especificado, pueden occur saltos dentro del cuadro. Predeterminado: verdadero

```csharp
public bool NoBreak { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBox box = new MathematicalText("**********").ToBox();
box.NoBreak = false;
```

### Véase también

* interfaz [IMathBox](../../imathbox)
* espacio de nombres [Aspose.Slides.MathText](../../imathbox)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->