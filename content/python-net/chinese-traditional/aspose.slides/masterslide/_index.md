---
title: MasterSlide class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/masterslide/
---
## MasterSlide 類別

表示簡報中的母投影片。

**Inheritance:**[`MasterSlide`](/slides/python-net/zh-hant/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)

MasterSlide 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/masterslide/shapes/) | Returns the shapes of a slide.<br/>            唯讀 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/masterslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            唯讀 [`IControlCollection`](/slides/python-net/zh-hant/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/masterslide/name/) | Returns or sets the name of a master slide.<br/>            可讀寫 **str**。 |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/masterslide/slide_id/) | Returns the ID of a slide.<br/>            唯讀 **int**。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/masterslide/custom_data/) | Returns the slide's custom data.<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/masterslide/timeline/) | Returns animation timeline object.<br/>            唯讀 [`IAnimationTimeLine`](/slides/python-net/zh-hant/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/masterslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            唯讀 [`ISlideShowTransition`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh-hant/aspose.slides/masterslide/background/) | Returns slide's background.<br/>            唯讀 [`IBackground`](/slides/python-net/zh-hant/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/masterslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/masterslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            可讀寫 **bool**。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/masterslide/presentation/) | Returns IPresentation interface.<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/masterslide/header_footer_manager/) | Returns HeaderFooter manager of the master slide.<br/>            唯讀 [`IMasterSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/imasterslideheaderfootermanager)。 |
| [`title_style`](/slides/python-net/zh-hant/aspose.slides/masterslide/title_style/) | Returns the style of a title text.<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle)。 |
| [`body_style`](/slides/python-net/zh-hant/aspose.slides/masterslide/body_style/) | Returns the style of a body text.<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle)。 |
| [`other_style`](/slides/python-net/zh-hant/aspose.slides/masterslide/other_style/) | Returns the style of an other text.<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle)。 |
| [`layout_slides`](/slides/python-net/zh-hant/aspose.slides/masterslide/layout_slides/) | Returns the collection of child layout slides for this master slide.<br/>            唯讀 [`IMasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/imasterlayoutslidecollection)。 |
| [`preserve`](/slides/python-net/zh-hant/aspose.slides/masterslide/preserve/) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted.<br/>            Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            可讀寫 **bool**。 |
| [`has_depending_slides`](/slides/python-net/zh-hant/aspose.slides/masterslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this master slide.<br/>            唯讀 **bool**。 |
| [`theme_manager`](/slides/python-net/zh-hant/aspose.slides/masterslide/theme_manager/) | Returns the theme manager.<br/>            唯讀 [`IMasterThemeManager`](/slides/python-net/zh-hant/aspose.slides.theme/imasterthememanager)。 |
| [`drawing_guides`](/slides/python-net/zh-hant/aspose.slides/masterslide/drawing_guides/) | Returns a collection of drawing guides for the master slide.<br/>            唯讀 [`IDrawingGuidesCollection`](/slides/python-net/zh-hant/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/masterslide/slide/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh-hant/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/masterslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/masterslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/zh-hant/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [`get_depending_slides(self)`](/slides/python-net/zh-hant/aspose.slides/masterslide/get_depending_slides/#) | Returns an array with all slides, which depend on this master slide. |


### 另見
* 類別 [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)
* 類別 [`MasterSlide`](/slides/python-net/zh-hant/aspose.slides/masterslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)