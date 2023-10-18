---
title: Audio
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/audio/
---

## Audio class

 Represents an embedded audio file.
 
### getBinaryData {#getBinaryData}

| Name | Description |
| --- | --- |
| getBinaryData () | Returns the copy of an audio's data. In case of large amount of data consider using of #getStream method to prevent unnecessary loading of audio's data into memory or even OutOfMemoryException. Read-only byte[]. |

 **Returns:**
byte


---


### getContentType {#getContentType}

| Name | Description |
| --- | --- |
| getContentType () | Returns a MIME type of an audio, encoded in ( #getBinaryData). Read-only String. |

 **Returns:**
String


---


### getStream {#getStream}

| Name | Description |
| --- | --- |
| getStream () | Returns Stream stream for reading. Use 'using' or close stream after using. |

 **Returns:**
InputStream


---


### setContentType {#setContentType}

| Name | Description |
| --- | --- |
| setContentType (String) | Returns a MIME type of an audio, encoded in ( #getBinaryData). Read-only String. |

 **Returns:**
void


---


