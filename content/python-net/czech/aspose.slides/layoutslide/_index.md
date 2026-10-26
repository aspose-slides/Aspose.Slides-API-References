---
title: LayoutSlide class
second_title: Aspose.Slides pro Python přes .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/layoutslide/
---
## LayoutSlide třída

Represents a layout slide.

**Inheritance:**[`LayoutSlide`](/slides/python-net/cs/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)

The LayoutSlide type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/cs/aspose.slides/layoutslide/shapes/) | Returns the shapes of a slide.<br/>            Read-only [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/cs/aspose.slides/layoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Read-only [`IControlCollection`](/slides/python-net/cs/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/cs/aspose.slides/layoutslide/name/) | Returns or sets the name of a slide.<br/>            Read/write **str**. |
| [`slide_id`](/slides/python-net/cs/aspose.slides/layoutslide/slide_id/) | Returns the ID of a slide.<br/>            Read-only **int**. |
| [`custom_data`](/slides/python-net/cs/aspose.slides/layoutslide/custom_data/) | Returns the slide's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/cs/aspose.slides/layoutslide/timeline/) | Returns animation timeline object.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/cs/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/cs/aspose.slides/layoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/cs/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/cs/aspose.slides/layoutslide/background/) | Returns slide's background.<br/>            Read-only [`IBackground`](/slides/python-net/cs/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/layoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/cs/aspose.slides/layoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Read/write **bool**. |
| [`presentation`](/slides/python-net/cs/aspose.slides/layoutslide/presentation/) | Returns IPresentation interface.<br/>            Read-only [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/layoutslide/header_footer_manager/) | Returns HeaderFooter manager of the layout slide.<br/>            Read-only [`ILayoutSlideHeaderFooterManager`](/slides/python-net/cs/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/cs/aspose.slides/layoutslide/placeholder_manager/) | Returns the placeholder manager of the layout slide.<br/>            Read-only [`ILayoutPlaceholderManager`](/slides/python-net/cs/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/cs/aspose.slides/layoutslide/master_slide/) | Returns or sets the master slide for a layout.<br/>            Read/write [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/cs/aspose.slides/layoutslide/theme_manager/) | Returns the overriding theme manager.<br/>            Read-only [`IOverrideThemeManager`](/slides/python-net/cs/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/cs/aspose.slides/layoutslide/layout_type/) | Returns layout type of this layout slide.<br/>            Read-only [`SlideLayoutType`](/slides/python-net/cs/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/cs/aspose.slides/layoutslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this layout slide.<br/>            Read-only **bool**. |
| [`drawing_guides`](/slides/python-net/cs/aspose.slides/layoutslide/drawing_guides/) | Returns a collection of drawing guides for the layout slide.<br/>            Read-only [`IDrawingGuidesCollection`](/slides/python-net/cs/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/cs/aspose.slides/layoutslide/slide/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/cs/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/cs/aspose.slides/layoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides/layoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/cs/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`remove(self)`](/slides/python-net/cs/aspose.slides/layoutslide/remove/#) | Removes layout from presentation. |
| [`get_depending_slides(self)`](/slides/python-net/cs/aspose.slides/layoutslide/get_depending_slides/#) | Returns an array with all slides, which depend on this layout slide. |


### Viz také
* třída [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)
* třída [`LayoutSlide`](/slides/python-net/cs/aspose.slides/layoutslide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)