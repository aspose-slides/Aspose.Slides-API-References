---
title: set_DetectTables()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se rilevare le tabelle durante l'importazione del file pdf.
type: docs
weight: 14
url: /it/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) metodo

Determina se rilevare le tabelle durante l'importazione del file pdf.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## Osservazioni

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
* Spazio dei nomi [Aspose::Slides::Import](../../)
* Libreria [Aspose.Slides](../../../)