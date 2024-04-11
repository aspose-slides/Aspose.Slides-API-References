---
title: BaseSlide
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/baseslide/
---


BaseSlide class

Represents common data for all slide types.

The BaseSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shapes](/slides/python-net/aspose.slides/baseslide/shapes/) | Returns the shapes of a slide.<br/>            Read-only [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection). |
| [controls](/slides/python-net/aspose.slides/baseslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only [`IControlCollection`](/slides/python-net/aspose.slides/icontrolcollection). |
| [name](/slides/python-net/aspose.slides/baseslide/name/) | Returns or sets the name of a slide.<br/>            Read/write .NET type System.String. |
| [slide_id](/slides/python-net/aspose.slides/baseslide/slide_id/) | Returns the ID of a slide.<br/>            Read-only .NET type System.UInt32. |
| [custom_data](/slides/python-net/aspose.slides/baseslide/custom_data/) | Returns the slide's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [timeline](/slides/python-net/aspose.slides/baseslide/timeline/) | Returns animation timeline object.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/aspose.slides/ianimationtimeline). |
| [slide_show_transition](/slides/python-net/aspose.slides/baseslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/aspose.slides/islideshowtransition). |
| [background](/slides/python-net/aspose.slides/baseslide/background/) | Returns slide's background.<br/>            Read-only [`IBackground`](/slides/python-net/aspose.slides/ibackground). |
| [hyperlink_queries](/slides/python-net/aspose.slides/baseslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/aspose.slides/ihyperlinkqueries). |
| [show_master_shapes](/slides/python-net/aspose.slides/baseslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Read/write .NET type System.Boolean. |
| [presentation](/slides/python-net/aspose.slides/baseslide/presentation/) | Returns IPresentation interface.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [as_i_themeable](/slides/python-net/aspose.slides/baseslide/as_i_themeable/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/baseslide/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides/baseslide/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/baseslide/as_i_presentation_component/) |  |

## Methods

| Method | Description |
| :- | :- |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/baseslide/join_portions_with_same_formatting/#IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [equals](/slides/python-net/aspose.slides/baseslide/equals/#IBaseSlide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [create_theme_effective](/slides/python-net/aspose.slides/baseslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [find_shape_by_alt_text](/slides/python-net/aspose.slides/baseslide/find_shape_by_alt_text/#string) | Finds first occurrence of a shape with the specified alternative text. |

