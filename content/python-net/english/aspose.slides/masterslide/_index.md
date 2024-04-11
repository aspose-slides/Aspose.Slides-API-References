---
title: MasterSlide
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/masterslide/
---


MasterSlide class

Represents a master slide in a presentation.

**Inheritance:**[`MasterSlide`](/slides/python-net/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/aspose.slides/baseslide)

The MasterSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shapes](/slides/python-net/aspose.slides/masterslide/shapes/) | Returns the shapes of a slide.<br/>            Read-only [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection). |
| [controls](/slides/python-net/aspose.slides/masterslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only [`IControlCollection`](/slides/python-net/aspose.slides/icontrolcollection). |
| [name](/slides/python-net/aspose.slides/masterslide/name/) | Returns or sets the name of a master slide.<br/>            Read/write .NET type System.String. |
| [slide_id](/slides/python-net/aspose.slides/masterslide/slide_id/) | Returns the ID of a slide.<br/>            Read-only .NET type System.UInt32. |
| [custom_data](/slides/python-net/aspose.slides/masterslide/custom_data/) | Returns the slide's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [timeline](/slides/python-net/aspose.slides/masterslide/timeline/) | Returns animation timeline object.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/aspose.slides/ianimationtimeline). |
| [slide_show_transition](/slides/python-net/aspose.slides/masterslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/aspose.slides/islideshowtransition). |
| [background](/slides/python-net/aspose.slides/masterslide/background/) | Returns slide's background.<br/>            Read-only [`IBackground`](/slides/python-net/aspose.slides/ibackground). |
| [hyperlink_queries](/slides/python-net/aspose.slides/masterslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/aspose.slides/ihyperlinkqueries). |
| [show_master_shapes](/slides/python-net/aspose.slides/masterslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Read/write .NET type System.Boolean. |
| [presentation](/slides/python-net/aspose.slides/masterslide/presentation/) | Returns IPresentation interface.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [header_footer_manager](/slides/python-net/aspose.slides/masterslide/header_footer_manager/) | Returns HeaderFooter manager of the master slide.<br/>            Read-only [`IMasterSlideHeaderFooterManager`](/slides/python-net/aspose.slides/imasterslideheaderfootermanager). |
| [title_style](/slides/python-net/aspose.slides/masterslide/title_style/) | Returns the style of a title text.<br/>            Read-only [`ITextStyle`](/slides/python-net/aspose.slides/itextstyle). |
| [body_style](/slides/python-net/aspose.slides/masterslide/body_style/) | Returns the style of a body text.<br/>            Read-only [`ITextStyle`](/slides/python-net/aspose.slides/itextstyle). |
| [other_style](/slides/python-net/aspose.slides/masterslide/other_style/) | Returns the style of an other text.<br/>            Read-only [`ITextStyle`](/slides/python-net/aspose.slides/itextstyle). |
| [layout_slides](/slides/python-net/aspose.slides/masterslide/layout_slides/) | Returns the collection of child layout slides for this master slide.<br/>            Read-only [`IMasterLayoutSlideCollection`](/slides/python-net/aspose.slides/imasterlayoutslidecollection). |
| [preserve](/slides/python-net/aspose.slides/masterslide/preserve/) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted.<br/>            Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste.<br/>            Read/write .NET type System.Boolean. |
| [has_depending_slides](/slides/python-net/aspose.slides/masterslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this master slide.<br/>            Read-only .NET type System.Boolean. |
| [theme_manager](/slides/python-net/aspose.slides/masterslide/theme_manager/) | Returns the theme manager.<br/>            Read-only [`IMasterThemeManager`](/slides/python-net/aspose.slides.theme/imasterthememanager). |
| [as_i_slide_component](/slides/python-net/aspose.slides/masterslide/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides/masterslide/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/masterslide/as_i_presentation_component/) |  |
| [as_i_base_slide](/slides/python-net/aspose.slides/masterslide/as_i_base_slide/) |  |
| [as_i_master_themeable](/slides/python-net/aspose.slides/masterslide/as_i_master_themeable/) |  |

## Methods

| Method | Description |
| :- | :- |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [join_portions_with_same_formatting](/slides/python-net/aspose.slides/masterslide/join_portions_with_same_formatting/#IShapeCollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [equals](/slides/python-net/aspose.slides/masterslide/equals/#IBaseSlide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [create_theme_effective](/slides/python-net/aspose.slides/masterslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [find_shape_by_alt_text](/slides/python-net/aspose.slides/masterslide/find_shape_by_alt_text/#string) | Finds first occurrence of a shape with the specified alternative text. |
| [apply_external_theme_to_depending_slides](/slides/python-net/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#string) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [get_depending_slides](/slides/python-net/aspose.slides/masterslide/get_depending_slides/#) | Returns an array with all slides, which depend on this master slide. |

