---
title: IMathElementCollection
second_title: Aspose.Slides para .NET Referencia de API
description: Representa una colección de elementos matemáticos MathElement.
type: docs
weight: 7990
url: /es/aspose.slides.mathtext/imathelementcollection/
---

## Interfaz IMathElementCollection

Representa una colección de elementos matemáticos (MathElement).

```csharp
public interface IMathElementCollection : IEnumerable<IMathElement>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIEnumerable](../../aspose.slides.mathtext/imathelementcollection/asienumerable) { get; } | Devuelve la interfaz IEnumerable. Solo lectura IEnumerable. |
| [Count](../../aspose.slides.mathtext/imathelementcollection/count) { get; } | Obtiene el número de elementos que realmente se encuentran en la colección. Solo lectura Int32. |
| [Item](../../aspose.slides.mathtext/imathelementcollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`IMathElement`](../imathelement). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.slides.mathtext/imathelementcollection/add)(IMathElement) | Agrega un elemento matemático al final de la colección. |
| [Clear](../../aspose.slides.mathtext/imathelementcollection/clear)() | Elimina todos los elementos de la colección. |
| [Contains](../../aspose.slides.mathtext/imathelementcollection/contains)(IMathElement) | Determina si la colección contiene un valor específico. |
| [CopyTo](../../aspose.slides.mathtext/imathelementcollection/copyto)(IMathElement[], int) | Copia al arreglo especificado. |
| [IndexOf](../../aspose.slides.mathtext/imathelementcollection/indexof)(IMathElement) | Determina el índice de un elemento matemático específico en la colección. |
| [Insert](../../aspose.slides.mathtext/imathelementcollection/insert)(int, IMathElement) | Inserta un elemento matemático en la colección en el índice especificado. |
| [Remove](../../aspose.slides.mathtext/imathelementcollection/remove)(IMathElement) | Elimina la primera aparición de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides.mathtext/imathelementcollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElementCollection collection = new MathBlock();
```

### Véase también

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->