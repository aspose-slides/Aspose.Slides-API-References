---
title: DetectTables
second_title: Référence de l'API Aspose.Slides pour .NET
description: Détermine si des tableaux doivent être détectés lors de l'importation d'un fichier pdf.
type: docs
weight: 20
url: /fr/aspose.slides.import/pdfimportoptions/detecttables/
---

## Propriété PdfImportOptions.DetectTables

Détermine si des tableaux doivent être détectés lors de l'importation d'un fichier pdf.

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
        // activer la détection des tableaux
        pres.Slides.AddFromPdf(stream, new PdfImportOptions { DetectTables = true });
    }
    
    pres.Save("fromPdfDocument.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* classe [PdfImportOptions](../../pdfimportoptions)
* espace de noms [Aspose.Slides.Import](../../pdfimportoptions)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->