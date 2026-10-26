---
title: get_DetectTables()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se rilevare le tabelle durante l'importazione di un file pdf.
type: docs
weight: 1
url: /it/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const method


Determina se rilevare le tabelle durante l'importazione del file pdf.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Note


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [PdfImportOptions](../)
* Namespace [Aspose::Slides::Import](../../)
* Libreria [Aspose.Slides](../../../)