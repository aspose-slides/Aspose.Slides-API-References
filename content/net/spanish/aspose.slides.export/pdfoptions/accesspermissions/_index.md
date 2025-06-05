---
title: AccessPermissions
second_title: Aspose.Slides para .NET Referencia de API
description: Contiene un conjunto de flags que especifican qué permisos de acceso deben ser otorgados cuando el documento se abre con acceso de usuario. Ver PdfAccessPermissionsaspose.slides.export/pdfaccesspermissions.
type: docs
weight: 20
url: /es/aspose.slides.export/pdfoptions/accesspermissions/
---

## PdfOptions.AccessPermissions propiedad

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

### Ver También

* enum [PdfAccessPermissions](../../pdfaccesspermissions)
* class [PdfOptions](../../pdfoptions)
* namespace [Aspose.Slides.Export](../../pdfoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITES: generado por xmldocmd para Aspose.Slides.dll -->