---
title: LayoutSlide class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/layoutslide/
---
## classe LayoutSlide

Rappresenta una diapositiva di layout.

**Inheritance:**[`LayoutSlide`](/slides/python-net/it/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)

Il tipo LayoutSlide espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/it/aspose.slides/layoutslide/shapes/) | Returns the shapes of a slide.<br/>            Solo lettura [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/it/aspose.slides/layoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Solo lettura [`IControlCollection`](/slides/python-net/it/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/it/aspose.slides/layoutslide/name/) | Returns or sets the name of a slide.<br/>            Lettura/scrittura **str**. |
| [`slide_id`](/slides/python-net/it/aspose.slides/layoutslide/slide_id/) | Returns the ID of a slide.<br/>            Solo lettura **int**. |
| [`custom_data`](/slides/python-net/it/aspose.slides/layoutslide/custom_data/) | Returns the slide's custom data.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/it/aspose.slides/layoutslide/timeline/) | Returns animation timeline object.<br/>            Solo lettura [`IAnimationTimeLine`](/slides/python-net/it/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/layoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Solo lettura [`ISlideShowTransition`](/slides/python-net/it/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/it/aspose.slides/layoutslide/background/) | Returns slide's background.<br/>            Solo lettura [`IBackground`](/slides/python-net/it/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/layoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Solo lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/layoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Lettura/scrittura **bool**. |
| [`presentation`](/slides/python-net/it/aspose.slides/layoutslide/presentation/) | Returns IPresentation interface.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/layoutslide/header_footer_manager/) | Returns HeaderFooter manager of the layout slide.<br/>            Solo lettura [`ILayoutSlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/it/aspose.slides/layoutslide/placeholder_manager/) | Returns the placeholder manager of the layout slide.<br/>            Solo lettura [`ILayoutPlaceholderManager`](/slides/python-net/it/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/it/aspose.slides/layoutslide/master_slide/) | Returns or sets the master slide for a layout.<br/>            Lettura/scrittura [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/it/aspose.slides/layoutslide/theme_manager/) | Returns the overriding theme manager.<br/>            Solo lettura [`IOverrideThemeManager`](/slides/python-net/it/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/it/aspose.slides/layoutslide/layout_type/) | Returns layout type of this layout slide.<br/>            Solo lettura [`SlideLayoutType`](/slides/python-net/it/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/it/aspose.slides/layoutslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this layout slide.<br/>            Solo lettura **bool**. |
| [`drawing_guides`](/slides/python-net/it/aspose.slides/layoutslide/drawing_guides/) | Returns a collection of drawing guides for the layout slide.<br/>            Solo lettura [`IDrawingGuidesCollection`](/slides/python-net/it/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/it/aspose.slides/layoutslide/slide/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/it/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/layoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/layoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`remove(self)`](/slides/python-net/it/aspose.slides/layoutslide/remove/#) | Removes layout from presentation. |
| [`get_depending_slides(self)`](/slides/python-net/it/aspose.slides/layoutslide/get_depending_slides/#) | Returns an array with all slides, which depend on this layout slide. |

### Vedi anche
* classe [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)
* classe [`LayoutSlide`](/slides/python-net/it/aspose.slides/layoutslide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)