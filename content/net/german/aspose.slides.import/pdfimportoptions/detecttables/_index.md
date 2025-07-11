---
title: DetectTables
second_title: Aspose.Slides für .NET API-Referenz
description: Bestimmt, ob beim Importieren einer PDF-Datei Tabellen erkannt werden.
type: docs
weight: 20
url: /de/aspose.slides.import/pdfimportoptions/detecttables/
---

## PdfImportOptions.DetectTables-Eigenschaft

Bestimmt, ob beim Importieren einer PDF-Datei Tabellen erkannt werden.

```csharp
public bool DetectTables { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    using (Stream stream = new FileStream("document.pdf", FileMode.Open, FileAccess.Read, FileShare.Read))
    {
        // Setze die Erkennung von Tabellen
        pres.Slides.AddFromPdf(stream, new PdfImportOptions { DetectTables = true });
    }
    
    pres.Save("fromPdfDocument.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* class [PdfImportOptions](../../pdfimportoptions)
* namespace [Aspose.Slides.Import](../../pdfimportoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->