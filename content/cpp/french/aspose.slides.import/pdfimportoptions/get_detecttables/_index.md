---
title: get_DetectTables()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si les tables sont détectées lors de l'importation d'un fichier PDF.
type: docs
weight: 1
url: /fr/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const méthode

Détermine si les tables sont détectées lors de l'importation d'un fichier pdf.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Remarques

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [PdfImportOptions](../)
* Espace de noms [Aspose::Slides::Import](../../)
* Bibliothèque [Aspose.Slides](../../../)