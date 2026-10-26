---
title: get_IncludeOleData()
second_title: Referencia de la API de Aspose.Slides para C++
description: Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Leer bool.
type: docs
weight: 456
url: /es/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() método

True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Leer **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

* Clase [IPdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)