---
title: CustomXmlPart
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/customxmlpart/
---

## CustomXmlPart class

 Represents custom xml part.
 
| Name | Description |
| --- | --- |
| getItemId () | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. Read-only java.util.UUID. |

### Result
UUID


---


| Name | Description |
| --- | --- |
| getNamespaceSchemas () | Returns the collection XML schemas that are associated with the custom XML part. Read-only String[]. |

### Result
String


---


| Name | Description |
| --- | --- |
| getXmlAsString () | Returns or sets xml data as UTF-8 string. Read/write String. |

### Result
String

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | value is empty or xml-data is invalid. |


---


| Name | Description |
| --- | --- |
| getXmlData () | Returns or sets xml data. Read/write byte[]. |

### Result
byte

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | value is empty or xml-data is invalid. |


---


| Name | Description |
| --- | --- |
| remove () | Removes the custom xml part from the presentation. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if xml part is already removed. |


---


| Name | Description |
| --- | --- |
| setItemId (UUID) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. Read-only java.util.UUID. |


---


| Name | Description |
| --- | --- |
| setXmlAsString (String) | Returns or sets xml data as UTF-8 string. Read/write String. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | value is empty or xml-data is invalid. |


---


| Name | Description |
| --- | --- |
| setXmlData (byte[]) | Returns or sets xml data. Read/write byte[]. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | value is empty or xml-data is invalid. |


---


