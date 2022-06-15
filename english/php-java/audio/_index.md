---
title: Audio
type: docs
weight: 0
url: /php-java/audio/
---

# Audio class

 Represents an embedded audio file.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBinaryData](/slides/php-java/audio/getbinarydata/)() | byte | Returns the copy of an audio's data. In case of large amount of data consider using of #getStream method to prevent unnecessary loading of audio's data into memory or even OutOfMemoryException. Read-only byte[]. |
| [getContentType](/slides/php-java/audio/getcontenttype/)() | String | Returns a MIME type of an audio, encoded in ( #getBinaryData). Read-only String. |
| [getStream](/slides/php-java/audio/getstream/)() | InputStream | Returns Stream stream for reading. Use 'using' or close stream after using. |
| [setContentType](/slides/php-java/audio/setcontenttype/)(String) | void | Returns a MIME type of an audio, encoded in ( #getBinaryData). Read-only String. |
