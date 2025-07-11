---
title: HighlightRegex
second_title: Aspose.Slides für .NET API Referenz
description: Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.
type: docs
weight: 320
url: /de/aspose.slides/ipresentation/highlightregex/
---

## IPresentation.HighlightRegex-Methode

Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.

```csharp
public void HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | Der reguläre Ausdruck Regex, um die zu hebenden Zeichenfolgen zu erhalten. |
| highlightColor | Color | Die Farbe, um den Text hervorzuheben. |
| callback | IFindResultCallback | Das Callback-Objekt zum Empfangen der Suchergebnisse [`IFindResultCallback`](../../ifindresultcallback). |

### Beispiele

Das folgende Codebeispiel zeigt, wie man Text in einer PowerPoint-Präsentation mit einem regulären Ausdruck hervorhebt.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// Hebt alle Wörter mit 10 oder mehr Zeichen hervor
	presentation.HighlightRegex(regex, Color.Blue, null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### Siehe Auch

* Schnittstelle [IFindResultCallback](../../ifindresultcallback)
* Schnittstelle [IPresentation](../../ipresentation)
* Namespace [Aspose.Slides](../../ipresentation)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->