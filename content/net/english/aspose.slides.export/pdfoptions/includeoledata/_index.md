---
title: IncludeOleData
second_title: Aspose.Sildes for .NET API Reference
description: True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read/write Boolean.
type: docs
weight: 110
url: /aspose.slides.export/pdfoptions/includeoledata/
---

## PdfOptions.IncludeOleData property

True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read/write Boolean.

```csharp
public bool IncludeOleData { get; set; }
```

### Remarks

Default is **false**.

### Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    PdfOptions options = new PdfOptions { IncludeOleData = true };
    pres.Save("pres.pdf", SaveFormat.Pdf, options);
}
```

### See Also

* class [PdfOptions](../../pdfoptions)
* namespace [Aspose.Slides.Export](../../pdfoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
