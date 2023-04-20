---
title: set_AccessPermissions()
second_title: Aspose.Slides for C++ API Reference
description: Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions.
type: docs
weight: 261
url: /cpp/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) method


Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## Remarks



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## See Also

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)