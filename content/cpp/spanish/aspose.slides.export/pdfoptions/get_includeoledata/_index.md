---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ Referencia de API
description: True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura bool.
type: docs
weight: 456
url: /es/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() método


True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Observaciones


El valor predeterminado es **false**. 

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Ver también

* Clase [PdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)