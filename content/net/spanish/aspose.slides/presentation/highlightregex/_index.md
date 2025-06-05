---
title: HighlightRegex
second_title: Referencia de la API de Aspose.Slides para .NET
description: Destaca todas las coincidencias de la expresión regular con el color especificado.
type: docs
weight: 330
url: /es/aspose.slides/presentation/highlightregex/
---

## Método Presentation.HighlightRegex

Destaca todas las coincidencias de la expresión regular con el color especificado.

```csharp
public void HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | Regex | La expresión regular Regex para obtener cadenas a resaltar. |
| highlightColor | Color | El color para resaltar el texto. |
| callback | IFindResultCallback | El objeto de callback para recibir resultados de búsqueda [`IFindResultCallback`](../../ifindresultcallback). |

### Ejemplos

El siguiente fragmento de código muestra cómo resaltar texto en una presentación de PowerPoint utilizando una expresión regular.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// resaltando todas las palabras con 10 caracteres o más
	presentation.HighlightRegex(regex, Color.Blue, null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### Vea También

* interfaz [IFindResultCallback](../../ifindresultcallback)
* clase [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->