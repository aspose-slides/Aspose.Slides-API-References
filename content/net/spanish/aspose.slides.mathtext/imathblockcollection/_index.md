---
title: IMathBlockCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Colección de bloques matemáticos IMathBlock
type: docs
weight: 7900
url: /es/aspose.slides.mathtext/imathblockcollection/
---

## Interfaz IMathBlockCollection

Colección de bloques matemáticos (IMathBlock)

```csharp
public interface IMathBlockCollection : IEnumerable<IMathBlock>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIEnumerable](../../aspose.slides.mathtext/imathblockcollection/asienumerable) { get; } | Permite obtener la interfaz base IEnumerable |
| [Count](../../aspose.slides.mathtext/imathblockcollection/count) { get; } | Obtiene el número de elementos que realmente contiene la colección. Solo lectura Int32. |
| [Item](../../aspose.slides.mathtext/imathblockcollection/item) { get; set; } | Obtiene el elemento en el índice especificado. Solo lectura [`IMathBlock`](../imathblock). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.slides.mathtext/imathblockcollection/add)(IMathBlock) | Agrega IMathBlock al final de la colección. |
| [Clear](../../aspose.slides.mathtext/imathblockcollection/clear)() | Elimina todos los elementos de la colección. |
| [Contains](../../aspose.slides.mathtext/imathblockcollection/contains)(IMathBlock) | Determina si la colección contiene un valor específico. |
| [IndexOf](../../aspose.slides.mathtext/imathblockcollection/indexof)(IMathBlock) | Determina el índice de un IMathBlock específico en la colección. |
| [Insert](../../aspose.slides.mathtext/imathblockcollection/insert)(int, IMathBlock) | Inserta IMathBlock en la colección en el índice especificado. |
| [Remove](../../aspose.slides.mathtext/imathblockcollection/remove)(IMathBlock) | Elimina la primera ocurrencia de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides.mathtext/imathblockcollection/removeat)(int) | Elimina un elemento en el índice especificado de la colección. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
```

### Véase También

* interfaz [IMathBlock](../imathblock)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->