---
title: Video class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/video/
---


## Video class

Represents an image embedded into a presentation.

The Video type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [content_type](/slides/python-net/aspose.slides/video/content_type/) | Returns a MIME type of an video, encoded in [`Video.binary_data`](/slides/python-net/aspose.slides/video#binary_data).<br/>            Read-only .NET type System.String. |
| [binary_data](/slides/python-net/aspose.slides/video/binary_data/) | Returns the copy of an audio's data. In case of large amount of data consider using of <br/>            [`Video.get_stream`](/slides/python-net/aspose.slides/video/get_stream) method to prevent unnecessary loading of video's data into memory <br/>            or even OutOfMemoryException.<br/>            Read-only .NET type System.Byte[]. |

## Methods

| Method | Description |
| :- | :- |
| [get_stream](/slides/python-net/aspose.slides/video/get_stream/#) | Returns Stream stream for reading.<br/>            Use 'using' or close stream after using. |

