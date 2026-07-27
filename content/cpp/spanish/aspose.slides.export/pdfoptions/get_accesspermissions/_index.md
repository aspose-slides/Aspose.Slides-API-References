---
title: get_AccessPermissions()
second_title: Referencia de la API de Aspose.Slides para C++
description: Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver PdfAccessPermissions.
type: docs
weight: 300
url: /es/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() método


Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Consulte [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
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
* Clase [PdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)