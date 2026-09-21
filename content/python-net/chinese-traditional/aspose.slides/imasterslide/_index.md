---
title: IMasterSlide class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/imasterslide/
---
## IMasterSlide 類別

表示簡報中的母投影片。

IMasterSlide 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/imasterslide/header_footer_manager/) | Returns HeaderFooter manager of the master slide.<br/>            唯讀 [`IMasterSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/zh-hant/aspose.slides/imasterslide/title_style/) | Returns the style of a title text.<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/zh-hant/aspose.slides/imasterslide/body_style/) | Returns the style of a body text.<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/zh-hant/aspose.slides/imasterslide/other_style/) | Returns the style of an other text.<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/zh-hant/aspose.slides/imasterslide/layout_slides/) | Returns the collection of child layout slides for this master slide.<br/>            唯讀 [`IMasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/zh-hant/aspose.slides/imasterslide/preserve/) | Determines whether the corresponding master is deleted when all <br/>            the slides that follow that master are deleted.<br/>            Note: Aspose.Slides will never remove any unused master by itself, <br/>            to actually remove unused masters call **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            讀寫 **bool**. |
| [`has_depending_slides`](/slides/python-net/zh-hant/aspose.slides/imasterslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this master slide.<br/>            唯讀 **bool**. |
| [`drawing_guides`](/slides/python-net/zh-hant/aspose.slides/imasterslide/drawing_guides/) | Returns a collection of drawing guides for the master slide.<br/>            唯讀 [`IDrawingGuidesCollection`](/slides/python-net/zh-hant/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/zh-hant/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/zh-hant/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/zh-hant/aspose.slides/imasterslide/theme_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/zh-hant/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [`get_depending_slides(self)`](/slides/python-net/zh-hant/aspose.slides/imasterslide/get_depending_slides/#) | Returns an array with all slides, which depend on this master slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/imasterslide/create_theme_effective/#) |  |


### 另請參閱
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)