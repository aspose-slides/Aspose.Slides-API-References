---
title: set_DetectTables()
second_title: Referência da API Aspose.Slides para C++
description: Determina se detecta tabelas ao importar um arquivo PDF.
type: docs
weight: 14
url: /pt/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) método

Determina se detecta tabelas ao importar um arquivo PDF.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [PdfImportOptions](../)
* Namespace [Aspose::Slides::Import](../../)
* Biblioteca [Aspose.Slides](../../../)