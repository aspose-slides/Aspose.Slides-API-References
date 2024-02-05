---
title: PdfAccessPermissions
second_title: Aspose.Sildes for Python via Java API Reference
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
[None](#None) | 0 | Specifies that a user does not have access permissions. |
[PrintDocument](#PrintDocument) | 4 | Specifies whether a user may print the document (possibly not at the highest quality level, depending on whether bit PdfAccessPermissions#HighQualityPrint is also set). |
[ModifyContent](#ModifyContent) | 8 | Specifies whether a user may modify the contents of the document by operations other than those controlled by bits PdfAccessPermissions#AddOrModifyFields, PdfAccessPermissions#FillExistingFields, PdfAccessPermissions#AssembleDocument. |
[CopyTextAndGraphics](#CopyTextAndGraphics) | 16 | Specifies whether a user may copy or otherwise extract text and graphics from the document by operations other than that controlled by bit PdfAccessPermissions#ExtractTextAndGraphics. |
[AddOrModifyFields](#AddOrModifyFields) | 32 | Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit PdfAccessPermissions#ModifyContent is also set, create or modify interactive form fields (including signature fields). |
[FillExistingFields](#FillExistingFields) | 256 | Specifies whether a user may fill in existing interactive form fields (including signature fields), even if bit PdfAccessPermissions#AddOrModifyFields is clear. |
[ExtractTextAndGraphics](#ExtractTextAndGraphics) | 512 | Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities or for other purposes. |
[AssembleDocument](#AssembleDocument) | 1024 | Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if bit PdfAccessPermissions#ModifyContent is clear. |
[HighQualityPrint](#HighQualityPrint) | 2048 | Specifies whether a user may print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit PdfAccessPermissions#PrintDocument is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |


---


### None {#None}
Specifies that a user does not have access permissions.

---

### PrintDocument {#PrintDocument}
Specifies whether a user may print the document (possibly not at the highest quality level, depending on whether bit PdfAccessPermissions#HighQualityPrint is also set).

---

### ModifyContent {#ModifyContent}
Specifies whether a user may modify the contents of the document by operations other than those controlled by bits PdfAccessPermissions#AddOrModifyFields, PdfAccessPermissions#FillExistingFields, PdfAccessPermissions#AssembleDocument.

---

### CopyTextAndGraphics {#CopyTextAndGraphics}
Specifies whether a user may copy or otherwise extract text and graphics from the document by operations other than that controlled by bit PdfAccessPermissions#ExtractTextAndGraphics.

---

### AddOrModifyFields {#AddOrModifyFields}
Specifies whether a user may add or modify text annotations, fill in interactive form fields, and, if bit PdfAccessPermissions#ModifyContent is also set, create or modify interactive form fields (including signature fields).

---

### FillExistingFields {#FillExistingFields}
Specifies whether a user may fill in existing interactive form fields (including signature fields), even if bit PdfAccessPermissions#AddOrModifyFields is clear.

---

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
Specifies whether a user may extract text and graphics in support of accessibility to users with disabilities or for other purposes.

---

### AssembleDocument {#AssembleDocument}
Specifies whether a user may assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if bit PdfAccessPermissions#ModifyContent is clear.

---

### HighQualityPrint {#HighQualityPrint}
Specifies whether a user may print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit PdfAccessPermissions#PrintDocument is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality.

---


### Clone {#Clone}

| Name | Description |
| --- | --- |
| Clone () |  |

 **Result:**
T


---


### CloneTo {#CloneTo}

| Name | Description |
| --- | --- |
| CloneTo (T) |  |


---


### format {#format}

| Name | Description |
| --- | --- |
| format (java.lang.Class<?>, long, String) |  |

 **Result:**
String


---


### format {#format}

| Name | Description |
| --- | --- |
| format (Type, Object, String) |  |

 **Result:**
String


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName (java.lang.Class<?>, long) |  |

 **Result:**
String


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName (Type, Object) |  |

 **Result:**
String


---


### getNames {#getNames}

| Name | Description |
| --- | --- |
| getNames (java.lang.Class<?>) |  |

 **Result:**
List, ArrayList


---


### getNames {#getNames}

| Name | Description |
| --- | --- |
| getNames (Type) |  |

 **Result:**
String


---


### getUnderlyingType {#getUnderlyingType}

| Name | Description |
| --- | --- |
| getUnderlyingType (java.lang.Class<?>) |  |

 **Result:**
Class


---


### getUnderlyingType {#getUnderlyingType}

| Name | Description |
| --- | --- |
| getUnderlyingType (Type) |  |

 **Result:**
Type


---


### getValue {#getValue}

| Name | Description |
| --- | --- |
| getValue (java.lang.Class<?>, String) |  |

 **Result:**
long


---


### getValues {#getValues}

| Name | Description |
| --- | --- |
| getValues (Type) |  |

 **Result:**
Array


---


### get_Caption {#get_Caption}

| Name | Description |
| --- | --- |
| get_Caption () |  |

 **Result:**
String


---


### get_Value {#get_Value}

| Name | Description |
| --- | --- |
| get_Value () |  |

 **Result:**
long


---


### isDefined {#isDefined}

| Name | Description |
| --- | --- |
| isDefined (java.lang.Class<?>, long) |  |

 **Result:**
boolean


---


### isDefined {#isDefined}

| Name | Description |
| --- | --- |
| isDefined (Type, long) |  |

 **Result:**
boolean


---


### isDefined {#isDefined}

| Name | Description |
| --- | --- |
| isDefined (Type, String) |  |

 **Result:**
boolean


---


### isDefined {#isDefined}

| Name | Description |
| --- | --- |
| isDefined (Type, Object) |  |

 **Result:**
boolean


---


### parse {#parse}

| Name | Description |
| --- | --- |
| parse (java.lang.Class<?>, String) |  |

 **Result:**
long


---


### parse {#parse}

| Name | Description |
| --- | --- |
| parse (java.lang.Class<?>, String, Boolean) |  |

 **Result:**
long


---


### parse {#parse}

| Name | Description |
| --- | --- |
| parse (Type, String) |  |

 **Result:**
long


---


### parse {#parse}

| Name | Description |
| --- | --- |
| parse (Type, String, Boolean) |  |

 **Result:**
long


---


### register {#register}

| Name | Description |
| --- | --- |
| register (Enum.AbstractEnum) |  |


---


### toObject {#toObject}

| Name | Description |
| --- | --- |
| toObject (Type, Object) |  |

 **Result:**
Object


---


### toString {#toString}

| Name | Description |
| --- | --- |
| toString (java.lang.Class<?>, long) |  |

 **Result:**
String


---


