---
title: Remove
second_title: Referencia de API de Aspose.Sildes para .NET
description: Elimina la primera ocurrencia de una fuente FallBack específica de la lista.
type: docs
weight: 90
url: /es/aspose.slides/fontfallbackrule/remove/
---

## Método FontFallBackRule.Remove

Elimina la primera ocurrencia de una fuente FallBack específica de la lista.

```csharp
public void Remove(string fontName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | El nombre de la fuente que se debe eliminar de la lista. |

### Ejemplos

```csharp
[C#]
// Crear una regla que contenga una lista de fuentes.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Eliminar Tahoma de la lista.
newRule.Remove ("Tahoma");
```

### Ver También

* clase [FontFallBackRule](../../fontfallbackrule)
* espacio de nombres [Aspose.Slides](../../fontfallbackrule)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->