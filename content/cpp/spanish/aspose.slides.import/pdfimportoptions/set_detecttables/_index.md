---
title: set_DetectTables()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si se detectan tablas al importar un archivo pdf.
type: docs
weight: 14
url: /es/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) método


Determina si se detectan tablas al importar un archivo pdf.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
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