---
title: NoBreak
second_title: Referencia de la API de Aspose.Slides para .NET
description: Sin interrupción Esta propiedad especifica la propiedad irrompible en el cuadro del objeto. Cuando es verdadero no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para los emuladores de operadores que constan de más de un operador binario. Cuando no se especifica este elemento pueden producirse rupturas dentro del cuadro. Valor predeterminado true
type: docs
weight: 60
url: /es/aspose.slides.mathtext/mathbox/nobreak/
---
## MathBox.NoBreak property

Sin interrupción Esta propiedad especifica la propiedad "irrompible" en el cuadro del objeto. Cuando es verdadero, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para los emuladores de operadores que constan de más de un operador binario. Cuando no se especifica este elemento, pueden producirse rupturas dentro del cuadro. Valor predeterminado: true

```csharp
public bool NoBreak { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("*****"));
box.NoBreak = false;
```

### Ver también

* class [MathBox](../../mathbox)
* espacio de nombres [Aspose.Slides.MathText](../../mathbox)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
