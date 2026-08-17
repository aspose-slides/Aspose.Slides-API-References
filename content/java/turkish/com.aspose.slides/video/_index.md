---
title: Video
second_title: Aspose.Slides for Java API Referansı
description: Bir sunuma gömülü resmi temsil eder.
type: docs
url: /tr/com.aspose.slides/video/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Bir sunuma gömülü resmi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an video, encoded in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returns a MIME type of an video, encoded in (\#getBinaryData.getBinaryData). Salt-okunur String.

**Döndürür:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Returns the copy of an audio's data. In case of large amount of data consider using of \#getStream.getStream method to prevent unnecessary loading of video's data into memory or even OutOfMemoryException. Salt-okunur byte[].

**Döndürür:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Returns Stream stream for reading. Use 'using' or close stream after using.

**Döndürür:**
java.io.InputStream - Stream for reading.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject