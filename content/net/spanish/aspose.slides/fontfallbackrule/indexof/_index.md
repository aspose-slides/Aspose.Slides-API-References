---
title: IndexOf
second_title: Aspose.Slides para .NET Referencia de API
description: Devuelve un índice de la regla especificada en la colección.
type: docs
weight: 80
url: /es/aspose.slides/fontfallbackrule/indexof/
---

## FontFallBackRule.IndexOf método

Devuelve un índice de la regla especificada en la colección.

```csharp
public int IndexOf(string fontName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Nombre de la fuente a encontrar. |

### Valor de Retorno

Índice de una fuente o -1 si la fuente no se encuentra en la lista.

### Ejemplos

```csharp
[C#]
// Crear una regla que contiene una lista de fuentes.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Obtener índice de Tahoma.
int tahomaIndex = newRule.IndexOf("Tahoma");
```

### Ver También

* clase [FontFallBackRule](../../fontfallbackrule)
* espacio de nombres [Aspose.Slides](../../fontfallbackrule)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->