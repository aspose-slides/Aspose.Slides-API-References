---
title: ReplaceText
second_title: Aspose.Sildes for .NET API Reference
description: Replaces all occurrences of the specified text with another specified text.
type: docs
weight: 120
url: /aspose.slides/itextframe/replacetext/
---

## ITextFrame.ReplaceText method

Replaces all occurrences of the specified text with another specified text.

```csharp
public void ReplaceText(string oldText, string newText, ITextSearchOptions options, 
    IFindResultCallback callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| oldText | String | The string to be replaced. |
| newText | String | The string to replace all occurrences of oldText. |
| options | ITextSearchOptions | Text search options [`ITextSearchOptions`](../../itextsearchoptions). |
| callback | IFindResultCallback | The callback object for receiving search results [`IFindResultCallback`](../../ifindresultcallback). |

### Examples

The following sample code shows how to replace one specified string with another specified string.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// Replace all separate 'the' occurrences with '***'
	((AutoShape)presentation.Slides[0].Shapes[0]).TextFrame.ReplaceText("the", "***", new TextSearchOptions()
	{ WholeWordsOnly = true }, null);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [ITextSearchOptions](../../itextsearchoptions)
* interface [IFindResultCallback](../../ifindresultcallback)
* interface [ITextFrame](../../itextframe)
* namespace [Aspose.Slides](../../itextframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
