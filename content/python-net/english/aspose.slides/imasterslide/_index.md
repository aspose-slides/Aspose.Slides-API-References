---
title: IMasterSlide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## IMasterSlide class

Represents a master slide in a presentation.

The IMasterSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [header_footer_manager](/slides/python-net/aspose.slides/header_footer_manager) | Returns HeaderFooter manager of the master slide.<br/>            Read-only :py:class:`aspose.slides.IMasterSlideHeaderFooterManager`. |
| [title_style](/slides/python-net/aspose.slides/title_style) | Returns the style of a title text.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [body_style](/slides/python-net/aspose.slides/body_style) | Returns the style of a body text.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [other_style](/slides/python-net/aspose.slides/other_style) | Returns the style of an other text.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [layout_slides](/slides/python-net/aspose.slides/layout_slides) | Returns the collection of child layout slides for this master slide.<br/>            Read-only :py:class:`aspose.slides.IMasterLayoutSlideCollection`. |
| [preserve](/slides/python-net/aspose.slides/preserve) | Determines whether the corresponding master is deleted when all <br/>            the slides that follow that master are deleted.<br/>            Note: Aspose.Slides will never remove any unused master by itself, <br/>            to actually remove unused masters call :py:func:`Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste.`<br/>            Read/write :py:class:`bool`. |
| [has_depending_slides](/slides/python-net/aspose.slides/has_depending_slides) | Returns true if there exists at least one slide that depends on this master slide.<br/>            Read-only :py:class:`bool`. |
| [as_i_base_slide](/slides/python-net/aspose.slides/as_i_base_slide) | Allows to get base IBaseSlide interface.<br/>            Read-only :py:class:`aspose.slides.IBaseSlide`. |
| [as_i_master_themeable](/slides/python-net/aspose.slides/as_i_master_themeable) | Returns IMasterThemeable interface.<br/>            Read-only :py:class:`aspose.slides.theme.IMasterThemeable`. |
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
| [__init__](/slides/python-net/aspose.slides/imasterslide/#string) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [__init__](/slides/python-net/aspose.slides/imasterslide/#) | Returns an array with all slides, which depend on this master slide. |
| [__init__](/slides/python-net/aspose.slides/imasterslide/#string) |  |
| [__init__](/slides/python-net/aspose.slides/imasterslide/#) |  |
| [__init__](/slides/python-net/aspose.slides/imasterslide/#IBaseSlide) |  |
| [__init__](/slides/python-net/aspose.slides/imasterslide/#) |  |

