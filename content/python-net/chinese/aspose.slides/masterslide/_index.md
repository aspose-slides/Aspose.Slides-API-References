---
title: MasterSlide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterslide/
---
## MasterSlide 类

表示演示文稿中的母版幻灯片。

**继承:**[`MasterSlide`](/slides/python-net/zh/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)

MasterSlide 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`shapes`](/slides/python-net/zh/aspose.slides/masterslide/shapes/) | 返回幻灯片的形状。<br/>            只读 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/zh/aspose.slides/masterslide/controls/) | 返回幻灯片上 ActiveX 控件的集合。<br/>            只读 [`IControlCollection`](/slides/python-net/zh/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/zh/aspose.slides/masterslide/name/) | 返回或设置母版幻灯片的名称。<br/>            读/写 **str**. |
| [`slide_id`](/slides/python-net/zh/aspose.slides/masterslide/slide_id/) | 返回幻灯片的 ID。<br/>            只读 **int**. |
| [`custom_data`](/slides/python-net/zh/aspose.slides/masterslide/custom_data/) | 返回幻灯片的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/zh/aspose.slides/masterslide/timeline/) | 返回动画时间线对象。<br/>            只读 [`IAnimationTimeLine`](/slides/python-net/zh/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/masterslide/slide_show_transition/) | 返回包含关于在幻灯片放映期间指定幻灯片如何推进的信息的 Transition 对象。<br/>            只读 [`ISlideShowTransition`](/slides/python-net/zh/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/zh/aspose.slides/masterslide/background/) | 返回幻灯片的背景。<br/>            只读 [`IBackground`](/slides/python-net/zh/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/masterslide/hyperlink_queries/) | 提供对包含的超链接的简易访问。<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/masterslide/show_master_shapes/) | 指定是否在幻灯片上显示母版幻灯片上的形状。<br/>            对于母版幻灯片本身，此属性始终返回 `false`。<br/>            读/写 **bool**. |
| [`presentation`](/slides/python-net/zh/aspose.slides/masterslide/presentation/) | 返回 IPresentation 接口。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/masterslide/header_footer_manager/) | 返回母版幻灯片的 HeaderFooter 管理器。<br/>            只读 [`IMasterSlideHeaderFooterManager`](/slides/python-net/zh/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/zh/aspose.slides/masterslide/title_style/) | 返回标题文本的样式。<br/>            只读 [`ITextStyle`](/slides/python-net/zh/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/zh/aspose.slides/masterslide/body_style/) | 返回正文文本的样式。<br/>            只读 [`ITextStyle`](/slides/python-net/zh/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/zh/aspose.slides/masterslide/other_style/) | 返回其他文本的样式。<br/>            只读 [`ITextStyle`](/slides/python-net/zh/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/zh/aspose.slides/masterslide/layout_slides/) | 返回此母版幻灯片的子布局幻灯片集合。<br/>            只读 [`IMasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/zh/aspose.slides/masterslide/preserve/) | 确定当删除所有跟随该母版的幻灯片时是否删除相应的母版。<br/>            注意：Aspose.Slides 永远不会自行删除任何未使用的母版，要实际删除未使用的母版，请调用 **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            读/写 **bool**. |
| [`has_depending_slides`](/slides/python-net/zh/aspose.slides/masterslide/has_depending_slides/) | 如果存在至少一个依赖此母版幻灯片的幻灯片，则返回 true。<br/>            只读 **bool**. |
| [`theme_manager`](/slides/python-net/zh/aspose.slides/masterslide/theme_manager/) | 返回主题管理器。<br/>            只读 [`IMasterThemeManager`](/slides/python-net/zh/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/zh/aspose.slides/masterslide/drawing_guides/) | 返回母版幻灯片的绘图参考线集合。<br/>            只读 [`IDrawingGuidesCollection`](/slides/python-net/zh/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/zh/aspose.slides/masterslide/slide/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/masterslide/join_portions_with_same_formatting/#) | 在所有可接受的形状的所有段落中合并具有相同格式的文本运行。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | 在所有可接受的形状的所有段落中合并具有相同格式的文本运行。 |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/masterslide/equals/#ibaseslide) | 确定两个 IBaseSlide 实例是否相等。<br/>            返回值根据幻灯片的结构和静态内容计算。<br/>            如果所有形状、样式、文本、动画和其他设置等都相等，则两张幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如日期占位符中的当前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/masterslide/create_theme_effective/#) | 返回此幻灯片的有效主题。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/masterslide/find_shape_by_alt_text/#str) | 查找具有指定替代文本的形状的首次出现。 |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/zh/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | 基于当前母版幻灯片创建一个新母版幻灯片，并对其应用外部主题 <br/>            然后将创建的母版幻灯片应用于所有依赖的幻灯片。 |
| [`get_depending_slides(self)`](/slides/python-net/zh/aspose.slides/masterslide/get_depending_slides/#) | 返回一个包含所有依赖此母版幻灯片的幻灯片的数组。 |


### 另请参见
* 类 [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)
* 类 [`MasterSlide`](/slides/python-net/zh/aspose.slides/masterslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)