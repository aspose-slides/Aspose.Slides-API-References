---
title: IMathRadical
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica la función radical que consiste en una base y un grado opcional. Un ejemplo de objeto radical es .
type: docs
weight: 8170
url: /es/aspose.slides.mathtext/imathradical/
---

## Interfaz IMathRadical

Especifica la función radical, que consiste en una base y un grado opcional. Un ejemplo de objeto radical es √𝑥.

```csharp
public interface IMathRadical : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathradical/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathradical/base) { get; } | Argumento base |
| [Degree](../../aspose.slides.mathtext/imathradical/degree) { get; } | Argumento de grado |
| [HideDegree](../../aspose.slides.mathtext/imathradical/hidedegree) { get; set; } | Ocultar grado Cuando es verdadero, el grado no se muestra, como en √𝑥 |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathRadical radical = new MathematicalText("x").Radical("3"); // raíz cúbica
```

### Ver También

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->