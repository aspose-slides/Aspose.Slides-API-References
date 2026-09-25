---
title: Slide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/slide/
---
## Slide 类

表示演示文稿中的幻灯片。

**继承:**[`Slide`](/slides/python-net/zh/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)

Slide 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/zh/aspose.slides/slide/shapes/) | 返回幻灯片的形状。<br/>            只读 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh/aspose.slides/slide/controls/) | 返回幻灯片上 ActiveX 控件的集合。<br/>            只读 [`IControlCollection`](/slides/python-net/zh/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh/aspose.slides/slide/name/) | 返回或设置幻灯片的名称。<br/>            读/写 **str**。 |
| [`slide_id`](/slides/python-net/zh/aspose.slides/slide/slide_id/) | 返回幻灯片的 ID。<br/>            只读 **int**。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides/slide/custom_data/) | 返回幻灯片的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh/aspose.slides/slide/timeline/) | 返回动画时间轴对象。<br/>            只读 [`IAnimationTimeLine`](/slides/python-net/zh/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/slide/slide_show_transition/) | 返回 Transition 对象，其中包含有关<br/>            指定幻灯片在放映过程中如何前进的信息。<br/>            只读 [`ISlideShowTransition`](/slides/python-net/zh/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh/aspose.slides/slide/background/) | 返回幻灯片的背景。<br/>            只读 [`IBackground`](/slides/python-net/zh/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/slide/hyperlink_queries/) | 提供对包含的超链接的便捷访问。<br/>            只读 [`IHyperlinkQueries`](/slides/python-net/zh/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/slide/show_master_shapes/) | 指定是否在幻灯片上显示母版幻灯片上的形状。<br/>            读/写 **bool**。 |
| [`presentation`](/slides/python-net/zh/aspose.slides/slide/presentation/) | 返回 IPresentation 接口。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/slide/header_footer_manager/) | 返回幻灯片的 HeaderFooter 管理器。<br/>            只读 [`ISlideHeaderFooterManager`](/slides/python-net/zh/aspose.slides/islideheaderfootermanager)。 |
| [`theme_manager`](/slides/python-net/zh/aspose.slides/slide/theme_manager/) | 返回覆盖主题管理器。<br/>            只读 [`IOverrideThemeManager`](/slides/python-net/zh/aspose.slides.theme/ioverridethememanager)。 |
| [`slide_number`](/slides/python-net/zh/aspose.slides/slide/slide_number/) | 返回幻灯片的编号。<br/>            [`Presentation.slides`](/slides/python-net/zh/aspose.slides/presentation/slides) 集合中的索引始终等于 SlideNumber - Presentation.FirstSlideNumber。<br/>            读/写 **int**。 |
| [`hidden`](/slides/python-net/zh/aspose.slides/slide/hidden/) | 确定指定的幻灯片在放映期间是否隐藏。<br/>            读/写 **bool**。 |
| [`layout_slide`](/slides/python-net/zh/aspose.slides/slide/layout_slide/) | 返回或设置当前幻灯片的布局幻灯片。<br/>            读/写 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)。 |
| [`notes_slide_manager`](/slides/python-net/zh/aspose.slides/slide/notes_slide_manager/) | 允许访问注释幻灯片，添加和删除它。<br/>            只读 [`INotesSlideManager`](/slides/python-net/zh/aspose.slides/inotesslidemanager)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/slide/slide/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/slide/join_portions_with_same_formatting/#) | 在所有可接受的形状的所有段落中合并具有相同格式的文本块。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | 在所有可接受的形状的所有段落中合并具有相同格式的文本块。 |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/slide/get_image/#float-float) | 返回具有自定义缩放的缩略图图像对象。 |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/slide/get_image/#) | 返回缩略图图像对象（实际大小的 20%）。 |
| [`get_image(self, image_size)`](/slides/python-net/zh/aspose.slides/slide/get_image/#asposeslidessize) | 返回具有指定大小的缩略图图像对象。 |
| [`get_image(self, options)`](/slides/python-net/zh/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | 返回具有指定参数的缩略图 TIFF 图像对象。 |
| [`get_image(self, options)`](/slides/python-net/zh/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | 返回缩略图图像对象。 |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | 返回具有自定义缩放的缩略图图像对象。 |
| [`get_image(self, options, image_size)`](/slides/python-net/zh/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | 返回具有指定大小的缩略图图像对象。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/slide/write_as_svg/#iorawiobase) | 将幻灯片内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将幻灯片内容保存为 SVG 文件。 |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/slide/equals/#ibaseslide) | 确定两个 IBaseSlide 实例是否相等。<br/>            返回值基于幻灯片的结构和静态内容计算。<br/>            当所有形状、样式、文本、动画和其他设置等均相等时，两个幻灯片被视为相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如日期占位符中的当前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/slide/create_theme_effective/#) | 返回此幻灯片的有效主题。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/slide/find_shape_by_alt_text/#str) | 查找具有指定替代文本的形状的第一次出现。 |
| [`write_as_emf(self, stream)`](/slides/python-net/zh/aspose.slides/slide/write_as_emf/#iorawiobase) | 将幻灯片内容保存为 EMF 文件。 |
| [`remove(self)`](/slides/python-net/zh/aspose.slides/slide/remove/#) | 从演示文稿中删除幻灯片。 |
| [`reset(self)`](/slides/python-net/zh/aspose.slides/slide/reset/#) | 重置在 LayoutSlide 上具有原型的每个形状的位置、大小和格式。 |
| [`get_slide_comments(self, author)`](/slides/python-net/zh/aspose.slides/slide/get_slide_comments/#icommentauthor) | 返回特定作者添加的所有幻灯片评论。 |

### 另见
* 类 [`BaseSlide`](/slides/python-net/zh/aspose.slides/baseslide)
* 类 [`Slide`](/slides/python-net/zh/aspose.slides/slide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)