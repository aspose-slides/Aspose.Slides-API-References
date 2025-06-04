---
title: IMathAccent
second_title: Aspose.Slides para .NET Referencia de API
description: Especifica la función de acento que consiste en una base y una marca diacrítica combinada Ejemplo ́
type: docs
weight: 7830
url: /es/aspose.slides.mathtext/imathaccent/
---

## Interfaz IMathAccent

Especifica la función de acento, que consiste en una base y una marca diacrítica combinada Ejemplo: 𝑎́

```csharp
public interface IMathAccent : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathaccent/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathaccent/base) { get; } | El argumento al que se aplicó el acento |
| [Character](../../aspose.slides.mathtext/imathaccent/character) { get; set; } | Carácter de acento El valor debe estar dentro del rango de (U+0300–U+036F) o (U+20D0–U+20EF) Valor por defecto: Acento circunflejo combinado (U+0302) |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
```

### Véase También

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->