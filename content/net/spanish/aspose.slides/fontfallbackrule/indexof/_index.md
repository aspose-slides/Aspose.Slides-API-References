---
title: IndexOf
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve un índice de la regla especificada en la colección.
type: docs
weight: 80
url: /es/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule.IndexOf method

Devuelve un índice de la regla especificada en la colección.

```csharp
public int IndexOf(string fontName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Nombre de la fuente a buscar. |

### Valor_devuelto

Índice de una fuente o -1 si la fuente no se encuentra en la lista.

### Ejemplos

```csharp
[C#]
// Crear una regla contiene una lista de fuentes.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Obtener índice de Tahoma.
int tahomaIndex = newRule.IndexOf("Tahoma");
```

### Ver también

* class [FontFallBackRule](../../fontfallbackrule)
* espacio de nombres [Aspose.Slides](../../fontfallbackrule)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
