---
title: PdfAccessPermissions
second_title: Aspose.Slides for C++ API Reference
description: Contains a set of flags specifying which access permissions should be granted when the document is opened with user access.
type: docs
weight: 859
url: /cpp/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum


Contains a set of flags specifying which access permissions should be granted when the document is opened with user access.

```cpp
enum class PdfAccessPermissions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Specifies that a user does not have access permissions. |
| PrintDocument | 4 | Specifies whether a user may print the document (possibly not at the highest quality level, depending on whether bit [PdfAccessPermissions::HighQualityPrint](./) is also set). |
| ModifyContent | 8 | Specifies whether a user may modify the contents of the document by operations other than those controlled by bits [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Specifies whether a user may copy or otherwise extract text and graphics from the document by operations other than that controlled by bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit [PdfAccessPermissions::ModifyContent](./) is also set, create or modify interactive form fields (including signature fields). |
| FillExistingFields | 256 | Specifies whether a user may fill in existing interactive form fields (including signature fields), even if bit [PdfAccessPermissions::AddOrModifyFields](./) is clear. |
| ExtractTextAndGraphics | 512 | Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities or for other purposes. |
| AssembleDocument | 1024 | Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if bit [PdfAccessPermissions::ModifyContent](./) is clear. |
| HighQualityPrint | 2048 | Specifies whether a user may print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit [PdfAccessPermissions::PrintDocument](./) is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |

## See Also

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)