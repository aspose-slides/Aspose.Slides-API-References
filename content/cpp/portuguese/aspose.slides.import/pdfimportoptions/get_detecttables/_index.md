---
title: get_DetectTables()
second_title: Referência da API Aspose.Slides para C++
description: Determina se detecta tabelas ao importar um arquivo pdf.
type: docs
weight: 1
url: /pt/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const método


Determina se detecta tabelas ao importar um arquivo pdf.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
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

## Ver Também

* Classe [PdfImportOptions](../)
* Espaço de nomes [Aspose::Slides::Import](../../)
* Biblioteca [Aspose.Slides](../../../)