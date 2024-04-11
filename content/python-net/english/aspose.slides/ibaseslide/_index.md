---
title: IBaseSlide
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ibaseslide/
---


IBaseSlide class

Represents common data for all slide types.

The IBaseSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shapes](/slides/python-net/aspose.slides/ibaseslide/shapes/) | Returns the shapes of a slide.<br/>            Read-only <br/>[`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)<br/>. |
| [controls](/slides/python-net/aspose.slides/ibaseslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only <br/>[`IControlCollection`](/slides/python-net/aspose.slides/icontrolcollection)<br/>. |
| [name](/slides/python-net/aspose.slides/ibaseslide/name/) | Returns or sets the name of a slide.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [slide_id](/slides/python-net/aspose.slides/ibaseslide/slide_id/) | Returns the ID of a slide.<br/>            Read-only <br/>.NET type System.UInt32<br/>. |
| [custom_data](/slides/python-net/aspose.slides/ibaseslide/custom_data/) | Returns the slide's custom data.<br/>            Read-only <br/>[`ICustomData`](/slides/python-net/aspose.slides/icustomdata)<br/>. |
| [timeline](/slides/python-net/aspose.slides/ibaseslide/timeline/) | Returns animation timeline object.<br/>            Read-only <br/>[`IAnimationTimeLine`](/slides/python-net/aspose.slides/ianimationtimeline)<br/>. |
| [slide_show_transition](/slides/python-net/aspose.slides/ibaseslide/slide_show_transition/) | Returns the TransitionEx object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only <br/>[`ISlideShowTransition`](/slides/python-net/aspose.slides/islideshowtransition)<br/>. |
| [background](/slides/python-net/aspose.slides/ibaseslide/background/) | Returns slide's background.<br/>            Read-only <br/>[`IBackground`](/slides/python-net/aspose.slides/ibackground)<br/>. |
| [hyperlink_queries](/slides/python-net/aspose.slides/ibaseslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only <br/>[`IHyperlinkQueries`](/slides/python-net/aspose.slides/ihyperlinkqueries)<br/>. |
| [show_master_shapes](/slides/python-net/aspose.slides/ibaseslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns <br/>`<br/>false<br/>`<br/>.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [as_i_themeable](/slides/python-net/aspose.slides/ibaseslide/as_i_themeable/) | Allows to get base IThemeable interface.<br/>            Read-only <br/>[`IThemeable`](/slides/python-net/aspose.slides.theme/ithemeable)<br/>. |
| [as_i_slide_component](/slides/python-net/aspose.slides/ibaseslide/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides/ibaseslide/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/ibaseslide/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides/ibaseslide/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [find_shape_by_alt_text](/slides/python-net/aspose.slides/ibaseslide/ibaseslide/#string/) | Finds first occurrence of a shape with the specified alternative text. |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/ibaseslide/ibaseslide/#/) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [equals](/slides/python-net/aspose.slides/ibaseslide/ibaseslide/#IBaseSlide/) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [create_theme_effective](/slides/python-net/aspose.slides/ibaseslide/ibaseslide/#/) |  |

