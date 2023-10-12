---
title: Video
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/video/
---

## Video class

 Represents an image embedded into a presentation.
 
### getBinaryData {#getBinaryData}

| Name | Description |
| --- | --- |
| getBinaryData () | Returns the copy of an audio's data. In case of large amount of data consider using of #getStream function to prevent unnecessary loading of video's data into memory or even OutOfMemoryException. Read-only byte[]. |

 **Result**
byte


---


### getContentType {#getContentType}

| Name | Description |
| --- | --- |
| getContentType () | Returns a MIME type of an video, encoded in ( #getBinaryData). Read-only String. |

 **Result**
String


---


### getStream {#getStream}

| Name | Description |
| --- | --- |
| getStream () | Returns Stream stream for reading. Use 'using' or close stream after using. |

 **Result**
InputStream


---


