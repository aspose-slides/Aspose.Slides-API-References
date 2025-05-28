---
title: AccessPermissions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Contiene un conjunto de flags que especifican qué permisos de acceso deben ser otorgados cuando el documento se abre con acceso de usuario. Ver PdfAccessPermissionsaspose.slides.export/pdfaccesspermissions.
type: docs
weight: 10
url: /es/aspose.slides.export/ipdfoptions/accesspermissions/
---

## Propiedad IPdfOptions.AccessPermissions

Contiene un conjunto de flags que especifican qué permisos de acceso deben ser otorgados cuando el documento se abre con acceso de usuario. Ver [`PdfAccessPermissions`](../../pdfaccesspermissions).

```csharp
public PdfAccessPermissions AccessPermissions { get; set; }
```

### Ejemplos

```csharp
[C#]
var pdfOptions = new PdfOptions();
pdfOptions.Password = "my_password";
pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;

using (var presentation = new Presentation())
{
    presentation.Save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
}
```

### También Vea

* enum [PdfAccessPermissions](../../pdfaccesspermissions)
* interface [IPdfOptions](../../ipdfoptions)
* namespace [Aspose.Slides.Export](../../ipdfoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->