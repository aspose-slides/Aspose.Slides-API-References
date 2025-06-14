---
title: SkipJavaScriptLinks
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese-/Schreib-Boolean. Der Standardwert ist false.
type: docs
weight: 40
url: /de/aspose.slides.export/saveoptions/skipjavascriptlinks/
---

## SaveOptions.SkipJavaScriptLinks-Eigenschaft

Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese-/Schreib-Boolean. Der Standardwert ist **false**.

```csharp
public bool SkipJavaScriptLinks { get; set; }
```

### Anmerkungen

Wenn diese Eigenschaft auf **true** gesetzt ist, werden Hyperlinks mit JavaScript-Aufrufen beim Speichern ignoriert.

Wenn diese Eigenschaft auf **false** gesetzt ist, werden alle Hyperlinks gespeichert.

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    pres.Save("result_without_JavaScript_links.html", SaveFormat.Html, new HtmlOptions()
    {
        SkipJavaScriptLinks = true
    });
}
```

### Siehe auch

* class [SaveOptions](../../saveoptions)
* namespace [Aspose.Slides.Export](../../saveoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->