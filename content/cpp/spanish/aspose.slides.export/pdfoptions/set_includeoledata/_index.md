---
title: set_IncludeOleData()
second_title: Referencia API de Aspose.Slides para C++
description: True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Escriba bool.
type: docs
weight: 469
url: /es/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) método

True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Escriba **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
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