---
title: IMathAccent
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica la función de acento que consta de una base y un signo diacrítico combinado Ejemplo ́
type: docs
weight: 7370
url: /es/aspose.slides.mathtext/imathaccent/
---
## IMathAccent interface

Especifica la función de acento, que consta de una base y un signo diacrítico combinado Ejemplo: 𝑎́

```csharp
public interface IMathAccent : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathaccent/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathaccent/base) { get; } | El argumento al que se aplicó el acento |
| [Character](../../aspose.slides.mathtext/imathaccent/character) { get; set; } | Carácter de acento El valor debe estar dentro del rango de (U+0300–U+036F) o(U+20D0–U+20EF) Valor predeterminado: combinación de acento circunflejo (U+0302) |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
```

### Ver también

* interface [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
