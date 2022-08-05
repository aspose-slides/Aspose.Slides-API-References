---
title: Audio
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an embedded audio file.
type: docs
weight: 21
url: /java/com.aspose.slides/audio/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Represents an embedded audio file.
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an audio, encoded in (\#getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Returns a MIME type of an audio, encoded in (\#getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returns a MIME type of an audio, encoded in (\#getBinaryData). Read-only String.

**Returns:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Returns a MIME type of an audio, encoded in (\#getBinaryData). Read-only String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Returns the copy of an audio's data. In case of large amount of data consider using of \#getStream method to prevent unnecessary loading of audio's data into memory or even OutOfMemoryException. Read-only byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Returns Stream stream for reading. Use 'using' or close stream after using.

**Returns:**
java.io.InputStream - Stream for reading.
