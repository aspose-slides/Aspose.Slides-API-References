---
title: IMathAccent
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica la función de acento que consta de una base y un signo diacrítico combinante Ejemplo ́
type: docs
weight: 7830
url: /es/aspose.slides.mathtext/imathaccent/
---

## Interfaz IMathAccent

Especifica la función de acento, que consiste en una base y un signo diacrítico combinante Ejemplo: 𝑎́

```csharp
public interface IMathAccent : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathaccent/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathaccent/base) { get; } | El argumento al que se le aplicó el acento |
| [Character](../../aspose.slides.mathtext/imathaccent/character) { get; set; } | Carácter de acento El valor debe estar dentro del rango de (U+0300–U+036F) o (U+20D0–U+20EF) Valor predeterminado: Acento circunflejo combinante (U+0302) |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
```

### Véase también

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->