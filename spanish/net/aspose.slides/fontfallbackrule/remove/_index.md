---
title: Remove
second_title: Referencia de la API de Aspose.Slides para .NET
description: Elimina la primera aparición de una fuente FallBack específica de la lista.
type: docs
weight: 90
url: /es/net/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule.Remove method

Elimina la primera aparición de una fuente FallBack específica de la lista.

```csharp
public void Remove(string fontName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | El nombre de la fuente a eliminar de la lista. |

### Ejemplos

```csharp
[C#]
// Crear una regla contiene una lista de fuentes.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Eliminar Tahoma de la lista.
newRule.Remove ("Tahoma");
```

### Ver también

* class [FontFallBackRule](../../fontfallbackrule)
* espacio de nombres [Aspose.Slides](../../fontfallbackrule)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->