---
title: IMasterSlide class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/imasterslide/
---
## کلاس IMasterSlide

یک اسلاید مستر را در یک ارائه نشان می‌دهد.

نوع IMMasterSlide اعضای زیر را ارائه می‌دهد:

## خصوصیات

| ویژگی | توضیح |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/imasterslide/header_footer_manager/) | Returns HeaderFooter manager of the master slide.<br/>            فقط-خواندنی [`IMasterSlideHeaderFooterManager`](/slides/python-net/fa/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/fa/aspose.slides/imasterslide/title_style/) | Returns the style of a title text.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/fa/aspose.slides/imasterslide/body_style/) | Returns the style of a body text.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/fa/aspose.slides/imasterslide/other_style/) | Returns the style of an other text.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/fa/aspose.slides/imasterslide/layout_slides/) | Returns the collection of child layout slides for this master slide.<br/>            فقط-خواندنی [`IMasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/fa/aspose.slides/imasterslide/preserve/) | Determines whether the corresponding master is deleted when all <br/>            the slides that follow that master are deleted.<br/>            Note: Aspose.Slides will never remove any unused master by itself, <br/>            to actually remove unused masters call **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            خواندنی/نوشتنی **bool**. |
| [`has_depending_slides`](/slides/python-net/fa/aspose.slides/imasterslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this master slide.<br/>            فقط-خواندنی **bool**. |
| [`drawing_guides`](/slides/python-net/fa/aspose.slides/imasterslide/drawing_guides/) | Returns a collection of drawing guides for the master slide.<br/>            فقط-خواندنی [`IDrawingGuidesCollection`](/slides/python-net/fa/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/fa/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/fa/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/fa/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/fa/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/fa/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/fa/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/fa/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/fa/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/fa/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/fa/aspose.slides/imasterslide/theme_manager/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/fa/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [`get_depending_slides(self)`](/slides/python-net/fa/aspose.slides/imasterslide/get_depending_slides/#) | Returns an array with all slides, which depend on this master slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fa/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/fa/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides/imasterslide/create_theme_effective/#) |  |

### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)