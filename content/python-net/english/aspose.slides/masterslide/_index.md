---
title: MasterSlide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## MasterSlide class

Represents a master slide in a presentation.

**Inheritance:**[`MasterSlide`](/slides/python-net/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/aspose.slides/baseslide)

The MasterSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shapes](/slides/python-net/aspose.slides/shapes) | Returns the shapes of a slide.<br/>            Read-only :py:class:`aspose.slides.IShapeCollection`. |
| [controls](/slides/python-net/aspose.slides/controls) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only :py:class:`aspose.slides.IControlCollection`. |
| [name](/slides/python-net/aspose.slides/name) | Returns or sets the name of a master slide.<br/>            Read/write :py:class:`System.String`. |
| [slide_id](/slides/python-net/aspose.slides/slide_id) | Returns the ID of a slide.<br/>            Read-only :py:class:`int`. |
| [custom_data](/slides/python-net/aspose.slides/custom_data) | Returns the slide's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [timeline](/slides/python-net/aspose.slides/timeline) | Returns animation timeline object.<br/>            Read-only :py:class:`aspose.slides.IAnimationTimeLine`. |
| [slide_show_transition](/slides/python-net/aspose.slides/slide_show_transition) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only :py:class:`aspose.slides.ISlideShowTransition`. |
| [background](/slides/python-net/aspose.slides/background) | Returns slide's background.<br/>            Read-only :py:class:`aspose.slides.IBackground`. |
| [hyperlink_queries](/slides/python-net/aspose.slides/hyperlink_queries) | Provides easy access to contained hyperlinks.<br/>            Read-only :py:class:`aspose.slides.IHyperlinkQueries`. |
| [show_master_shapes](/slides/python-net/aspose.slides/show_master_shapes) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns ``false``.<br/>            Read/write :py:class:`bool`. |
| [presentation](/slides/python-net/aspose.slides/presentation) | Returns IPresentation interface.<br/>            Read-only :py:class:`aspose.slides.IPresentation`. |
| [header_footer_manager](/slides/python-net/aspose.slides/header_footer_manager) | Returns HeaderFooter manager of the master slide.<br/>            Read-only :py:class:`aspose.slides.IMasterSlideHeaderFooterManager`. |
| [title_style](/slides/python-net/aspose.slides/title_style) | Returns the style of a title text.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [body_style](/slides/python-net/aspose.slides/body_style) | Returns the style of a body text.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [other_style](/slides/python-net/aspose.slides/other_style) | Returns the style of an other text.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [layout_slides](/slides/python-net/aspose.slides/layout_slides) | Returns the collection of child layout slides for this master slide.<br/>            Read-only :py:class:`aspose.slides.IMasterLayoutSlideCollection`. |
| [preserve](/slides/python-net/aspose.slides/preserve) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted.<br/>            Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call :py:func:`Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste.`<br/>            Read/write :py:class:`bool`. |
| [has_depending_slides](/slides/python-net/aspose.slides/has_depending_slides) | Returns true if there exists at least one slide that depends on this master slide.<br/>            Read-only :py:class:`bool`. |
| [theme_manager](/slides/python-net/aspose.slides/theme_manager) | Returns the theme manager.<br/>            Read-only :py:class:`aspose.slides.theme.IMasterThemeManager`. |
| [as_i_slide_component](/slides/python-net/aspose.slides/as_i_slide_component) |  |
| [slide](/slides/python-net/aspose.slides/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/as_i_presentation_component) |  |
| [as_i_base_slide](/slides/python-net/aspose.slides/as_i_base_slide) |  |
| [as_i_master_themeable](/slides/python-net/aspose.slides/as_i_master_themeable) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/masterslide/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [__init__](/slides/python-net/aspose.slides/masterslide/#IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [__init__](/slides/python-net/aspose.slides/masterslide/#IBaseSlide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [__init__](/slides/python-net/aspose.slides/masterslide/#) | Returns an effective theme for this slide. |
| [__init__](/slides/python-net/aspose.slides/masterslide/#string) | Finds first occurrence of a shape with the specified alternative text. |
| [__init__](/slides/python-net/aspose.slides/masterslide/#string) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [__init__](/slides/python-net/aspose.slides/masterslide/#) | Returns an array with all slides, which depend on this master slide. |

