﻿---
title: SwfOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/swfoptions/
---


## SwfOptions class

Provides options that control how a presentation is saved in Swf format.

**Inheritance:**[`SwfOptions`](/slides/python-net/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)

The SwfOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.export/swfoptions/__init__/#) | Default constructor. |

## Properties

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/aspose.slides.export/swfoptions/warning_callback/) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [`IWarningCallback`](/slides/python-net/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/aspose.slides.export/swfoptions/progress_callback/) | Represents a callback object for saving progress updates in percentage.<br/>            See [`IProgressCallback`](/slides/python-net/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/aspose.slides.export/swfoptions/default_regular_font/) | Returns or sets font used in case source font is not found.<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/aspose.slides.export/swfoptions/gradient_style/) | Returns or sets the visual style of the gradient.<br/>            Read/write [`GradientStyle`](/slides/python-net/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/aspose.slides.export/swfoptions/skip_java_script_links/) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. <br/>            Read/write **bool**. The default value is **false** . |
| [`show_hidden_slides`](/slides/python-net/aspose.slides.export/swfoptions/show_hidden_slides/) | Specifies whether the generated document should include hidden slides or not.<br/>            Default is `false`. |
| [`compressed`](/slides/python-net/aspose.slides.export/swfoptions/compressed/) | Specifies whether the generated SWF document should be compressed or not.<br/>            Default is `true`. |
| [`viewer_included`](/slides/python-net/aspose.slides.export/swfoptions/viewer_included/) | Specifies whether the generated SWF document should include the integrated document viewer or not.<br/>            Default is `true`. |
| [`show_page_border`](/slides/python-net/aspose.slides.export/swfoptions/show_page_border/) | Specifies whether border around pages should be shown. Default is true. |
| [`show_full_screen`](/slides/python-net/aspose.slides.export/swfoptions/show_full_screen/) | Show/hide fullscreen button. Can be overridden in flashvars. Default is true. |
| [`show_page_stepper`](/slides/python-net/aspose.slides.export/swfoptions/show_page_stepper/) | Show/hide page stepper. Can be overridden in flashvars. Default is true. |
| [`show_search`](/slides/python-net/aspose.slides.export/swfoptions/show_search/) | Show/hide search section. Can be overridden in flashvars. Default is true. |
| [`show_top_pane`](/slides/python-net/aspose.slides.export/swfoptions/show_top_pane/) | Show/hide whole top pane. Can be overridden in flashvars. Default is true. |
| [`show_bottom_pane`](/slides/python-net/aspose.slides.export/swfoptions/show_bottom_pane/) | Show/hide bottom pane. Can be overridden in flashvars. Default is true. |
| [`show_left_pane`](/slides/python-net/aspose.slides.export/swfoptions/show_left_pane/) | Show/hide left pane. Can be overridden in flashvars. Default is true. |
| [`start_open_left_pane`](/slides/python-net/aspose.slides.export/swfoptions/start_open_left_pane/) | Start with opened left pane. Can be overridden in flashvars. Default is false. |
| [`enable_context_menu`](/slides/python-net/aspose.slides.export/swfoptions/enable_context_menu/) | Enable/disable context menu. Default is true. |
| [`logo_image_bytes`](/slides/python-net/aspose.slides.export/swfoptions/logo_image_bytes/) | Image that will be displayed as logo in the top right corner of the viewer.<br/>            Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly. |
| [`logo_link`](/slides/python-net/aspose.slides.export/swfoptions/logo_link/) | Gets or sets the full hyperlink address for a logo.<br/>            Has an effect only if a [`SwfOptions.logo_image_bytes`](/slides/python-net/aspose.slides.export/swfoptions/logo_image_bytes) is specified. |
| [`jpeg_quality`](/slides/python-net/aspose.slides.export/swfoptions/jpeg_quality/) | Specifies the quality of JPEG images.<br/>            Default is 95. |
| [`notes_comments_layouting`](/slides/python-net/aspose.slides.export/swfoptions/notes_comments_layouting/) | Provides options that control how notes and comments is placed in exported document. |
| [`slides_layout_options`](/slides/python-net/aspose.slides.export/swfoptions/slides_layout_options/) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](/slides/python-net/aspose.slides.export/islideslayoutoptions). <br/>            This property doesn't support assigning objects of type [`HandoutLayoutingOptions`](/slides/python-net/aspose.slides.export/handoutlayoutingoptions) |


### Examples

The following example shows how to convert PowerPoint to SWF Flash.


### See Also
* class [`SaveOptions`](/slides/python-net/aspose.slides.export/saveoptions)
* class [`SwfOptions`](/slides/python-net/aspose.slides.export/swfoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

