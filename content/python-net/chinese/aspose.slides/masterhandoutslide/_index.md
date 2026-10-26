---
title: MasterHandoutSlide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide 类

表示讲义的主幻灯片。

**继承:**[`MasterHandoutSlide`](/slides/python-net/zh/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)

The MasterHandoutSlide type exposes the following members:

## 属性

| 属性 | 说明 |
| :- | :- |
| [`shapes`](/slides/python-net/zh/aspose.slides/masterhandoutslide/shapes/) | Returns the shapes of a slide.<br/>            只读 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/zh/aspose.slides/masterhandoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            只读 [`IControlCollection`](/slides/python-net/zh/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/zh/aspose.slides/masterhandoutslide/name/) | Returns or sets the name of a slide.<br/>            读写 **str**. |
| [`slide_id`](/slides/python-net/zh/aspose.slides/masterhandoutslide/slide_id/) | Returns the ID of a slide.<br/>            只读 **int**. |
| [`custom_data`](/slides/python-net/zh/aspose.slides/masterhandoutslide/custom_data/) | Returns the slide's custom data.<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/zh/aspose.slides/masterhandoutslide/timeline/) | Returns animation timeline object.<br/>            只读 [`IAnimationTimeLine`](/slides/python-net/zh/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/masterhandoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            只读 [`ISlideShowTransition`](/slides/python-net/zh/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/zh/aspose.slides/masterhandoutslide/background/) | Returns slide's background.<br/>            只读 [`IBackground`](/slides/python-net/zh/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/masterhandoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/masterhandoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            读写 **bool**. |
| [`presentation`](/slides/python-net/zh/aspose.slides/masterhandoutslide/presentation/) | Returns IPresentation interface.<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/masterhandoutslide/header_footer_manager/) | Returns HeaderFooter manager of the master handout slide.<br/>            只读 [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/zh/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/zh/aspose.slides/masterhandoutslide/theme_manager/) | Returns the theme manager.<br/>            只读 [`IMasterThemeManager`](/slides/python-net/zh/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/zh/aspose.slides/masterhandoutslide/drawing_guides/) | Returns a collection of drawing guides for the master handout slide.<br/>            只读 [`IDrawingGuidesCollection`](/slides/python-net/zh/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/zh/aspose.slides/masterhandoutslide/slide/) |  |

## 方法

| 方法 | 说明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/masterhandoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |


### 另请参见
* 类 [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)
* 类 [`MasterHandoutSlide`](/slides/python-net/zh/aspose.slides/masterhandoutslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)