---
title: ISlide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islide/
---


## ISlide class

Represents a slide in a presentation.

The ISlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/aspose.slides/islide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            Read-only [`ISlideHeaderFooterManager`](/slides/python-net/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/aspose.slides/islide/slide_number/) | Returns a number of slide.<br/>            Index of slide in [`IPresentation.slides`](/slides/python-net/aspose.slides/ipresentation/slides) collection is always equal to SlideNumber - 1.<br/>            Read/write **int**. |
| [`hidden`](/slides/python-net/aspose.slides/islide/hidden/) | Determines whether the specified slide is hidden during a slide show.<br/>            Read/write **bool**. |
| [`layout_slide`](/slides/python-net/aspose.slides/islide/layout_slide/) | Returns or sets the layout slide for the current slide.<br/>            Read/write [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/aspose.slides/islide/notes_slide_manager/) | Allow to access notes slide, add and remove it.<br/>            Read-only [`INotesSlideManager`](/slides/python-net/aspose.slides/inotesslidemanager). |

## Methods

| Method | Description |
| :- | :- |
| [`get_thumbnail`](/slides/python-net/aspose.slides/islide/get_thumbnail/#float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [`get_thumbnail`](/slides/python-net/aspose.slides/islide/get_thumbnail/#) | Returns a Thumbnail Image object (20% of real size). |
| [`get_thumbnail`](/slides/python-net/aspose.slides/islide/get_thumbnail/#asposepydrawingsize) | Returns a Thumbnail Bitmap object with specified size. |
| [`get_thumbnail`](/slides/python-net/aspose.slides/islide/get_thumbnail/#asposeslidesexportitiffoptions) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [`get_thumbnail`](/slides/python-net/aspose.slides/islide/get_thumbnail/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Bitmap object. |
| [`get_thumbnail`](/slides/python-net/aspose.slides/islide/get_thumbnail/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [`get_thumbnail`](/slides/python-net/aspose.slides/islide/get_thumbnail/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returns a Thumbnail Bitmap object with specified size. |
| [`get_image`](/slides/python-net/aspose.slides/islide/get_image/#float-float) | Returns an image object with custom scaling. |
| [`get_image`](/slides/python-net/aspose.slides/islide/get_image/#) | Returns a Thumbnail Image object (20% of real size). |
| [`get_image`](/slides/python-net/aspose.slides/islide/get_image/#asposepydrawingsize) | Returns an image object with specified size. |
| [`get_image`](/slides/python-net/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [`get_image`](/slides/python-net/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Bitmap object. |
| [`get_image`](/slides/python-net/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [`get_image`](/slides/python-net/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returns a Thumbnail Bitmap object with specified size. |
| [`render_to_graphics`](/slides/python-net/aspose.slides/islide/render_to_graphics/#asposeslidesexportirenderingoptions-asposepydrawinggraphics) | Renders certain slide to a Graphics object. |
| [`render_to_graphics`](/slides/python-net/aspose.slides/islide/render_to_graphics/#asposeslidesexportirenderingoptions-asposepydrawinggraphics-float-float) | Renders certain slide to a Graphics object with custom scaling. |
| [`render_to_graphics`](/slides/python-net/aspose.slides/islide/render_to_graphics/#asposeslidesexportirenderingoptions-asposepydrawinggraphics-asposepydrawingsize) | Renders certain slide to a Graphics object using specified size. |
| [`write_as_svg`](/slides/python-net/aspose.slides/islide/write_as_svg/#iorawiobase) | Saves the slide content as an SVG file. |
| [`write_as_svg`](/slides/python-net/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves the slide content as an SVG file. |
| [`get_slide_comments`](/slides/python-net/aspose.slides/islide/get_slide_comments/#asposeslidesicommentauthor) | Returns all slide comments added by specific author. |
| [`write_as_emf`](/slides/python-net/aspose.slides/islide/write_as_emf/#iorawiobase) | Saves the slide content as an EMF file. |
| [`remove`](/slides/python-net/aspose.slides/islide/remove/#) | Removes slide from presentation. |
| [`reset`](/slides/python-net/aspose.slides/islide/reset/#) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

