---
title: ReplaceRegex
second_title: Aspose.Slides für .NET API Referenz
description: Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch den angegebenen String.
type: docs
weight: 360
url: /de/aspose.slides/presentation/replaceregex/
---

## Presentation.ReplaceRegex Methode

Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch den angegebenen String.

```csharp
public void ReplaceRegex(Regex regex, string newText, IFindResultCallback callback)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | Der reguläre Ausdruck Regex, um die zu ersetzenden Strings zu erhalten. |
| newText | String | Der String, der alle Vorkommen der zu ersetzenden Strings ersetzt. |
| callback | IFindResultCallback | Das Callback-Objekt zum Empfang der Suchergebnisse [`IFindResultCallback`](../../ifindresultcallback). |

### Beispiele

Das folgende Codebeispiel zeigt, wie man Text mithilfe eines regulären Ausdrucks durch den angegebenen String ersetzt.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// Ersetzt alle Wörter mit 10 oder mehr Zeichen durch '***'
	presentation.ReplaceRegex(regex, "***", null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### Siehe Auch

* Schnittstelle [IFindResultCallback](../../ifindresultcallback)
* Klasse [Presentation](../../presentation)
* Namespace [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->