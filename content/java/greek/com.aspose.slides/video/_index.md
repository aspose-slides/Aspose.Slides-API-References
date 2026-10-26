---
title: Video
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει μια εικόνα ενσωματωμένη σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/video/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Αντιπροσωπεύει μια εικόνα ενσωματωμένη σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an video, encoded in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returns a MIME type of an video, encoded in (\#getBinaryData.getBinaryData). **Μόνο για ανάγνωση** String.

**Επιστρέφει:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Returns the copy of an audio's data. In case of large amount of data consider using of \#getStream.getStream method to prevent unnecessary loading of video's data into memory or even OutOfMemoryException. **Μόνο για ανάγνωση** byte[].

**Επιστρέφει:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Returns Stream stream for reading. Use 'using' or close stream after using.

**Επιστρέφει:**
java.io.InputStream - Stream for reading.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent_Immediate object. **Μόνο για ανάγνωση** IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject