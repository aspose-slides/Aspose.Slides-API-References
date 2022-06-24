---
title: Video
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/video/
---

## Video class

 Represents an image embedded into a presentation.
 

## Methods

| Name | Description |
| --- | --- |
| [getBinaryData](getbinarydata)() | Returns the copy of an audio's data. In case of large amount of data consider using of #getStream method to prevent unnecessary loading of video's data into memory or even OutOfMemoryException. Read-only byte[]. |
| [getContentType](getcontenttype)() | Returns a MIME type of an video, encoded in ( #getBinaryData). Read-only String. |
| [getStream](getstream)() | Returns Stream stream for reading. Use 'using' or close stream after using. |
