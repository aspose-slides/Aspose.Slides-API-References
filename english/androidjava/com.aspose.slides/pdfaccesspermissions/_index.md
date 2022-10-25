---
title: PdfAccessPermissions
second_title: Aspose.Slides for Android via Java API Reference
description: Contains a set of flags specifying which access permissions should be granted when the document is opened with  user access.
type: docs
weight: 408
url: /androidjava/com.aspose.slides/pdfaccesspermissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Contains a set of flags specifying which access permissions should be granted when the document is opened with user access.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Specifies that a user does not have access permissions. |
| [PrintDocument](#PrintDocument) | Specifies whether a user may print the document (possibly not at the highest quality level, depending on whether bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) is also set). |
| [ModifyContent](#ModifyContent) | Specifies whether a user may modify the contents of the document by operations other than those controlled by bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Specifies whether a user may copy or otherwise extract text and graphics from the document by operations other than that controlled by bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) is also set, create or modify interactive form fields (including signature fields). |
| [FillExistingFields](#FillExistingFields) | Specifies whether a user may fill in existing interactive form fields (including signature fields), even if bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) is clear. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities or for other purposes. |
| [AssembleDocument](#AssembleDocument) | Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) is clear. |
| [HighQualityPrint](#HighQualityPrint) | Specifies whether a user may print the document to a representation from which a faithful digital copy of the PDF content could be generated. |
### None {#None}
```
public static final int None
```


Specifies that a user does not have access permissions.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Specifies whether a user may print the document (possibly not at the highest quality level, depending on whether bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) is also set).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Specifies whether a user may modify the contents of the document by operations other than those controlled by bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```


Specifies whether a user may copy or otherwise extract text and graphics from the document by operations other than that controlled by bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```


Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) is also set, create or modify interactive form fields (including signature fields).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```


Specifies whether a user may fill in existing interactive form fields (including signature fields), even if bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) is clear.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```


Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities or for other purposes.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) is clear.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```


Specifies whether a user may print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality.

