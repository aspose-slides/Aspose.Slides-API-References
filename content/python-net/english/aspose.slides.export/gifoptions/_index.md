﻿---
title: GifOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/gifoptions/
---


## GifOptions class

Represents GIF exporting options.

**Inheritance:**[`GifOptions`](/slides/python-net/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The GifOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.export/gifoptions/__init__/#) | Initializes a new instance of the GifOptions class. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/aspose.slides.export/gifoptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/aspose.slides.export/gifoptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See [`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/gifoptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/aspose.slides.export/gifoptions/gradient_style/) | Returns or sets the visual style of the gradient.<br/>            Read/write [`GradientStyle`](/slides/python-net/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/aspose.slides.export/gifoptions/skip_java_script_links/) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. <br/>            Read/write **bool**. The default value is **false** . |
| [`frame_size`](/slides/python-net/aspose.slides.export/gifoptions/frame_size/) | Gets or sets frame size. |
| [`export_hidden_slides`](/slides/python-net/aspose.slides.export/gifoptions/export_hidden_slides/) | Determines whether hidden slides will be exported.<br/>            The default value is false. |
| [`transition_fps`](/slides/python-net/aspose.slides.export/gifoptions/transition_fps/) | Gets or sets transition FPS [frames/sec]<br/>            The default value is 25. |
| [`default_delay`](/slides/python-net/aspose.slides.export/gifoptions/default_delay/) | Gets or sets default delay time [ms]. This value will be used if [`ISlideShowTransition.advance_after_time`](/slides/python-net/aspose.slides/islideshowtransition/advance_after_time) is not set.<br/>            The default value is 1000. |


### Examples

The following example shows how to converting presentations to animated GIF using custom settings.


### See Also
* class [`GifOptions`](/slides/python-net/aspose.slides.export/gifoptions)
* class [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

