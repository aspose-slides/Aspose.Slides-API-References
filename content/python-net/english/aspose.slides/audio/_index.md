---
title: Audio
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/audio/
---


Audio class

Represents an embedded audio file.

The Audio type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [content_type](/slides/python-net/aspose.slides/audio/content_type/) | Returns a MIME type of an audio, encoded in :py:attr:`aspose.slides.Audio.binary_data`.<br/>            Read-only :py:class:`System.String`. |
| [binary_data](/slides/python-net/aspose.slides/audio/binary_data/) | Returns the copy of an audio's data. In case of large amount of data consider <br/>            using of :py:func:`aspose.slides.Audio.get_stream` method to prevent unnecessary  loading of audio's<br/>            data into memory or even OutOfMemoryException.<br/>            Read-only :py:class:`int`[]. |

## Methods

| Method | Description |
| :- | :- |
| [get_stream](/slides/python-net/aspose.slides/audio/audio/#/) | Returns Stream stream for reading.<br/>            Use 'using' or close stream after using. |

