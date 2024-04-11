---
title: IVideo
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ivideo/
---


IVideo class

Represents a video embedded into a presentation.

The IVideo type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [content_type](/slides/python-net/aspose.slides/ivideo/content_type/) | Returns a MIME type of an video, encoded in [`IVideo.binary_data`](/slides/python-net/aspose.slides/ivideo#binary_data).<br/>            Read-only .NET type System.String. |
| [binary_data](/slides/python-net/aspose.slides/ivideo/binary_data/) | Returns the copy of an audio's data. In case of large amount of data consider using of <br/>            [`IVideo.get_stream`](/slides/python-net/aspose.slides/ivideo/get_stream) method to prevent unnecessary loading of video's data into memory <br/>            or even OutOfMemoryException.<br/>            Read-only .NET type System.Byte[]. |

## Methods

| Method | Description |
| :- | :- |
| [get_stream](/slides/python-net/aspose.slides/ivideo/get_stream/#) | Returns Stream stream for reading.<br/>            Use 'using' or close stream after using. |

