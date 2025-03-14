---
title: OperatorEmulator
second_title: Referencia de la API de Aspose.Slides para .NET
description: Emulador de operador. Cuando es verdadero el cuadro y su contenido se comportan como un solo operador y heredan las propiedades de un operador. Esto significa por ejemplo que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operadores se usan a menudo cuando uno o más glifos se combinan para formar un operador como  . Valor por defecto false
type: docs
weight: 70
url: /es/aspose.slides.mathtext/imathbox/operatoremulator/
---
## IMathBox.OperatorEmulator property

Emulador de operador. Cuando es verdadero, el cuadro y su contenido se comportan como un solo operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operadores se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '==' . Valor por defecto: false

```csharp
public bool OperatorEmulator { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
box.OperatorEmulator = true;
```

### Ver también

* interface [IMathBox](../../imathbox)
* espacio de nombres [Aspose.Slides.MathText](../../imathbox)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
