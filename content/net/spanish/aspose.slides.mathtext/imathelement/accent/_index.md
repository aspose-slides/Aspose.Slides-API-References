---
title: Accent
second_title: Referencia de API de Aspose.Slides para .NET
description: Establece un signo de acento un carácter en la parte superior de este elemento
type: docs
weight: 10
url: /es/aspose.slides.mathtext/imathelement/accent/
---

## Método IMathElement.Accent

Establece un signo de acento (un carácter en la parte superior de este elemento)

```csharp
public IMathAccent Accent(char accentCharacter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| accentCharacter | Char | Carácter de acento. El valor debe estar dentro del rango de (U+0300–U+036F) o (U+20D0–U+20EF) |

### Valor de Retorno

Nueva instancia del tipo [`IMathAccent`](../../imathaccent)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
```

### Véase También

* interfaz [IMathAccent](../../imathaccent)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->