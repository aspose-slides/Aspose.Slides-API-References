---
title: Slide class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/slide/
---
## Slide класс

Represents a slide in a presentation.

**Inheritance:**[`Slide`](/slides/python-net/ru/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)

The Slide type exposes the following members:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/slide/shapes/) | Returns the shapes of a slide.<br/>            Read-only [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/slide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/slide/name/) | Returns or sets the name of a slide.<br/>            Read/write **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/slide/slide_id/) | Returns the ID of a slide.<br/>            Read-only **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/slide/custom_data/) | Returns the slide's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/slide/timeline/) | Returns animation timeline object.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/slide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/slide/background/) | Returns slide's background.<br/>            Read-only [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/slide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/slide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Read/write **bool**. |
| [`presentation`](/slides/python-net/ru/aspose.slides/slide/presentation/) | Returns IPresentation interface.<br/>            Read-only [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/slide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            Read-only [`ISlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/slide/theme_manager/) | Returns the overriding theme manager.<br/>            Read-only [`IOverrideThemeManager`](/slides/python-net/ru/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/ru/aspose.slides/slide/slide_number/) | Returns a number of slide.<br/>            Index of slide in [`Presentation.slides`](/slides/python-net/ru/aspose.slides/presentation/slides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber.<br/>            Read/write **int**. |
| [`hidden`](/slides/python-net/ru/aspose.slides/slide/hidden/) | Determines whether the specified slide is hidden during a slide show.<br/>            Read/write **bool**. |
| [`layout_slide`](/slides/python-net/ru/aspose.slides/slide/layout_slide/) | Returns or sets the layout slide for the current slide.<br/>            Read/write [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ru/aspose.slides/slide/notes_slide_manager/) | Allow to access notes slide, add and remove it.<br/>            Read-only [`INotesSlideManager`](/slides/python-net/ru/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/ru/aspose.slides/slide/slide/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/slide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ru/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/slide/get_image/#float-float) | Returns a Thumbnail Image object with custom scaling. |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/slide/get_image/#) | Returns a Thumbnail Image object (20% of real size). |
| [`get_image(self, image_size)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidessize) | Returns a Thumbnail Image object with specified size. |
| [`get_image(self, options)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Returns a Thumbnail tiff image object with specified parameters. |
| [`get_image(self, options)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Image object. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Image object with custom scaling. |
| [`get_image(self, options, image_size)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Returns a Thumbnail Image object with specified size. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/slide/write_as_svg/#iorawiobase) | Saves the slide content as an SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves the slide content as an SVG file. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/slide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/slide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/slide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`write_as_emf(self, stream)`](/slides/python-net/ru/aspose.slides/slide/write_as_emf/#iorawiobase) | Saves the slide content as an EMF file. |
| [`remove(self)`](/slides/python-net/ru/aspose.slides/slide/remove/#) | Removes slide from presentation. |
| [`reset(self)`](/slides/python-net/ru/aspose.slides/slide/reset/#) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/ru/aspose.slides/slide/get_slide_comments/#icommentauthor) | Returns all slide comments added by specific author. |


### См. также
* класс [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)
* класс [`Slide`](/slides/python-net/ru/aspose.slides/slide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)