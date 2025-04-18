﻿---
title: RenderingOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/renderingoptions/
---


## RenderingOptions class

Provides options that control how a presentation/slide is rendered.

**Inheritance:**[`RenderingOptions`](/slides/python-net/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The RenderingOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.export/renderingoptions/__init__/#) | Default constructor. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/aspose.slides.export/renderingoptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/aspose.slides.export/renderingoptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See [`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/renderingoptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/aspose.slides.export/renderingoptions/gradient_style/) | Returns or sets the visual style of the gradient.<br/>            Read/write [`GradientStyle`](/slides/python-net/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/aspose.slides.export/renderingoptions/skip_java_script_links/) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. <br/>            Read/write **bool**. The default value is **false** . |
| [`slides_layout_options`](/slides/python-net/aspose.slides.export/renderingoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/aspose.slides.export/renderingoptions/ink_options/) | Provides options that control the look of Ink objects in exported document.<br/>            Read-only [`IInkOptions`](/slides/python-net/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Gets or sets a value indicating whether text is rendered without using ligatures.<br/>            When set to `true`, ligatures will be disabled in the rendered output. By default, this property is set to `false`. |


### See Also
* class [`RenderingOptions`](/slides/python-net/aspose.slides.export/renderingoptions)
* class [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

