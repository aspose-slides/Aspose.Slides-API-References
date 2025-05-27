---
title: ReplaceRegex
second_title: Referencia de API de Aspose.Slides para .NET
description: Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.
type: docs
weight: 110
url: /es/aspose.slides/itextframe/replaceregex/
---

## Método ITextFrame.ReplaceRegex

Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.

```csharp
public void ReplaceRegex(Regex regex, string newText, IFindResultCallback callback)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | Regex | La expresión regular Regex para obtener cadenas a reemplazar. |
| newText | String | La cadena para reemplazar todas las ocurrencias de las cadenas a ser reemplazadas. |
| callback | IFindResultCallback | El objeto de devolución de llamada para recibir los resultados de búsqueda [`IFindResultCallback`](../../ifindresultcallback). |

### Ejemplos

El siguiente ejemplo de código muestra cómo reemplazar texto utilizando una expresión regular con la cadena especificada.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// Reemplazar todas las palabras con 10 o más caracteres por '***'
	((AutoShape)presentation.Slides[0].Shapes[0]).TextFrame.ReplaceRegex(regex, "***", null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### Véase también

* interfaz [IFindResultCallback](../../ifindresultcallback)
* interfaz [ITextFrame](../../itextframe)
* espacio de nombres [Aspose.Slides](../../itextframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->