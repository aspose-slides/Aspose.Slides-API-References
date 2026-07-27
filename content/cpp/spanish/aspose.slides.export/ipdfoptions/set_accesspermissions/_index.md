---
title: set_AccessPermissions()
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Véase PdfAccessPermissions.
type: docs
weight: 274
url: /es/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) método


Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Vea [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)