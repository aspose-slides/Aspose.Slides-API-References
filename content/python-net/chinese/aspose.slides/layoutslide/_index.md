---
title: LayoutSlide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/layoutslide/
---
## LayoutSlide 类

表示布局幻灯片。

**继承:**[`LayoutSlide`](/slides/python-net/zh/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)

LayoutSlide 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`shapes`](/slides/python-net/zh/aspose.slides/layoutslide/shapes/) | Returns the shapes of a slide.<br/>            只读 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/zh/aspose.slides/layoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            只读 [`IControlCollection`](/slides/python-net/zh/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/zh/aspose.slides/layoutslide/name/) | Returns or sets the name of a slide.<br/>            读写 **str**. |
| [`slide_id`](/slides/python-net/zh/aspose.slides/layoutslide/slide_id/) | Returns the ID of a slide.<br/>            只读 **int**. |
| [`custom_data`](/slides/python-net/zh/aspose.slides/layoutslide/custom_data/) | Returns the slide's custom data.<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/zh/aspose.slides/layoutslide/timeline/) | Returns animation timeline object.<br/>            只读 [`IAnimationTimeLine`](/slides/python-net/zh/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/layoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            只读 [`ISlideShowTransition`](/slides/python-net/zh/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/zh/aspose.slides/layoutslide/background/) | Returns slide's background.<br/>            只读 [`IBackground`](/slides/python-net/zh/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/layoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/layoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            读写 **bool**. |
| [`presentation`](/slides/python-net/zh/aspose.slides/layoutslide/presentation/) | Returns IPresentation interface.<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/layoutslide/header_footer_manager/) | Returns HeaderFooter manager of the layout slide.<br/>            只读 [`ILayoutSlideHeaderFooterManager`](/slides/python-net/zh/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/zh/aspose.slides/layoutslide/placeholder_manager/) | Returns the placeholder manager of the layout slide.<br/>            只读 [`ILayoutPlaceholderManager`](/slides/python-net/zh/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/zh/aspose.slides/layoutslide/master_slide/) | Returns or sets the master slide for a layout.<br/>            读写 [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/zh/aspose.slides/layoutslide/theme_manager/) | Returns the overriding theme manager.<br/>            只读 [`IOverrideThemeManager`](/slides/python-net/zh/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/zh/aspose.slides/layoutslide/layout_type/) | Returns layout type of this layout slide.<br/>            只读 [`SlideLayoutType`](/slides/python-net/zh/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/zh/aspose.slides/layoutslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this layout slide.<br/>            只读 **bool**. |
| [`drawing_guides`](/slides/python-net/zh/aspose.slides/layoutslide/drawing_guides/) | Returns a collection of drawing guides for the layout slide.<br/>            只读 [`IDrawingGuidesCollection`](/slides/python-net/zh/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/zh/aspose.slides/layoutslide/slide/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/layoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/layoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`remove(self)`](/slides/python-net/zh/aspose.slides/layoutslide/remove/#) | Removes layout from presentation. |
| [`get_depending_slides(self)`](/slides/python-net/zh/aspose.slides/layoutslide/get_depending_slides/#) | Returns an array with all slides, which depend on this layout slide. |


### 另请参见
* 类 [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)
* 类 [`LayoutSlide`](/slides/python-net/zh/aspose.slides/layoutslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)