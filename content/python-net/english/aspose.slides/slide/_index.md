---
title: Slide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slide/
---


## Slide class

Represents a slide in a presentation.

**Inheritance:**[`Slide`](/slides/python-net/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/aspose.slides/baseslide)

The Slide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shapes](/slides/python-net/aspose.slides/slide/shapes/) | Returns the shapes of a slide.<br/>            Read-only [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection). |
| [controls](/slides/python-net/aspose.slides/slide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only [`IControlCollection`](/slides/python-net/aspose.slides/icontrolcollection). |
| [name](/slides/python-net/aspose.slides/slide/name/) | Returns or sets the name of a slide.<br/>            Read/write .NET type System.String. |
| [slide_id](/slides/python-net/aspose.slides/slide/slide_id/) | Returns the ID of a slide.<br/>            Read-only .NET type System.UInt32. |
| [custom_data](/slides/python-net/aspose.slides/slide/custom_data/) | Returns the slide's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [timeline](/slides/python-net/aspose.slides/slide/timeline/) | Returns animation timeline object.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/aspose.slides/ianimationtimeline). |
| [slide_show_transition](/slides/python-net/aspose.slides/slide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/aspose.slides/islideshowtransition). |
| [background](/slides/python-net/aspose.slides/slide/background/) | Returns slide's background.<br/>            Read-only [`IBackground`](/slides/python-net/aspose.slides/ibackground). |
| [hyperlink_queries](/slides/python-net/aspose.slides/slide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/aspose.slides/ihyperlinkqueries). |
| [show_master_shapes](/slides/python-net/aspose.slides/slide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Read/write .NET type System.Boolean. |
| [presentation](/slides/python-net/aspose.slides/slide/presentation/) | Returns IPresentation interface.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [header_footer_manager](/slides/python-net/aspose.slides/slide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            Read-only [`ISlideHeaderFooterManager`](/slides/python-net/aspose.slides/islideheaderfootermanager). |
| [theme_manager](/slides/python-net/aspose.slides/slide/theme_manager/) | Returns the overriding theme manager.<br/>            Read-only [`IOverrideThemeManager`](/slides/python-net/aspose.slides.theme/ioverridethememanager). |
| [slide_number](/slides/python-net/aspose.slides/slide/slide_number/) | Returns a number of slide.<br/>            Index of slide in [`Presentation.slides`](/slides/python-net/aspose.slides/presentation#slides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber.<br/>            Read/write .NET type System.Int32. |
| [hidden](/slides/python-net/aspose.slides/slide/hidden/) | Determines whether the specified slide is hidden during a slide show.<br/>            Read/write .NET type System.Boolean. |
| [layout_slide](/slides/python-net/aspose.slides/slide/layout_slide/) | Returns or sets the layout slide for the current slide.<br/>            Read/write [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide). |
| [notes_slide_manager](/slides/python-net/aspose.slides/slide/notes_slide_manager/) | Allow to access notes slide, add and remove it.<br/>            Read-only [`INotesSlideManager`](/slides/python-net/aspose.slides/inotesslidemanager). |
| [as_i_slide_component](/slides/python-net/aspose.slides/slide/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides/slide/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/slide/as_i_presentation_component/) |  |
| [as_i_base_slide](/slides/python-net/aspose.slides/slide/as_i_base_slide/) |  |
| [as_i_override_themeable](/slides/python-net/aspose.slides/slide/as_i_override_themeable/) |  |

## Methods

| Method | Description |
| :- | :- |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/slide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#) | Returns a Thumbnail Image object (20% of real size). |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#asposepydrawingsize) | Returns a Thumbnail Bitmap object with specified size. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#asposeslidesexportitiffoptions) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#asposeslidesexportinotescommentslayoutingoptions) | Returns a Thumbnail Bitmap object. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#asposeslidesexportinotescommentslayoutingoptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#asposeslidesexportinotescommentslayoutingoptions-asposepydrawingsize) | Returns a Thumbnail Bitmap object with specified size. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Bitmap object. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [get_thumbnail](/slides/python-net/aspose.slides/slide/get_thumbnail/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Returns a Thumbnail Bitmap object with specified size. |
| [render_to_graphics](/slides/python-net/aspose.slides/slide/render_to_graphics/#asposeslidesexportinotescommentslayoutingoptions-asposepydrawinggraphics-int-int) | Renders certain slide to a Graphics object using specified size. |
| [render_to_graphics](/slides/python-net/aspose.slides/slide/render_to_graphics/#asposeslidesexportinotescommentslayoutingoptions-asposepydrawinggraphics-float) | Renders certain slide to a Graphics object using specified scale. |
| [render_to_graphics](/slides/python-net/aspose.slides/slide/render_to_graphics/#asposeslidesexportinotescommentslayoutingoptions-asposepydrawinggraphics) | Renders certain slide to a Graphics object. |
| [render_to_graphics](/slides/python-net/aspose.slides/slide/render_to_graphics/#asposeslidesexportirenderingoptions-asposepydrawinggraphics) | Renders certain slide to a Graphics object. |
| [render_to_graphics](/slides/python-net/aspose.slides/slide/render_to_graphics/#asposeslidesexportirenderingoptions-asposepydrawinggraphics-float-float) | Renders certain slide to a Graphics object with custom scaling. |
| [render_to_graphics](/slides/python-net/aspose.slides/slide/render_to_graphics/#asposeslidesexportirenderingoptions-asposepydrawinggraphics-asposepydrawingsize) | Renders certain slide to a Graphics object using specified size. |
| [write_as_svg](/slides/python-net/aspose.slides/slide/write_as_svg/#systemiostream) | Saves content of slide as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/slide/write_as_svg/#systemiostream-asposeslidesexportisvgoptions) | Saves content of slide as SVG file. |
| [equals](/slides/python-net/aspose.slides/slide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [create_theme_effective](/slides/python-net/aspose.slides/slide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [find_shape_by_alt_text](/slides/python-net/aspose.slides/slide/find_shape_by_alt_text/#string) | Finds first occurrence of a shape with the specified alternative text. |
| [remove](/slides/python-net/aspose.slides/slide/remove/#) | Removes slide from presentation. |
| [reset](/slides/python-net/aspose.slides/slide/reset/#) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [get_slide_comments](/slides/python-net/aspose.slides/slide/get_slide_comments/#icommentauthor) | Returns all slide comments added by specific author. |

