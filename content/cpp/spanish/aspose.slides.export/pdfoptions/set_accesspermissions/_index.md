---
title: set_AccessPermissions()
second_title: Referencia de la API de Aspose.Slides para C++
description: Contiene un conjunto de banderas que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver PdfAccessPermissions.
type: docs
weight: 313
url: /es/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) método

Contiene un conjunto de banderas que especifican qué permisos de acceso deben otorgarse cuando el documento se abre con acceso de usuario. Ver [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
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