---
title: NotesSlide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## NotesSlide class

Represents a notes slide in a presentation.

**Inheritance:**[`NotesSlide`](/slides/python-net/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/aspose.slides/baseslide)

The NotesSlide type exposes the following members:

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
| [header_footer_manager](/slides/python-net/aspose.slides/header_footer_manager) | Returns HeaderFooter manager of the notes slide.<br/>            Read-only :py:class:`aspose.slides.INotesSlideHeaderFooterManager`. |
| [notes_text_frame](/slides/python-net/aspose.slides/notes_text_frame) | Returns a TextFrame with notes' text if there is one.<br/>            Read-only :py:class:`aspose.slides.ITextFrame`. |
| [theme_manager](/slides/python-net/aspose.slides/theme_manager) | Returns the overriding theme manager.<br/>            Read-only :py:class:`aspose.slides.theme.IOverrideThemeManager`. |
| [parent_slide](/slides/python-net/aspose.slides/parent_slide) | Returns the parent slide.<br/>            Read-only :py:class:`aspose.slides.ISlide`. |
| [as_i_slide_component](/slides/python-net/aspose.slides/as_i_slide_component) |  |
| [slide](/slides/python-net/aspose.slides/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/as_i_presentation_component) |  |
| [as_i_base_slide](/slides/python-net/aspose.slides/as_i_base_slide) |  |
| [as_i_override_themeable](/slides/python-net/aspose.slides/as_i_override_themeable) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/notesslide/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [__init__](/slides/python-net/aspose.slides/notesslide/#IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [__init__](/slides/python-net/aspose.slides/notesslide/#IBaseSlide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [__init__](/slides/python-net/aspose.slides/notesslide/#) | Returns an effective theme for this slide. |
| [__init__](/slides/python-net/aspose.slides/notesslide/#string) | Finds first occurrence of a shape with the specified alternative text. |

