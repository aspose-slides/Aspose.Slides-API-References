---
title: ReplaceRegex
second_title: Referencia de la API Aspose.Sildes para .NET
description: Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.
type: docs
weight: 360
url: /es/aspose.slides/presentation/replaceregex/
---

## Método Presentation.ReplaceRegex

Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.

```csharp
public void ReplaceRegex(Regex regex, string newText, IFindResultCallback callback)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | Regex | La expresión regular Regex para obtener cadenas a reemplazar. |
| newText | String | La cadena para reemplazar todas las ocurrencias de las cadenas a ser reemplazadas. |
| callback | IFindResultCallback | El objeto de callback para recibir los resultados de búsqueda [`IFindResultCallback`](../../ifindresultcallback). |

### Ejemplos

El siguiente fragmento de código muestra cómo reemplazar texto utilizando una expresión regular con la cadena especificada.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// Reemplazar todas las palabras de 10 caracteres o más por '***'
	presentation.ReplaceRegex(regex, "***", null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IFindResultCallback](../../ifindresultcallback)
* clase [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->