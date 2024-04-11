---
title: IAudio
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iaudio/
---


IAudio class

Represents an embedded audio file.

The IAudio type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [content_type](/slides/python-net/aspose.slides/iaudio/content_type/) | Returns a MIME type of an audio, encoded in <br/>[`IAudio.binary_data`](/slides/python-net/aspose.slides/iaudio#binary_data)<br/>.<br/>            Read-only <br/>.NET type System.String<br/>. |
| [binary_data](/slides/python-net/aspose.slides/iaudio/binary_data/) | Returns the copy of an audio's data. In case of large amount of data consider <br/>            using of <br/>[`IAudio.get_stream`](/slides/python-net/aspose.slides/iaudio/get_stream)<br/> method to prevent unnecessary  loading of audio's<br/>            data into memory or even OutOfMemoryException.<br/>            Read-only <br/>.NET type System.Byte<br/>[]. |

## Methods

| Method | Description |
| :- | :- |
| [get_stream](/slides/python-net/aspose.slides/iaudio/iaudio/#/) | Returns Stream stream for reading.<br/>            Use 'using' or close stream after using. |

