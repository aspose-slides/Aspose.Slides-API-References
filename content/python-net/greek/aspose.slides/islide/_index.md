---
title: ISlide class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/islide/
---
## ISlide κλάση

Αναπαριστά μια διαφάνεια σε μια παρουσίαση.

Ο τύπος ISlide εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/el/aspose.slides/islide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            Μόνο ανάγνωση [`ISlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/el/aspose.slides/islide/slide_number/) | Returns a number of slide.<br/>            Index of slide in [`IPresentation.slides`](/slides/python-net/el/aspose.slides/ipresentation/slides) collection is always equal to SlideNumber - 1.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`hidden`](/slides/python-net/el/aspose.slides/islide/hidden/) | Determines whether the specified slide is hidden during a slide show.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`layout_slide`](/slides/python-net/el/aspose.slides/islide/layout_slide/) | Returns or sets the layout slide for the current slide.<br/>            Ανάγνωση/εγγραφή [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/el/aspose.slides/islide/notes_slide_manager/) | Allow to access notes slide, add and remove it.<br/>            Μόνο ανάγνωση [`INotesSlideManager`](/slides/python-net/el/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/el/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/el/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/el/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/el/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/el/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/el/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/el/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/el/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/el/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/el/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/el/aspose.slides/islide/theme_manager/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/islide/get_image/#float-float) | Returns an image object with custom scaling. |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/islide/get_image/#) | Returns a Thumbnail Image object (20% of real size). |
| [`get_image(self, image_size)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidessize) | Returns an image object with specified size. |
| [`get_image(self, options)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [`get_image(self, options)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Bitmap object. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [`get_image(self, options, image_size)`](/slides/python-net/el/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Returns a Thumbnail Bitmap object with specified size. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/islide/write_as_svg/#iorawiobase) | Saves the slide content as an SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves the slide content as an SVG file. |
| [`get_slide_comments(self, author)`](/slides/python-net/el/aspose.slides/islide/get_slide_comments/#icommentauthor) | Returns all slide comments added by specific author. |
| [`write_as_emf(self, stream)`](/slides/python-net/el/aspose.slides/islide/write_as_emf/#iorawiobase) | Saves the slide content as an EMF file. |
| [`remove(self)`](/slides/python-net/el/aspose.slides/islide/remove/#) | Removes slide from presentation. |
| [`reset(self)`](/slides/python-net/el/aspose.slides/islide/reset/#) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/el/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/el/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/el/aspose.slides/islide/create_theme_effective/#) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)