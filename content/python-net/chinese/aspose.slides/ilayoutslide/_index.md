---
title: ILayoutSlide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ilayoutslide/
---
## ILayoutSlide 类

表示一个布局幻灯片。

ILayoutSlide 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/ilayoutslide/header_footer_manager/) | 返回布局幻灯片的 HeaderFooter 管理器。<br/>            只读 [`ILayoutSlideHeaderFooterManager`](/slides/python-net/zh/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/zh/aspose.slides/ilayoutslide/placeholder_manager/) | 返回布局幻灯片的占位符管理器。<br/>            只读 [`ILayoutPlaceholderManager`](/slides/python-net/zh/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/zh/aspose.slides/ilayoutslide/master_slide/) | 返回或设置布局的母版幻灯片。<br/>            可读写 [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide). |
| [`layout_type`](/slides/python-net/zh/aspose.slides/ilayoutslide/layout_type/) | 返回此布局幻灯片的布局类型。<br/>            只读 [`SlideLayoutType`](/slides/python-net/zh/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/zh/aspose.slides/ilayoutslide/has_depending_slides/) | 如果存在至少一个依赖此布局幻灯片的幻灯片，则返回 true。<br/>            只读 **bool**. |
| [`drawing_guides`](/slides/python-net/zh/aspose.slides/ilayoutslide/drawing_guides/) | 返回布局幻灯片的绘图参考线集合。<br/>            只读 [`IDrawingGuidesCollection`](/slides/python-net/zh/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/zh/aspose.slides/ilayoutslide/shapes/) |  |
| [`controls`](/slides/python-net/zh/aspose.slides/ilayoutslide/controls/) |  |
| [`name`](/slides/python-net/zh/aspose.slides/ilayoutslide/name/) |  |
| [`slide_id`](/slides/python-net/zh/aspose.slides/ilayoutslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/zh/aspose.slides/ilayoutslide/custom_data/) |  |
| [`timeline`](/slides/python-net/zh/aspose.slides/ilayoutslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/ilayoutslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/zh/aspose.slides/ilayoutslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/ilayoutslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/ilayoutslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides/ilayoutslide/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/ilayoutslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/zh/aspose.slides/ilayoutslide/theme_manager/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_depending_slides(self)`](/slides/python-net/zh/aspose.slides/ilayoutslide/get_depending_slides/#) | 返回一个数组，包含所有依赖此布局幻灯片的幻灯片。 |
| [`remove(self)`](/slides/python-net/zh/aspose.slides/ilayoutslide/remove/#) | 从演示文稿中移除布局。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/ilayoutslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/ilayoutslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/ilayoutslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/ilayoutslide/create_theme_effective/#) |  |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)