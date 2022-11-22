---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Represents custom xml part.
type: docs
weight: 738
url: /androidjava/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Represents custom xml part.
## Methods

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Returns or sets xml data as UTF-8 string. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Returns or sets xml data as UTF-8 string. |
| [getXmlData()](#getXmlData--) | Returns or sets xml data. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Returns or sets xml data. |
| [getItemId()](#getItemId--) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Returns the collection XML schemas that are associated with the custom XML part. |
| [remove()](#remove--) | Removes the custom xml part from the presentation. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```


Returns or sets xml data as UTF-8 string. Read/write String.

**Returns:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```


Returns or sets xml data as UTF-8 string. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```


Returns or sets xml data. Read/write byte[].

**Returns:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```


Returns or sets xml data. Read/write byte[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```


Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. Read-only java.util.UUID.

**Returns:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```


Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. Read-only java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```


Returns the collection XML schemas that are associated with the custom XML part. Read-only String[].

**Returns:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```


Removes the custom xml part from the presentation.

