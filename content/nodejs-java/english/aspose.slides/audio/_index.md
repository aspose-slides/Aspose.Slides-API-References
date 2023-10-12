---
title: Audio
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/audio/
---

## Audio class

 Represents an embedded audio file.
 
| Name | Description |
| --- | --- |
| getBinaryData () | Returns the copy of an audio's data. In case of large amount of data consider using of #getStream function to prevent unnecessary loading of audio's data into memory or even OutOfMemoryException. Read-only byte[]. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getContentType () | Returns a MIME type of an audio, encoded in ( #getBinaryData). Read-only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getStream () | Returns Stream stream for reading. Use 'using' or close stream after using. |

### Result
InputStream


---


| Name | Description |
| --- | --- |
| setContentType (String) | Returns a MIME type of an audio, encoded in ( #getBinaryData). Read-only String. |


---


