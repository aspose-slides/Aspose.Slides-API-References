---
title: ISlide
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islide/
---


ISlide class

Represents a slide in a presentation.

The ISlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [header_footer_manager](/slides/python-net/aspose.slides/islide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            Read-only [`ISlideHeaderFooterManager`](/slides/python-net/aspose.slides/islideheaderfootermanager). |
| [slide_number](/slides/python-net/aspose.slides/islide/slide_number/) | Returns a number of slide.<br/>            Index of slide in [`IPresentation.slides`](/slides/python-net/aspose.slides/ipresentation#slides) collection is always equal to SlideNumber - 1.<br/>            Read/write .NET type System.Int32. |
| [hidden](/slides/python-net/aspose.slides/islide/hidden/) | Determines whether the specified slide is hidden during a slide show.<br/>            Read/write .NET type System.Boolean. |
| [layout_slide](/slides/python-net/aspose.slides/islide/layout_slide/) | Returns or sets the layout slide for the current slide.<br/>            Read/write [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide). |
| [notes_slide_manager](/slides/python-net/aspose.slides/islide/notes_slide_manager/) | Allow to access notes slide, add and remove it.<br/>            Read-only [`INotesSlideManager`](/slides/python-net/aspose.slides/inotesslidemanager). |
| [as_i_base_slide](/slides/python-net/aspose.slides/islide/as_i_base_slide/) | Allows to get base IBaseSlide interface.<br/>            Read-only [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide). |
| [as_i_override_themeable](/slides/python-net/aspose.slides/islide/as_i_override_themeable/) | Returns IOverrideThemeable interface.<br/>            Read-only [`IOverrideThemeable`](/slides/python-net/aspose.slides.theme/ioverridethemeable). |
| [shapes](/slides/python-net/aspose.slides/islide/shapes/) |  |
| [controls](/slides/python-net/aspose.slides/islide/controls/) |  |
| [name](/slides/python-net/aspose.slides/islide/name/) |  |
| [slide_id](/slides/python-net/aspose.slides/islide/slide_id/) |  |
| [custom_data](/slides/python-net/aspose.slides/islide/custom_data/) |  |
| [timeline](/slides/python-net/aspose.slides/islide/timeline/) |  |
| [slide_show_transition](/slides/python-net/aspose.slides/islide/slide_show_transition/) |  |
| [background](/slides/python-net/aspose.slides/islide/background/) |  |
| [hyperlink_queries](/slides/python-net/aspose.slides/islide/hyperlink_queries/) |  |
| [show_master_shapes](/slides/python-net/aspose.slides/islide/show_master_shapes/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/islide/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides/islide/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/islide/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides/islide/presentation/) |  |
| [theme_manager](/slides/python-net/aspose.slides/islide/theme_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#float-float/) | Returns a Thumbnail Bitmap object with custom scaling. |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#/) | Returns a Thumbnail Image object (20% of real size). |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#aspose.pydrawing.Size/) | Returns a Thumbnail Bitmap object with specified size. |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.ITiffOptions/) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.INotesCommentsLayoutingOptions/) | Returns a Thumbnail Bitmap object. |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-float-float/) | Returns a Thumbnail Bitmap object with custom scaling. |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Size/) | Returns a Thumbnail Bitmap object with specified size. |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.IRenderingOptions/) | Returns a Thumbnail Bitmap object. |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.IRenderingOptions-float-float/) | Returns a Thumbnail Bitmap object with custom scaling. |
| [get_thumbnail](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Size/) | Returns a Thumbnail Bitmap object with specified size. |
| [render_to_graphics](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics-int-int/) | Renders certain slide to a Graphics object. |
| [render_to_graphics](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics-float/) | Renders certain slide to a Graphics object. |
| [render_to_graphics](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics/) | Renders certain slide to a Graphics object. |
| [render_to_graphics](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics/) | Renders certain slide to a Graphics object. |
| [render_to_graphics](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics-float-float/) | Renders certain slide to a Graphics object with custom scaling. |
| [render_to_graphics](/slides/python-net/aspose.slides/islide/islide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics-aspose.pydrawing.Size/) | Renders certain slide to a Graphics object using specified size. |
| [write_as_svg](/slides/python-net/aspose.slides/islide/islide/#System.IO.Stream/) | Saves content of slide as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/islide/islide/#System.IO.Stream-aspose.slides.export.ISVGOptions/) | Saves content of slide as SVG file. |
| [get_slide_comments](/slides/python-net/aspose.slides/islide/islide/#ICommentAuthor/) | Returns all slide comments added by specific author. |
| [remove](/slides/python-net/aspose.slides/islide/islide/#/) | Removes slide from presentation. |
| [reset](/slides/python-net/aspose.slides/islide/islide/#/) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [find_shape_by_alt_text](/slides/python-net/aspose.slides/islide/islide/#string/) |  |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/islide/islide/#/) |  |
| [equals](/slides/python-net/aspose.slides/islide/islide/#IBaseSlide/) |  |
| [create_theme_effective](/slides/python-net/aspose.slides/islide/islide/#/) |  |

