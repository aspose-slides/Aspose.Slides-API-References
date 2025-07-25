---
title: DetectTables
second_title: Référence de l'API Aspose.Slides pour .NET
description: Détermine si des tables doivent être détectées lors de l'importation d'un fichier pdf.
type: docs
weight: 20
url: /fr/aspose.slides.import/pdfimportoptions/detecttables/
---

## PdfImportOptions.DetectTables propriété

Détermine si des tables doivent être détectées lors de l'importation d'un fichier pdf.

```csharp
public bool DetectTables { get; set; }
```

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    using (Stream stream = new FileStream("document.pdf", FileMode.Open, FileAccess.Read, FileShare.Read))
    {
        // définir la détection des tables
        pres.Slides.AddFromPdf(stream, new PdfImportOptions { DetectTables = true });
    }
    
    pres.Save("fromPdfDocument.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* class [PdfImportOptions](../../pdfimportoptions)
* namespace [Aspose.Slides.Import](../../pdfimportoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->