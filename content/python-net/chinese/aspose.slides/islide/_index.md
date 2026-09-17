---
title: ISlide class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islide/
---
## ISlide 类

表示演示文稿中的幻灯片。

ISlide 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/zh/aspose.slides/islide/header_footer_manager/) | 返回幻灯片的 HeaderFooter 管理器。<br/>            只读 [`ISlideHeaderFooterManager`](/slides/python-net/zh/aspose.slides/islideheaderfootermanager)。 |
| [`slide_number`](/slides/python-net/zh/aspose.slides/islide/slide_number/) | 返回幻灯片的编号。<br/>            在 [`IPresentation.slides`](/slides/python-net/zh/aspose.slides/ipresentation/slides) 集合中的索引始终等于 SlideNumber - 1。<br/>            可读写 **int**。 |
| [`hidden`](/slides/python-net/zh/aspose.slides/islide/hidden/) | 确定在幻灯片放映期间指定的幻灯片是否隐藏。<br/>            可读写 **bool**。 |
| [`layout_slide`](/slides/python-net/zh/aspose.slides/islide/layout_slide/) | 返回或设置当前幻灯片的布局幻灯片。<br/>            可读写 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)。 |
| [`notes_slide_manager`](/slides/python-net/zh/aspose.slides/islide/notes_slide_manager/) | 允许访问备注幻灯片，添加和删除它。<br/>            只读 [`INotesSlideManager`](/slides/python-net/zh/aspose.slides/inotesslidemanager)。 |
| [`shapes`](/slides/python-net/zh/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/zh/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/zh/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/zh/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/zh/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/zh/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/zh/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/zh/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/zh/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/zh/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/zh/aspose.slides/islide/theme_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/islide/get_image/#float-float) | 返回具有自定义缩放的图像对象。 |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/islide/get_image/#) | 返回缩略图图像对象（实际大小的 20%）。 |
| [`get_image(self, image_size)`](/slides/python-net/zh/aspose.slides/islide/get_image/#asposepydrawingsize) | 返回具有指定大小的图像对象。 |
| [`get_image(self, options)`](/slides/python-net/zh/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | 返回具有指定参数的缩略图 TIFF 位图对象。 |
| [`get_image(self, options)`](/slides/python-net/zh/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | 返回缩略图位图对象。 |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | 返回具有自定义缩放的缩略图位图对象。 |
| [`get_image(self, options, image_size)`](/slides/python-net/zh/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | 返回具有指定大小的缩略图位图对象。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/islide/write_as_svg/#iorawiobase) | 将幻灯片内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将幻灯片内容保存为 SVG 文件。 |
| [`get_slide_comments(self, author)`](/slides/python-net/zh/aspose.slides/islide/get_slide_comments/#icommentauthor) | 返回特定作者添加的所有幻灯片批注。 |
| [`write_as_emf(self, stream)`](/slides/python-net/zh/aspose.slides/islide/write_as_emf/#iorawiobase) | 将幻灯片内容保存为 EMF 文件。 |
| [`remove(self)`](/slides/python-net/zh/aspose.slides/islide/remove/#) | 从演示文稿中移除幻灯片。 |
| [`reset(self)`](/slides/python-net/zh/aspose.slides/islide/reset/#) | 重置在 LayoutSlide 上具有原型的每个形状的位置、大小和格式。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/zh/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides/islide/create_theme_effective/#) |  |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)