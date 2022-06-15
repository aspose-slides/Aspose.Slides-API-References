---
title: Video
type: docs
weight: 0
url: /php-java/video/
---

# Video class

 Represents an image embedded into a presentation.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBinaryData](/php-java/video/getbinarydata/)() | byte | Returns the copy of an audio's data. In case of large amount of data consider using of #getStream method to prevent unnecessary loading of video's data into memory or even OutOfMemoryException. Read-only byte[]. |
| [getContentType](/php-java/video/getcontenttype/)() | String | Returns a MIME type of an video, encoded in ( #getBinaryData). Read-only String. |
| [getStream](/php-java/video/getstream/)() | InputStream | Returns Stream stream for reading. Use 'using' or close stream after using. |
