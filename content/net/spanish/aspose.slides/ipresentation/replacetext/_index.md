---
title: ReplaceText
second_title: Referencia de API de Aspose.Slides para .NET
description: Reemplaza todas las ocurrencias del texto especificado con otro texto especificado.
type: docs
weight: 360
url: /es/aspose.slides/ipresentation/replacetext/
---

## IPresentation.ReplaceText method

Reemplaza todas las ocurrencias del texto especificado con otro texto especificado.

```csharp
public void ReplaceText(string oldText, string newText, ITextSearchOptions options, 
    IFindResultCallback callback)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldText | String | La cadena que se va a reemplazar. |
| newText | String | La cadena para reemplazar todas las ocurrencias de oldText. |
| options | ITextSearchOptions | Opciones de búsqueda de texto [`ITextSearchOptions`](../../itextsearchoptions). |
| callback | IFindResultCallback | El objeto de callback para recibir resultados de búsqueda [`IFindResultCallback`](../../ifindresultcallback). |

### Ejemplos

El siguiente código de muestra muestra cómo reemplazar una cadena especificada por otra cadena especificada.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// Reemplaza todas las ocurrencias separadas de 'the' con '***'
	presentation.ReplaceText("the", "***", new TextSearchOptions() {WholeWordsOnly = true}, null);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### Ver también

* interfaz [ITextSearchOptions](../../itextsearchoptions)
* interfaz [IFindResultCallback](../../ifindresultcallback)
* interfaz [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- NO MODIFICAR: generado por xmldocmd para Aspose.Slides.dll -->