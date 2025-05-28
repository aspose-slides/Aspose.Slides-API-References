---
title: RemoveAt
second_title: Referencia de API de Aspose.Slides para .NET
description: Elimina la fuente FallBack en el índice especificado de la lista.
type: docs
weight: 90
url: /es/aspose.slides/ifontfallbackrule/removeat/
---

## Método IFontFallBackRule.RemoveAt

Elimina la fuente FallBack en el índice especificado de la lista.

```csharp
public void RemoveAt(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero de la fuente a eliminar. |

### Ejemplos

```csharp
[C#]
// Crear una regla que contiene una lista de fuentes.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Eliminación de Tahoma de la lista
newRule.Remove (2);
```

### Véase también

* interfaz [IFontFallBackRule](../../ifontfallbackrule)
* espacio de nombres [Aspose.Slides](../../ifontfallbackrule)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->