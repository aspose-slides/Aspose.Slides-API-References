---
title: ReplaceRegex
second_title: Aspose.Sildes for .NET API Reference
description: Replaces all matches of regular expression with specified string.
type: docs
weight: 120
url: /aspose.slides/textframe/replaceregex/
---

## TextFrame.ReplaceRegex method

Replaces all matches of regular expression with specified string.

```csharp
public void ReplaceRegex(Regex regex, string newText, IFindResultCallback callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | The regular expression Regex to get strings to be replaced. |
| newText | String | The string to replace all occurrences of strings to be replaced. |
| callback | IFindResultCallback | Callback object for saving replacement operation result [`IFindResultCallback`](../../ifindresultcallback). |

### Examples

The following sample code shows how to replace text using regular expression with specified string.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx")){
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// Replace all words with 10 or more characters with '***'
	((AutoShape)presentation.Slides[0].Shapes[0]).TextFrame.ReplaceRegex(regex, "***", null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IFindResultCallback](../../ifindresultcallback)
* class [TextFrame](../../textframe)
* namespace [Aspose.Slides](../../textframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
