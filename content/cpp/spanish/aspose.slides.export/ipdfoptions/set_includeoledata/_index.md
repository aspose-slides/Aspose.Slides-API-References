---
title: set_IncludeOleData()
second_title: Referencia de API de Aspose.Slides para C++
description: Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Escriba bool.
type: docs
weight: 469
url: /es/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) método

Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Escriba **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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