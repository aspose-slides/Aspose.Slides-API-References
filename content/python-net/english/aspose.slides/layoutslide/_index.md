---
title: LayoutSlide class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/layoutslide/
---


## LayoutSlide class

Represents a layout slide.

**Inheritance:**[`LayoutSlide`](/slides/python-net/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/aspose.slides/baseslide)

The LayoutSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/aspose.slides/layoutslide/shapes/) | Returns the shapes of a slide.<br/>            Read-only [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/aspose.slides/layoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only [`IControlCollection`](/slides/python-net/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/aspose.slides/layoutslide/name/) | Returns or sets the name of a slide.<br/>            Read/write **string**. |
| [`slide_id`](/slides/python-net/aspose.slides/layoutslide/slide_id/) | Returns the ID of a slide.<br/>            Read-only **int**. |
| [`custom_data`](/slides/python-net/aspose.slides/layoutslide/custom_data/) | Returns the slide's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/aspose.slides/layoutslide/timeline/) | Returns animation timeline object.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/aspose.slides/layoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/aspose.slides/layoutslide/background/) | Returns slide's background.<br/>            Read-only [`IBackground`](/slides/python-net/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/aspose.slides/layoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/aspose.slides/layoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Read/write **bool**. |
| [`presentation`](/slides/python-net/aspose.slides/layoutslide/presentation/) | Returns IPresentation interface.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/aspose.slides/layoutslide/header_footer_manager/) | Returns HeaderFooter manager of the layout slide.<br/>            Read-only [`ILayoutSlideHeaderFooterManager`](/slides/python-net/aspose.slides/ilayoutslideheaderfootermanager). |
| [`master_slide`](/slides/python-net/aspose.slides/layoutslide/master_slide/) | Returns or sets the master slide for a layout.<br/>            Read/write [`IMasterSlide`](/slides/python-net/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/aspose.slides/layoutslide/theme_manager/) | Returns the overriding theme manager.<br/>            Read-only [`IOverrideThemeManager`](/slides/python-net/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/aspose.slides/layoutslide/layout_type/) | Returns layout type of this layout slide.<br/>            Read-only [`SlideLayoutType`](/slides/python-net/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/aspose.slides/layoutslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this layout slide.<br/>            Read-only **bool**. |
| [`as_i_slide_component`](/slides/python-net/aspose.slides/layoutslide/as_i_slide_component/) |  |
| [`slide`](/slides/python-net/aspose.slides/layoutslide/slide/) |  |
| [`as_i_presentation_component`](/slides/python-net/aspose.slides/layoutslide/as_i_presentation_component/) |  |
| [`as_i_base_slide`](/slides/python-net/aspose.slides/layoutslide/as_i_base_slide/) |  |
| [`as_i_override_themeable`](/slides/python-net/aspose.slides/layoutslide/as_i_override_themeable/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting`](/slides/python-net/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting`](/slides/python-net/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals`](/slides/python-net/aspose.slides/layoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective`](/slides/python-net/aspose.slides/layoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text`](/slides/python-net/aspose.slides/layoutslide/find_shape_by_alt_text/#string) | Finds first occurrence of a shape with the specified alternative text. |
| [`remove`](/slides/python-net/aspose.slides/layoutslide/remove/#) | Removes layout from presentation. |
| [`get_depending_slides`](/slides/python-net/aspose.slides/layoutslide/get_depending_slides/#) | Returns an array with all slides, which depend on this layout slide. |

### See Also
* class [`BaseSlide`](/slides/python-net/aspose.slides/baseslide)
* class [`LayoutSlide`](/slides/python-net/aspose.slides/layoutslide)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
