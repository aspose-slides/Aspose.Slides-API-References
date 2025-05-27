---
title: IMathLimit
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica el objeto Limit que consiste en texto en la línea base y texto de tamaño reducido inmediatamente arriba o abajo de él.
type: docs
weight: 8070
url: /es/aspose.slides.mathtext/imathlimit/
---

## Interfaz IMathLimit

Especifica el objeto Limit, que consiste en texto en la línea base y texto de tamaño reducido inmediatamente arriba o abajo de él.

```csharp
public interface IMathLimit : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathlimit/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathlimit/base) { get; } | Argumento base |
| [Limit](../../aspose.slides.mathtext/imathlimit/limit) { get; } | Argumento del límite |
| [UpperLimit](../../aspose.slides.mathtext/imathlimit/upperlimit) { get; set; } | Especifica el límite superior o inferior |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("𝑛→∞"));
```

### Véase También

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->