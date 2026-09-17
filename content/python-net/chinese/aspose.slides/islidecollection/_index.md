---
title: ISlideCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islidecollection/
---
## ISlideCollection 类

表示一组幻灯片。

ISlideCollection 类型公开以下成员：

Gets the element at the specified index.
            只读 [`ISlide`](/slides/python-net/zh/aspose.slides/islide).

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/islidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/zh/aspose.slides/islidecollection/add_clone/#islide) | 将指定幻灯片的副本添加到集合的末尾。 |
| [`add_clone(self, source_slide, section)`](/slides/python-net/zh/aspose.slides/islidecollection/add_clone/#islide-isection) | 将指定幻灯片的副本添加到指定节的末尾。 |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/zh/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | 将指定幻灯片的副本添加到集合的末尾。 |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/zh/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | 将指定源幻灯片的副本添加到集合的末尾。<br/>            将自动从指定的 <br/>            主版中选择合适的布局（合适的布局是具有相同 Type 或 Name 的布局）。如果没有合适的布局，则<br/>            将克隆源幻灯片的布局（如果 allowCloneMissingLayout <br/>            为 true）或抛出 PptxEditException（如果 allowCloneMissingLayout<br/>            为 false）。 |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_clone/#int-islide) | 将指定幻灯片的副本插入到集合的指定位置。 |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | 将指定幻灯片的副本插入到集合的指定位置。 |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | 将指定源幻灯片的副本插入到集合的指定位置。<br/>            将自动从指定的 <br/>            主版中选择合适的布局（合适的布局是具有相同 Type 或 Name 的布局）。如果没有合适的布局，则<br/>            将克隆源幻灯片的布局（如果 allowCloneMissingLayout <br/>            为 true）或抛出 PptxEditException（如果 allowCloneMissingLayout<br/>            为 false）。 |
| [`to_array(self)`](/slides/python-net/zh/aspose.slides/islidecollection/to_array/#) | 创建并返回包含所有幻灯片的数组。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh/aspose.slides/islidecollection/to_array/#int-int) | 创建并返回包含指定范围内所有幻灯片的数组。 |
| [`reorder(self, index, slide)`](/slides/python-net/zh/aspose.slides/islidecollection/reorder/#int-islide) | 将幻灯片从集合移动到指定位置。 |
| [`reorder(self, index, slides)`](/slides/python-net/zh/aspose.slides/islidecollection/reorder/#int-listislide) | 将幻灯片从集合移动到指定位置。<br/>            幻灯片将从索引开始按在列表中出现的顺序放置。 |
| [`add_from_pdf(self, path)`](/slides/python-net/zh/aspose.slides/islidecollection/add_from_pdf/#str) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/zh/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | 从 PDF 文档创建幻灯片并根据 PDF 导入选项将其添加到集合的末尾。 |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/zh/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/zh/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/zh/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_html(self, html_text)`](/slides/python-net/zh/aspose.slides/islidecollection/add_from_html/#str) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/zh/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [`add_from_html(self, html_stream)`](/slides/python-net/zh/aspose.slides/islidecollection/add_from_html/#iorawiobase) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_from_html/#int-str) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [`add_empty_slide(self, layout)`](/slides/python-net/zh/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | 向集合的末尾添加一个新的空幻灯片。 |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/zh/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | 将指定幻灯片的副本插入到集合的指定位置。 |
| [`remove(self, value)`](/slides/python-net/zh/aspose.slides/islidecollection/remove/#islide) | 从集合中移除特定对象的第一次出现。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/islidecollection/remove_at/#int) | 移除集合中指定索引处的元素。 |
| [`index_of(self, slide)`](/slides/python-net/zh/aspose.slides/islidecollection/index_of/#islide) | 返回指定幻灯片在集合中的索引。 |


### 另见
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)