---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Java API Reference
description:  Represents embedded data info for OLE object.
type: docs
weight: 385
url: /java/com.aspose.slides/oleembeddeddatainfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Represents embedded data info for OLE object.
## Constructors

| Constructor | Description |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Creates new embedded data info for OLE object. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Creates a new instance of an embedded data info for OLE object. |
## Methods

| Method | Description |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Returns the file data of an embedded OLE object Read only byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Returns the file extension for the current embedded OLE object Read only String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


Creates new embedded data info for OLE object.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


Creates a new instance of an embedded data info for OLE object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| embeddedFileData | byte[] | File data of an embedded OLE object byte[]. |
| embeddedFileExtension | java.lang.String | File extension for the current embedded OLE object String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


Returns the file data of an embedded OLE object Read only byte[].

**Returns:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


Returns the file extension for the current embedded OLE object Read only String.

**Returns:**
java.lang.String
