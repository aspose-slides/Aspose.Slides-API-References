---
title: get_DetectTables()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si se detectan tablas al importar un archivo pdf.
type: docs
weight: 1
url: /es/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const método


Determina si se detectan tablas al importar un archivo pdf.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [PdfImportOptions](../)
* Espacio de nombres [Aspose::Slides::Import](../../)
* Biblioteca [Aspose.Slides](../../../)