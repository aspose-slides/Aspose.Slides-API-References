---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/
---


## PdfAccessPermissions enumeration

Contains a set of flags specifying which access permissions should be granted when the document is opened with 
            user access.

The PdfAccessPermissions type exposes the following members:

## Fields

| Field | Description |
| :- | :- |
| NONE | Specifies that a user does not have access permissions. |
| PRINT_DOCUMENT | Specifies whether a user may print the document (possibly not at the highest quality level, depending on <br/>            whether bit :py:attr:`aspose.slides.export.PdfAccessPermissions.HIGH_QUALITY_PRINT` is also set). |
| MODIFY_CONTENT | Specifies whether a user may modify the contents of the document by operations other than those controlled<br/>            by bits :py:attr:`aspose.slides.export.PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`, :py:attr:`aspose.slides.export.PdfAccessPermissions.FILL_EXISTING_FIELDS`, :py:attr:`aspose.slides.export.PdfAccessPermissions.ASSEMBLE_DOCUMENT`. |
| COPY_TEXT_AND_GRAPHICS | Specifies whether a user may copy or otherwise extract text and graphics from the document by operations <br/>            other than that controlled by bit :py:attr:`aspose.slides.export.PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`. |
| ADD_OR_MODIFY_FIELDS | Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit<br/>            :py:attr:`aspose.slides.export.PdfAccessPermissions.MODIFY_CONTENT` is also set, create or modify interactive form fields (including signature <br/>            fields). |
| FILL_EXISTING_FIELDS | Specifies whether a user may fill in existing interactive form fields (including signature fields), even if<br/>            bit :py:attr:`aspose.slides.export.PdfAccessPermissions.ADD_OR_MODIFY_FIELDS` is clear. |
| EXTRACT_TEXT_AND_GRAPHICS | Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities<br/>            or for other purposes. |
| ASSEMBLE_DOCUMENT | Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or<br/>            thumbnail images), even if bit :py:attr:`aspose.slides.export.PdfAccessPermissions.MODIFY_CONTENT` is clear. |
| HIGH_QUALITY_PRINT | Specifies whether a user may print the document to a representation from which a faithful digital copy of<br/>            the PDF content could be generated. When this bit is clear (and bit :py:attr:`aspose.slides.export.PdfAccessPermissions.PRINT_DOCUMENT` is set),<br/>            printing is limited to a low-level representation of the appearance, possibly of degraded quality. |

