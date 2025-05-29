---
title: ReplaceRegex
second_title: Referencia de API de Aspose.Slides para .NET
description: Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.
type: docs
weight: 120
url: /es/aspose.slides/textframe/replaceregex/
---

## Método TextFrame.ReplaceRegex

Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.

```csharp
public void ReplaceRegex(Regex regex, string newText, IFindResultCallback callback)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | Regex | La expresión regular Regex para obtener cadenas a ser reemplazadas. |
| newText | String | La cadena para reemplazar todas las ocurrencias de las cadenas a ser reemplazadas. |
| callback | IFindResultCallback | Objeto de callback para guardar el resultado de la operación de reemplazo [`IFindResultCallback`](../../ifindresultcallback). |

### Ejemplos

El siguiente código de muestra muestra cómo reemplazar texto utilizando una expresión regular con la cadena especificada.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx")){
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// Reemplazar todas las palabras con 10 o más caracteres con '***'
	((AutoShape)presentation.Slides[0].Shapes[0]).TextFrame.ReplaceRegex(regex, "***", null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### Véase también

* interfaz [IFindResultCallback](../../ifindresultcallback)
* clase [TextFrame](../../textframe)
* espacio de nombres [Aspose.Slides](../../textframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->