---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Represents the WebVTT closed captions.
## Methods

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Returns the globally unique identifier (GUID) of the closed captions. |
| [getLabel()](#getLabel--) | Returns or sets the label of the closed captions. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Returns or sets the label of the closed captions. |
| [getBinaryData()](#getBinaryData--) | Returns the binary data of the closed captions. |
| [getDataAsString()](#getDataAsString--) | Returns the closed captions data as UTF-8 string Read-only String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Returns the globally unique identifier (GUID) of the closed captions. Read-only java.util.UUID.

**Returns:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Returns or sets the label of the closed captions. Read/write String.

**Returns:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Returns or sets the label of the closed captions. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Returns the binary data of the closed captions. Read-only byte[].

**Returns:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Returns the closed captions data as UTF-8 string Read-only String.

**Returns:**
java.lang.String
