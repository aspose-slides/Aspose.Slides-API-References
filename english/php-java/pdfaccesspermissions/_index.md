---
title: PdfAccessPermissions
type: docs
weight: 0
url: /php-java/pdfaccesspermissions/
---

# PdfAccessPermissions class

 Contains a set of flags specifying which access permissions should be granted when the document is opened with 
 user access.
 

## Constants

| name | description |
| --- | --- |
| AddOrModifyFields | Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit PdfAccessPermissions#ModifyContent is also set, create or modify interactive form fields (including signature fields). |
| AssembleDocument | Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if bit PdfAccessPermissions#ModifyContent is clear. |
| CopyTextAndGraphics | Specifies whether a user may copy or otherwise extract text and graphics from the document by operations other than that controlled by bit PdfAccessPermissions#ExtractTextAndGraphics. |
| ExtractTextAndGraphics | Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities or for other purposes. |
| FillExistingFields | Specifies whether a user may fill in existing interactive form fields (including signature fields), even if bit PdfAccessPermissions#AddOrModifyFields is clear. |
| HighQualityPrint | Specifies whether a user may print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit PdfAccessPermissions#PrintDocument is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |
| ModifyContent | Specifies whether a user may modify the contents of the document by operations other than those controlled by bits PdfAccessPermissions#AddOrModifyFields, PdfAccessPermissions#FillExistingFields, PdfAccessPermissions#AssembleDocument. |
| None | Specifies that a user does not have access permissions. |
| PrintDocument | Specifies whether a user may print the document (possibly not at the highest quality level, depending on whether bit PdfAccessPermissions#HighQualityPrint is also set). |

