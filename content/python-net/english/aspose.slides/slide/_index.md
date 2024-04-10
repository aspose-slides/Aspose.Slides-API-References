---
title: Slide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## Slide class

Represents a slide in a presentation.

**Inheritance:**[`Slide`](/slides/python-net/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/aspose.slides/baseslide)

The Slide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shapes](/slides/python-net/aspose.slides/shapes) | Returns the shapes of a slide.<br/>            Read-only :py:class:`aspose.slides.IShapeCollection`. |
| [controls](/slides/python-net/aspose.slides/controls) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only :py:class:`aspose.slides.IControlCollection`. |
| [name](/slides/python-net/aspose.slides/name) | Returns or sets the name of a slide.<br/>            Read/write :py:class:`System.String`. |
| [slide_id](/slides/python-net/aspose.slides/slide_id) | Returns the ID of a slide.<br/>            Read-only :py:class:`int`. |
| [custom_data](/slides/python-net/aspose.slides/custom_data) | Returns the slide's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [timeline](/slides/python-net/aspose.slides/timeline) | Returns animation timeline object.<br/>            Read-only :py:class:`aspose.slides.IAnimationTimeLine`. |
| [slide_show_transition](/slides/python-net/aspose.slides/slide_show_transition) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only :py:class:`aspose.slides.ISlideShowTransition`. |
| [background](/slides/python-net/aspose.slides/background) | Returns slide's background.<br/>            Read-only :py:class:`aspose.slides.IBackground`. |
| [hyperlink_queries](/slides/python-net/aspose.slides/hyperlink_queries) | Provides easy access to contained hyperlinks.<br/>            Read-only :py:class:`aspose.slides.IHyperlinkQueries`. |
| [show_master_shapes](/slides/python-net/aspose.slides/show_master_shapes) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Read/write :py:class:`bool`. |
| [presentation](/slides/python-net/aspose.slides/presentation) | Returns IPresentation interface.<br/>            Read-only :py:class:`aspose.slides.IPresentation`. |
| [header_footer_manager](/slides/python-net/aspose.slides/header_footer_manager) | Returns HeaderFooter manager of the slide.<br/>            Read-only :py:class:`aspose.slides.ISlideHeaderFooterManager`. |
| [theme_manager](/slides/python-net/aspose.slides/theme_manager) | Returns the overriding theme manager.<br/>            Read-only :py:class:`aspose.slides.theme.IOverrideThemeManager`. |
| [slide_number](/slides/python-net/aspose.slides/slide_number) | Returns a number of slide.<br/>            Index of slide in :py:attr:`aspose.slides.Presentation.slides` collection is always equal to SlideNumber - Presentation.FirstSlideNumber.<br/>            Read/write :py:class:`int`. |
| [hidden](/slides/python-net/aspose.slides/hidden) | Determines whether the specified slide is hidden during a slide show.<br/>            Read/write :py:class:`bool`. |
| [layout_slide](/slides/python-net/aspose.slides/layout_slide) | Returns or sets the layout slide for the current slide.<br/>            Read/write :py:class:`aspose.slides.ILayoutSlide`. |
| [notes_slide_manager](/slides/python-net/aspose.slides/notes_slide_manager) | Allow to access notes slide, add and remove it.<br/>            Read-only :py:class:`aspose.slides.INotesSlideManager`. |
| [as_i_slide_component](/slides/python-net/aspose.slides/as_i_slide_component) |  |
| [slide](/slides/python-net/aspose.slides/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/as_i_presentation_component) |  |
| [as_i_base_slide](/slides/python-net/aspose.slides/as_i_base_slide) |  |
| [as_i_override_themeable](/slides/python-net/aspose.slides/as_i_override_themeable) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/slide/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [__init__](/slides/python-net/aspose.slides/slide/#IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [__init__](/slides/python-net/aspose.slides/slide/#float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/slide/#) | Returns a Thumbnail Image object (20% of real size). |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.pydrawing.Size) | Returns a Thumbnail Bitmap object with specified size. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.ITiffOptions) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.INotesCommentsLayoutingOptions) | Returns a Thumbnail Bitmap object. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.INotesCommentsLayoutingOptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap object with specified size. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.IRenderingOptions) | Returns a Thumbnail Bitmap object. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.IRenderingOptions-float-float) | Returns a Thumbnail Bitmap object with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Size) | Returns a Thumbnail Bitmap object with specified size. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics-int-int) | Renders certain slide to a Graphics object using specified size. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics-float) | Renders certain slide to a Graphics object using specified scale. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.INotesCommentsLayoutingOptions-aspose.pydrawing.Graphics) | Renders certain slide to a Graphics object. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics) | Renders certain slide to a Graphics object. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics-float-float) | Renders certain slide to a Graphics object with custom scaling. |
| [__init__](/slides/python-net/aspose.slides/slide/#aspose.slides.export.IRenderingOptions-aspose.pydrawing.Graphics-aspose.pydrawing.Size) | Renders certain slide to a Graphics object using specified size. |
| [__init__](/slides/python-net/aspose.slides/slide/#System.IO.Stream) | Saves content of slide as SVG file. |
| [__init__](/slides/python-net/aspose.slides/slide/#System.IO.Stream-aspose.slides.export.ISVGOptions) | Saves content of slide as SVG file. |
| [__init__](/slides/python-net/aspose.slides/slide/#IBaseSlide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [__init__](/slides/python-net/aspose.slides/slide/#) | Returns an effective theme for this slide. |
| [__init__](/slides/python-net/aspose.slides/slide/#string) | Finds first occurrence of a shape with the specified alternative text. |
| [__init__](/slides/python-net/aspose.slides/slide/#) | Removes slide from presentation. |
| [__init__](/slides/python-net/aspose.slides/slide/#) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [__init__](/slides/python-net/aspose.slides/slide/#ICommentAuthor) | Returns all slide comments added by specific author. |

