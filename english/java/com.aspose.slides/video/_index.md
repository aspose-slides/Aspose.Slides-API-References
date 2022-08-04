---
title: Video
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an image embedded into a presentation.
type: docs
weight: 602
url: /java/com.aspose.slides/video/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Represents an image embedded into a presentation.
## Constructors

| Constructor | Description |
| --- | --- |
| [Video(VideoCollection parentImmediate, IBlobHandler blobHandler, String contentType, String extension)](#Video-com.aspose.slides.VideoCollection-com.aspose.foundation.blob.IBlobHandler-java.lang.String-java.lang.String-) |  |
| [Video(VideoCollection parentImmediate, IBlobHandler blobHandler)](#Video-com.aspose.slides.VideoCollection-com.aspose.foundation.blob.IBlobHandler-) | Creates video with unitialized content type and extension, these properties will be lazy initialized |
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an video, encoded in (\#getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Video(VideoCollection parentImmediate, IBlobHandler blobHandler, String contentType, String extension) {#Video-com.aspose.slides.VideoCollection-com.aspose.foundation.blob.IBlobHandler-java.lang.String-java.lang.String-}
```
 Video(VideoCollection parentImmediate, IBlobHandler blobHandler, String contentType, String extension)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [VideoCollection](../../com.aspose.slides/videocollection) |  |
| blobHandler | com.aspose.foundation.blob.IBlobHandler |  |
| contentType | java.lang.String |  |
| extension | java.lang.String |  |

### Video(VideoCollection parentImmediate, IBlobHandler blobHandler) {#Video-com.aspose.slides.VideoCollection-com.aspose.foundation.blob.IBlobHandler-}
```
 Video(VideoCollection parentImmediate, IBlobHandler blobHandler)
```


Creates video with unitialized content type and extension, these properties will be lazy initialized

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [VideoCollection](../../com.aspose.slides/videocollection) |  |
| blobHandler | com.aspose.foundation.blob.IBlobHandler |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returns a MIME type of an video, encoded in (\#getBinaryData). Read-only String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Returns the copy of an audio's data. In case of large amount of data consider using of \#getStream method to prevent unnecessary loading of video's data into memory or even OutOfMemoryException. Read-only byte[].

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
