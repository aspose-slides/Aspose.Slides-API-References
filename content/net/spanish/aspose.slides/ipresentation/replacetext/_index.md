---
title: ReplaceText
second_title: Referencia de API de Aspose.Slides para .NET
description: Reemplaza todas las ocurrencias del texto especificado por otro texto especificado.
type: docs
weight: 360
url: /es/aspose.slides/ipresentation/replacetext/
---

## Método IPresentation.ReplaceText

Reemplaza todas las ocurrencias del texto especificado por otro texto especificado.

```csharp
public void ReplaceText(string oldText, string newText, ITextSearchOptions options, 
    IFindResultCallback callback)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldText | String | La cadena que se va a reemplazar. |
| newText | String | La cadena para reemplazar todas las ocurrencias de oldText. |
| options | ITextSearchOptions | Opciones de búsqueda de texto [`ITextSearchOptions`](../../itextsearchoptions). |
| callback | IFindResultCallback | El objeto de devolución de llamada para recibir resultados de búsqueda [`IFindResultCallback`](../../ifindresultcallback). |

### Ejemplos

El siguiente código de ejemplo muestra cómo reemplazar una cadena especificada por otra cadena especificada.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// Reemplazar todas las ocurrencias separadas de 'the' por '***'
	presentation.ReplaceText("the", "***", new TextSearchOptions() {WholeWordsOnly = true}, null);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interface [ITextSearchOptions](../../itextsearchoptions)
* interface [IFindResultCallback](../../ifindresultcallback)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->