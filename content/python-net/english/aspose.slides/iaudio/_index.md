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
| [content_type](/slides/python-net/aspose.slides/iaudio/content_type/) | Returns a MIME type of an audio, encoded in [`IAudio.binary_data`](/slides/python-net/aspose.slides/iaudio#binary_data).<br/>            Read-only .NET type System.String. |
| [binary_data](/slides/python-net/aspose.slides/iaudio/binary_data/) | Returns the copy of an audio's data. In case of large amount of data consider <br/>            using of [`IAudio.get_stream`](/slides/python-net/aspose.slides/iaudio/get_stream) method to prevent unnecessary  loading of audio's<br/>            data into memory or even OutOfMemoryException.<br/>            Read-only .NET type System.Byte[]. |

## Methods

| Method | Description |
| :- | :- |
| [get_stream](/slides/python-net/aspose.slides/iaudio/get_stream/#/) | Returns Stream stream for reading.<br/>            Use 'using' or close stream after using. |

