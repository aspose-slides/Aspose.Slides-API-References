---
title: IMathFunction
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica una función de un argumento.
type: docs
weight: 8020
url: /es/aspose.slides.mathtext/imathfunction/
---

## Interfaz IMathFunction

Especifica una función de un argumento.

```csharp
public interface IMathFunction : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathfunction/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathfunction/base) { get; } | Argumento de la función |
| [Name](../../aspose.slides.mathtext/imathfunction/name) { get; } | Nombre de la función. Por ejemplo, los nombres de funciones son sin y cos |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathFunction sinX = new MathematicalText("sin").Function("x");
```

### Ver También

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->