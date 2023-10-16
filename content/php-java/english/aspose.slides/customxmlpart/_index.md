---
title: CustomXmlPart
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/customxmlpart/
---

## CustomXmlPart class

 Represents custom xml part.
 
### getItemId {#getItemId}

| Name | Description |
| --- | --- |
| getItemId () | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. Read-only java.util.UUID. |

 **Returns:**
UUID


---


### getNamespaceSchemas {#getNamespaceSchemas}

| Name | Description |
| --- | --- |
| getNamespaceSchemas () | Returns the collection XML schemas that are associated with the custom XML part. Read-only String[]. |

 **Returns:**
String


---


### getXmlAsString {#getXmlAsString}

| Name | Description |
| --- | --- |
| getXmlAsString () | Returns or sets xml data as UTF-8 string. Read/write String. |

 **Returns:**
String

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | value is empty or xml-data is invalid. |


---


### getXmlData {#getXmlData}

| Name | Description |
| --- | --- |
| getXmlData () | Returns or sets xml data. Read/write byte[]. |

 **Returns:**
byte

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | value is empty or xml-data is invalid. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Removes the custom xml part from the presentation. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if xml part is already removed. |


---


### setItemId {#setItemId}

| Name | Description |
| --- | --- |
| setItemId (UUID) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. Read-only java.util.UUID. |

 **Returns:**
void


---


### setXmlAsString {#setXmlAsString}

| Name | Description |
| --- | --- |
| setXmlAsString (String) | Returns or sets xml data as UTF-8 string. Read/write String. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | value is empty or xml-data is invalid. |


---


### setXmlData {#setXmlData}

| Name | Description |
| --- | --- |
| setXmlData (byte[]) | Returns or sets xml data. Read/write byte[]. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | value is empty or xml-data is invalid. |


---


