---
title: MasterNotesSlide
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/masternotesslide/
---


MasterNotesSlide class

Represents master slide for notes.

**Inheritance:**[`MasterNotesSlide`](/slides/python-net/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/aspose.slides/baseslide)

The MasterNotesSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shapes](/slides/python-net/aspose.slides/masternotesslide/shapes/) | Returns the shapes of a slide.<br/>            Read-only :py:class:`aspose.slides.IShapeCollection`. |
| [controls](/slides/python-net/aspose.slides/masternotesslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only :py:class:`aspose.slides.IControlCollection`. |
| [name](/slides/python-net/aspose.slides/masternotesslide/name/) | Returns or sets the name of a slide.<br/>            Read/write :py:class:`System.String`. |
| [slide_id](/slides/python-net/aspose.slides/masternotesslide/slide_id/) | Returns the ID of a slide.<br/>            Read-only :py:class:`int`. |
| [custom_data](/slides/python-net/aspose.slides/masternotesslide/custom_data/) | Returns the slide's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [timeline](/slides/python-net/aspose.slides/masternotesslide/timeline/) | Returns animation timeline object.<br/>            Read-only :py:class:`aspose.slides.IAnimationTimeLine`. |
| [slide_show_transition](/slides/python-net/aspose.slides/masternotesslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only :py:class:`aspose.slides.ISlideShowTransition`. |
| [background](/slides/python-net/aspose.slides/masternotesslide/background/) | Returns slide's background.<br/>            Read-only :py:class:`aspose.slides.IBackground`. |
| [hyperlink_queries](/slides/python-net/aspose.slides/masternotesslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only :py:class:`aspose.slides.IHyperlinkQueries`. |
| [show_master_shapes](/slides/python-net/aspose.slides/masternotesslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns ``false``.<br/>            Read/write :py:class:`bool`. |
| [presentation](/slides/python-net/aspose.slides/masternotesslide/presentation/) | Returns IPresentation interface.<br/>            Read-only :py:class:`aspose.slides.IPresentation`. |
| [header_footer_manager](/slides/python-net/aspose.slides/masternotesslide/header_footer_manager/) | Returns HeaderFooter manager of the master notes slide.<br/>            Read-only :py:class:`aspose.slides.IMasterHandoutSlideHeaderFooterManager`. |
| [theme_manager](/slides/python-net/aspose.slides/masternotesslide/theme_manager/) | Returns the theme manager.<br/>            Read-only :py:class:`aspose.slides.theme.IMasterThemeManager`. |
| [notes_style](/slides/python-net/aspose.slides/masternotesslide/notes_style/) | Returns the style of a notes text.<br/>            Read-only :py:class:`aspose.slides.ITextStyle`. |
| [as_i_slide_component](/slides/python-net/aspose.slides/masternotesslide/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides/masternotesslide/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/masternotesslide/as_i_presentation_component/) |  |
| [as_i_base_slide](/slides/python-net/aspose.slides/masternotesslide/as_i_base_slide/) |  |
| [as_i_master_themeable](/slides/python-net/aspose.slides/masternotesslide/as_i_master_themeable/) |  |

## Methods

| Method | Description |
| :- | :- |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/masternotesslide/masternotesslide/#/) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/masternotesslide/masternotesslide/#IShapeCollection/) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [equals](/slides/python-net/aspose.slides/masternotesslide/masternotesslide/#IBaseSlide/) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [create_theme_effective](/slides/python-net/aspose.slides/masternotesslide/masternotesslide/#/) | Returns an effective theme for this slide. |
| [find_shape_by_alt_text](/slides/python-net/aspose.slides/masternotesslide/masternotesslide/#string/) | Finds first occurrence of a shape with the specified alternative text. |

