---
title: get_AccessPermissions()
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver PdfAccessPermissions.
type: docs
weight: 261
url: /es/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() método


Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
```

## Observaciones



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Ver también

* Enumeración [PdfAccessPermissions](../../pdfaccesspermissions/)
* Clase [IPdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)