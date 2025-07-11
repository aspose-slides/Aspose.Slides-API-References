---
title: HighlightRegex
second_title: Referencia de API de Aspose.Slides para .NET
description: Resalta todas las coincidencias de la expresión regular con el color especificado.
type: docs
weight: 80
url: /es/aspose.slides/itextframe/highlightregex/
---

## Método ITextFrame.HighlightRegex

Resalta todas las coincidencias de la expresión regular con el color especificado.

```csharp
public void HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | Regex | La expresión regular Regex para obtener cadenas para resaltar. |
| highlightColor | Color | El color para resaltar el texto. |
| callback | IFindResultCallback | El objeto de callback para recibir los resultados de búsqueda [`IFindResultCallback`](../../ifindresultcallback). |

### Ejemplos

El siguiente fragmento de código muestra cómo resaltar texto en un TextFrame utilizando una expresión regular.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// resaltando todas las palabras con 10 o más caracteres
	((AutoShape)presentation.Slides[0].Shapes[0]).TextFrame.HighlightRegex(regex, Color.Blue, null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IFindResultCallback](../../ifindresultcallback)
* interfaz [ITextFrame](../../itextframe)
* espacio de nombres [Aspose.Slides](../../itextframe)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->