---
title: ToArray
second_title: Referencia de la API de Aspose.Sildes para .NET
description: Crea y devuelve un arreglo con todas las fuentes de retroceso para esta regla.
type: docs
weight: 110
url: /es/aspose.slides/fontfallbackrule/toarray/
---

## ToArray() {#toarray}

Crea y devuelve un arreglo con todas las fuentes de retroceso para esta regla.

```csharp
public string[] ToArray()
```

### Valor de retorno

Arreglo de String

### Ejemplos

```csharp
[C#]
// Crea una regla que contiene una lista de fuentes.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Obtiene todos los nombres de fuentes como un arreglo.
string[] fontNames = newRule.ToArray();
```

### Véase también

* clase [FontFallBackRule](../../fontfallbackrule)
* espacio de nombres [Aspose.Slides](../../fontfallbackrule)
* ensamblado [Aspose.Slides](../../../)

---

## ToArray(int, int) {#toarray_1}

Crea y devuelve un arreglo con todas las fuentes de retroceso del rango especificado en la lista.

```csharp
public string[] ToArray(int startIndex, int count)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | Int32 | Un índice de la primera fuente a agregar. |
| count | Int32 | Un número de fuentes a agregar. |

### Valor de retorno

Arreglo de String

### Ejemplos

```csharp
[C#]
// Crea una regla que contiene una lista de fuentes.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Obtiene los últimos dos nombres de fuentes como un arreglo.
string[] fontNames = newRule.ToArray(2,2);
```

### Véase también

* clase [FontFallBackRule](../../fontfallbackrule)
* espacio de nombres [Aspose.Slides](../../fontfallbackrule)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->