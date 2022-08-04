---
title: IVideo
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a video embedded into a presentation.
type: docs
weight: 1096
url: /java/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Represents a video embedded into a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an video, encoded in (\#getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Returns a MIME type of an video, encoded in (\#getBinaryData). Read-only String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Returns the copy of an audio's data. In case of large amount of data consider using of \#getStream method to prevent unnecessary loading of video's data into memory or even OutOfMemoryException. Read-only byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Returns Stream stream for reading. Use 'using' or close stream after using.

**Returns:**
java.io.InputStream - Stream for reading.
