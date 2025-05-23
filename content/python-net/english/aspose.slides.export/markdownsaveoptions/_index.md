﻿---
title: MarkdownSaveOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/markdownsaveoptions/
---


## MarkdownSaveOptions class

Represents options that control how presentation should be saved to markdown.

**Inheritance:**[`MarkdownSaveOptions`](/slides/python-net/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The MarkdownSaveOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/aspose.slides.export/markdownsaveoptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/aspose.slides.export/markdownsaveoptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See [`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/aspose.slides.export/markdownsaveoptions/gradient_style/) | Returns or sets the visual style of the gradient.<br/>            Read/write [`GradientStyle`](/slides/python-net/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. <br/>            Read/write **bool**. The default value is **false** . |
| [`export_type`](/slides/python-net/aspose.slides.export/markdownsaveoptions/export_type/) | Specifies markdown specification to convert presentation.<br/>            Default is `TextOnly`. |
| [`base_path`](/slides/python-net/aspose.slides.export/markdownsaveoptions/base_path/) | Specifies the base path where document with resources will be saved.<br/>            Default is the current directory of the application. |
| [`images_save_folder_name`](/slides/python-net/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Specifies folder name to save images.<br/>            Default is `Images`. |
| [`new_line_type`](/slides/python-net/aspose.slides.export/markdownsaveoptions/new_line_type/) | Specifies whether the generated document should have new lines \\r(Macintosh) of \\n(Unix) or \\r\\n(Windows).<br/>            Default is `Unix`. |
| [`show_comments`](/slides/python-net/aspose.slides.export/markdownsaveoptions/show_comments/) | Specifies whether the generated document should show comments or not.<br/>            Default is `false`. |
| [`show_hidden_slides`](/slides/python-net/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is `false`. |
| [`show_slide_number`](/slides/python-net/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Specifies whether the generated document should show number of each slide or not.<br/>            Default is `false`. |
| [`flavor`](/slides/python-net/aspose.slides.export/markdownsaveoptions/flavor/) | Specifies markdown specification to convert presentation.<br/>            Default is `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Gets or sets the format string used for slide number headers in Markdown output.<br/>            The format must include the "{0}" placeholder, which will be replaced with the slide index during export.<br/>            Example: "# Slide {0}" will produce "# Slide 1", "# Slide 2", etc. |
| [`handle_repeated_spaces`](/slides/python-net/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | If set to `true`, removes empty or whitespace-only lines from the final Markdown output.<br/>            Default is `false`. |


### Examples

Example:


### See Also
* class [`MarkdownSaveOptions`](/slides/python-net/aspose.slides.export/markdownsaveoptions)
* class [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

