---
title: ISlide class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/islide/
---
## คลาส ISlide

แทนสไลด์ในงานนำเสนอ

The ISlide type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/islide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            อ่านอย่างเดียว [`ISlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/th/aspose.slides/islide/slide_number/) | Returns a number of slide.<br/>            Index of slide in [`IPresentation.slides`](/slides/python-net/th/aspose.slides/ipresentation/slides) collection is always equal to SlideNumber - 1.<br/>            อ่าน/เขียน **int**. |
| [`hidden`](/slides/python-net/th/aspose.slides/islide/hidden/) | Determines whether the specified slide is hidden during a slide show.<br/>            อ่าน/เขียน **bool**. |
| [`layout_slide`](/slides/python-net/th/aspose.slides/islide/layout_slide/) | Returns or sets the layout slide for the current slide.<br/>            อ่าน/เขียน [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/th/aspose.slides/islide/notes_slide_manager/) | Allow to access notes slide, add and remove it.<br/>            อ่านอย่างเดียว [`INotesSlideManager`](/slides/python-net/th/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/th/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/th/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/th/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/th/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/th/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/th/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/th/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/th/aspose.slides/islide/theme_manager/) |  |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/islide/get_image/#float-float) | Returns an image object with custom scaling. |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/islide/get_image/#) | Returns a Thumbnail Image object (20% of real size). |
| [`get_image(self, image_size)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposepydrawingsize) | Returns an image object with specified size. |
| [`get_image(self, options)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [`get_image(self, options)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Bitmap object. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [`get_image(self, options, image_size)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returns a Thumbnail Bitmap object with specified size. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/islide/write_as_svg/#iorawiobase) | Saves the slide content as an SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves the slide content as an SVG file. |
| [`get_slide_comments(self, author)`](/slides/python-net/th/aspose.slides/islide/get_slide_comments/#icommentauthor) | Returns all slide comments added by specific author. |
| [`write_as_emf(self, stream)`](/slides/python-net/th/aspose.slides/islide/write_as_emf/#iorawiobase) | Saves the slide content as an EMF file. |
| [`remove(self)`](/slides/python-net/th/aspose.slides/islide/remove/#) | Removes slide from presentation. |
| [`reset(self)`](/slides/python-net/th/aspose.slides/islide/reset/#) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/islide/create_theme_effective/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)