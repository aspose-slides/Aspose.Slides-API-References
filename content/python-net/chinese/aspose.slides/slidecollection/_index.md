---
title: SlideCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/slidecollection/
---
## SlideCollection 类

表示幻灯片的集合。

SlideCollection 类型公开以下成员：

获取指定索引处的元素。  
只读 [`Slide`](/slides/python-net/zh/aspose.slides/slide)。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/slidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/zh/aspose.slides/slidecollection/add_clone/#islide) | 将指定幻灯片的副本添加到集合的末尾。 |
| [`add_clone(self, source_slide, section)`](/slides/python-net/zh/aspose.slides/slidecollection/add_clone/#islide-isection) | 将指定幻灯片的副本添加到指定章节的末尾。 |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/zh/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | 将指定幻灯片的副本添加到集合的末尾。 |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/zh/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | 将指定源幻灯片的副本添加到集合的末尾。<br/>            将自动从指定的<br/>            母版中选择适当的布局（适当的布局是与源幻灯片的布局具有相同 Type 或 Name 的布局）。如果没有适当的布局，则<br/>            将克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true）或抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_clone/#int-islide) | 将指定幻灯片的副本插入集合的指定位置。 |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | 将指定幻灯片的副本插入集合的指定位置。 |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | 将指定源幻灯片的副本插入集合的指定位置。<br/>            将自动从指定的<br/>            母版中选择适当的布局（适当的布局是与源幻灯片的布局具有相同 Type 或 Name 的布局）。如果没有适当的布局，则<br/>            将克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true）或抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |
| [`to_array(self)`](/slides/python-net/zh/aspose.slides/slidecollection/to_array/#) | 创建并返回包含所有幻灯片的数组。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh/aspose.slides/slidecollection/to_array/#int-int) | 创建并返回一个数组，包含指定范围内的所有幻灯片。<br/>            第一个要添加的幻灯片的索引。要添加的幻灯片数量。 |
| [`reorder(self, index, slide)`](/slides/python-net/zh/aspose.slides/slidecollection/reorder/#int-islide) | 将幻灯片从集合中移动到指定位置。 |
| [`reorder(self, index, slides)`](/slides/python-net/zh/aspose.slides/slidecollection/reorder/#int-listislide) | 将幻灯片从集合中移动到指定位置。<br/>            幻灯片将从索引开始按它们在列表中出现的顺序放置。 |
| [`add_from_pdf(self, path)`](/slides/python-net/zh/aspose.slides/slidecollection/add_from_pdf/#str) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/zh/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | 根据 PDF 导入选项，从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/zh/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/zh/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/zh/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_html(self, html_text)`](/slides/python-net/zh/aspose.slides/slidecollection/add_from_html/#str) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/zh/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_html(self, html_stream)`](/slides/python-net/zh/aspose.slides/slidecollection/add_from_html/#iorawiobase) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | 从 HTML 文本创建幻灯片并将其插入集合的指定位置。 |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | 从 HTML 文本创建幻灯片并将其插入集合的指定位置。 |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_from_html/#int-str) | 从 HTML 文本创建幻灯片并将其插入集合的指定位置。 |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | 从 HTML 文本创建幻灯片并将其插入集合的指定位置。 |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 从 HTML 文本创建幻灯片并将其插入集合的指定位置。 |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | 从 HTML 文本创建幻灯片并将其插入集合的指定位置。 |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | 从 HTML 文本创建幻灯片并将其插入集合的指定位置。 |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | 从 HTML 文本创建幻灯片并将其插入集合的指定位置。 |
| [`add_empty_slide(self, layout)`](/slides/python-net/zh/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | 在集合的末尾添加一个新的空白幻灯片。 |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/zh/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | 将指定幻灯片的副本插入集合的指定位置。 |
| [`remove(self, value)`](/slides/python-net/zh/aspose.slides/slidecollection/remove/#islide) | 从集合中移除特定对象的第一次出现。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/slidecollection/remove_at/#int) | 移除集合中指定索引处的元素。 |
| [`index_of(self, slide)`](/slides/python-net/zh/aspose.slides/slidecollection/index_of/#islide) | 返回指定幻灯片在集合中的索引。 |

### 另见
* 类 [`Slide`](/slides/python-net/zh/aspose.slides/slide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)