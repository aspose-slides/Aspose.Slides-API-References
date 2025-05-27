---
title: OperatorEmulator
second_title: Referencia de API de Aspose.Slides para .NET
description: Emulador de Operadores. Cuando es verdadero, la caja y su contenido se comportan como un solo operador e heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como un punto para un salto de línea y puede alinearse con otros operadores. Los Emuladores de Operadores se utilizan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor por defecto: falso
type: docs
weight: 70
url: /es/aspose.slides.mathtext/imathbox/operatoremulator/
---

## Propiedad IMathBox.OperatorEmulator

Emulador de Operadores. Cuando es verdadero, la caja y su contenido se comportan como un solo operador e heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como un punto para un salto de línea y puede alinearse con otros operadores. Los Emuladores de Operadores se utilizan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor por defecto: falso

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

### Ver También

* interfaz [IMathBox](../../imathbox)
* espacio de nombres [Aspose.Slides.MathText](../../imathbox)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->