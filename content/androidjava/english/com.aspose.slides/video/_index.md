---
title: Video
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an image embedded into a presentation.
type: docs
weight: 606
url: /com.aspose.slides/video/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Represents an image embedded into a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an video, encoded in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returns a MIME type of an video, encoded in (\#getBinaryData.getBinaryData). Read-only String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Returns the copy of an audio's data. In case of large amount of data consider using of \#getStream.getStream method to prevent unnecessary loading of video's data into memory or even OutOfMemoryException. Read-only byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Returns Stream stream for reading. Use 'using' or close stream after using.

**Returns:**
java.io.InputStream - Stream for reading.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
