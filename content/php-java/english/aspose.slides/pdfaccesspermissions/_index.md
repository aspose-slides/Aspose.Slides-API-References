---
title: PdfAccessPermissions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/pdfaccesspermissions/
---

## PdfAccessPermissions class

 Contains a set of flags specifying which access permissions should be granted when the document is opened with 
 user access.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Specifies that a user does not have access permissions. |
| PrintDocument | 4 | Specifies whether a user may print the document (possibly not at the highest quality level, depending on whether bit PdfAccessPermissions#HighQualityPrint is also set). |
| ModifyContent | 8 | Specifies whether a user may modify the contents of the document by operations other than those controlled by bits PdfAccessPermissions#AddOrModifyFields, PdfAccessPermissions#FillExistingFields, PdfAccessPermissions#AssembleDocument. |
| CopyTextAndGraphics | 16 | Specifies whether a user may copy or otherwise extract text and graphics from the document by operations other than that controlled by bit PdfAccessPermissions#ExtractTextAndGraphics. |
| AddOrModifyFields | 32 | Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit PdfAccessPermissions#ModifyContent is also set, create or modify interactive form fields (including signature fields). |
| FillExistingFields | 256 | Specifies whether a user may fill in existing interactive form fields (including signature fields), even if bit PdfAccessPermissions#AddOrModifyFields is clear. |
| ExtractTextAndGraphics | 512 | Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities or for other purposes. |
| AssembleDocument | 1024 | Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if bit PdfAccessPermissions#ModifyContent is clear. |
| HighQualityPrint | 2048 | Specifies whether a user may print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit PdfAccessPermissions#PrintDocument is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |

