---
title: ISlide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## ISlide class

Represents a slide in a presentation.

The ISlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [header_footer_manager](/slides/python-net/aspose.slides/header_footer_manager) | Returns HeaderFooter manager of the slide.<br/>            Read-only :py:class:`aspose.slides.ISlideHeaderFooterManager`. |
| [slide_number](/slides/python-net/aspose.slides/slide_number) | Returns a number of slide.<br/>            Index of slide in :py:attr:`aspose.slides.IPresentation.slides` collection is always equal to SlideNumber - 1.<br/>            Read/write :py:class:`int`. |
| [hidden](/slides/python-net/aspose.slides/hidden) | Determines whether the specified slide is hidden during a slide show.<br/>            Read/write :py:class:`bool`. |
| [layout_slide](/slides/python-net/aspose.slides/layout_slide) | Returns or sets the layout slide for the current slide.<br/>            Read/write :py:class:`aspose.slides.ILayoutSlide`. |
| [notes_slide_manager](/slides/python-net/aspose.slides/notes_slide_manager) | Allow to access notes slide, add and remove it.<br/>            Read-only :py:class:`aspose.slides.INotesSlideManager`. |
| [as_i_base_slide](/slides/python-net/aspose.slides/as_i_base_slide) | Allows to get base IBaseSlide interface.<br/>            Read-only :py:class:`aspose.slides.IBaseSlide`. |
| [as_i_override_themeable](/slides/python-net/aspose.slides/as_i_override_themeable) | Returns IOverrideThemeable interface.<br/>            Read-only :py:class:`aspose.slides.theme.IOverrideThemeable`. |
| [shapes](/slides/python-net/aspose.slides/shapes) |  |
| [controls](/slides/python-net/aspose.slides/controls) |  |
| [name](/slides/python-net/aspose.slides/name) |  |
| [slide_id](/slides/python-net/aspose.slides/slide_id) |  |
| [custom_data](/slides/python-net/aspose.slides/custom_data) |  |
| [timeline](/slides/python-net/aspose.slides/timeline) |  |
| [slide_show_transition](/slides/python-net/aspose.slides/slide_show_transition) |  |
| [background](/slides/python-net/aspose.slides/background) |  |
| [hyperlink_queries](/slides/python-net/aspose.slides/hyperlink_queries) |  |
| [show_master_shapes](/slides/python-net/aspose.slides/show_master_shapes) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/as_i_slide_component) |  |
| [slide](/slides/python-net/aspose.slides/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/as_i_presentation_component) |  |
| [presentation](/slides/python-net/aspose.slides/presentation) |  |
| [theme_manager](/slides/python-net/aspose.slides/theme_manager) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/islide/#float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/islide/#) | Returns a Thumbnail Image object (20% of real size). |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.pydrawing.Size) | Returns a Thumbnail Bitmap object with specified size. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.ITiffOptions) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.INotesCommentsLayoutingOptions) | Returns a Thumbnail Bitmap object. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap object with specified size. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.IRenderingOptions) | Returns a Thumbnail Bitmap object. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.IRenderingOptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap object with specified size. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics-int-int) | Renders certain slide to a Graphics object. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics-float) | Renders certain slide to a Graphics object. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics) | Renders certain slide to a Graphics object. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics) | Renders certain slide to a Graphics object. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics-float-float) | Renders certain slide to a Graphics object with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/islide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics-aspose.pydrawing.Size) | Renders certain slide to a Graphics object using specified size. |
| [__init__](/slides/python-net/aspose.slides/islide/#System.IO.Stream) | Saves content of slide as SVG file. |
| [__init__](/slides/python-net/aspose.slides/islide/#System.IO.Stream-aspose.slides.export.ISVGOptions) | Saves content of slide as SVG file. |
| [__init__](/slides/python-net/aspose.slides/islide/#ICommentAuthor) | Returns all slide comments added by specific author. |
| [__init__](/slides/python-net/aspose.slides/islide/#) | Removes slide from presentation. |
| [__init__](/slides/python-net/aspose.slides/islide/#) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [__init__](/slides/python-net/aspose.slides/islide/#string) |  |
| [__init__](/slides/python-net/aspose.slides/islide/#) |  |
| [__init__](/slides/python-net/aspose.slides/islide/#IBaseSlide) |  |
| [__init__](/slides/python-net/aspose.slides/islide/#) |  |

