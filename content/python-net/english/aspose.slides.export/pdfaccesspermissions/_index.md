---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/pdfaccesspermissions/
---


## PdfAccessPermissions enumeration

Contains a set of flags specifying which access permissions should be granted when the document is opened with 
            user access.

The PdfAccessPermissions type exposes the following members:

## Fields

| Field | Description |
| :- | :- |
| NONE | Specifies that a user does not have access permissions. |
| PRINT_DOCUMENT | Specifies whether a user may print the document (possibly not at the highest quality level, depending on <br/>            whether bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) is also set). |
| MODIFY_CONTENT | Specifies whether a user may modify the contents of the document by operations other than those controlled<br/>            by bits [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Specifies whether a user may copy or otherwise extract text and graphics from the document by operations <br/>            other than that controlled by bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit<br/>[`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) is also set, create or modify interactive form fields (including signature <br/>            fields). |
| FILL_EXISTING_FIELDS | Specifies whether a user may fill in existing interactive form fields (including signature fields), even if<br/>            bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) is clear. |
| EXTRACT_TEXT_AND_GRAPHICS | Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities<br/>            or for other purposes. |
| ASSEMBLE_DOCUMENT | Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or<br/>            thumbnail images), even if bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) is clear. |
| HIGH_QUALITY_PRINT | Specifies whether a user may print the document to a representation from which a faithful digital copy of<br/>            the PDF content could be generated. When this bit is clear (and bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) is set),<br/>            printing is limited to a low-level representation of the appearance, possibly of degraded quality. |


### See Also
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

