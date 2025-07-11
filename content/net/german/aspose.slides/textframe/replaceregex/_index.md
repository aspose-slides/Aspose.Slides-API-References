---
title: ReplaceRegex
second_title: Aspose.Sildes für .NET API Referenz
description: Ersetzt alle Übereinstimmungen des regulären Ausdrucks mit dem angegebenen String.
type: docs
weight: 120
url: /de/aspose.slides/textframe/replaceregex/
---

## TextFrame.ReplaceRegex-Methode

Ersetzt alle Übereinstimmungen des regulären Ausdrucks mit dem angegebenen String.

```csharp
public void ReplaceRegex(Regex regex, string newText, IFindResultCallback callback)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | Der reguläre Ausdruck Regex, um Strings zu erhalten, die ersetzt werden sollen. |
| newText | String | Der String, um alle Vorkommen der zu ersetzenden Strings zu ersetzen. |
| callback | IFindResultCallback | Callback-Objekt zum Speichern des Ergebnisses der Ersetzungsoperation [`IFindResultCallback`](../../ifindresultcallback). |

### Beispiele

Der folgende Beispielcode zeigt, wie man Text mit einem regulären Ausdruck durch den angegebenen String ersetzen kann.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx")){
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// Ersetze alle Wörter mit 10 oder mehr Zeichen durch '***'
	((AutoShape)presentation.Slides[0].Shapes[0]).TextFrame.ReplaceRegex(regex, "***", null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Interface [IFindResultCallback](../../ifindresultcallback)
* Klasse [TextFrame](../../textframe)
* Namespace [Aspose.Slides](../../textframe)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->