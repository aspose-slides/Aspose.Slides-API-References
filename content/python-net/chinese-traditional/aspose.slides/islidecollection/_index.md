---
title: ISlideCollection class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/islidecollection/
---
## ISlideCollection 類別

表示投影片的集合。

ISlideCollection 類型公開以下成員：

取得指定索引處的元素。  
唯讀 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)。

## 索引子

| 名稱 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/islidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_clone/#islide) | 在集合的末尾加入指定投影片的副本。 |
| [`add_clone(self, source_slide, section)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_clone/#islide-isection) | 在指定區段的末尾加入指定投影片的副本。 |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | 在集合的末尾加入指定投影片的副本。 |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | 在集合的末尾加入指定來源投影片的副本。<br/>            會自動從指定的母片中選取適當的版面配置（適當的版面配置是具有與來源投影片相同類型或名稱的版面配置）。如果沒有適當的版面配置，則會複製來源投影片的版面配置（如果 allowCloneMissingLayout 為 true）或拋出 PptxEditException（如果 allowCloneMissingLayout 為 false）。 |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_clone/#int-islide) | 在集合的指定位置插入指定投影片的副本。 |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | 在集合的指定位置插入指定投影片的副本。 |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | 在集合的指定位置插入指定來源投影片的副本。<br/>            會自動從指定的母片中選取適當的版面配置（適當的版面配置是具有與來源投影片相同類型或名稱的版面配置）。如果沒有適當的版面配置，則會複製來源投影片的版面配置（如果 allowCloneMissingLayout 為 true）或拋出 PptxEditException（如果 allowCloneMissingLayout 為 false）。 |
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/to_array/#) | 建立並傳回包含所有投影片的陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/to_array/#int-int) | 建立並傳回包含指定範圍內所有投影片的陣列。 |
| [`reorder(self, index, slide)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/reorder/#int-islide) | 將投影片從集合中移動到指定位置。 |
| [`reorder(self, index, slides)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/reorder/#int-listislide) | 將投影片從集合中移動到指定位置。<br/>            投影片將從索引開始，以清單中出現的順序放置。 |
| [`add_from_pdf(self, path)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_from_pdf/#str) | 從 PDF 文件建立投影片，並將其加入集合的末尾。 |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | 根據 PDF 匯入選項，從 PDF 文件建立投影片，並將其加入集合的末尾。 |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | 從 PDF 文件建立投影片，並將其加入集合的末尾。 |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | 從 PDF 文件建立投影片，並將其加入集合的末尾。 |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | 從 HTML 文字建立投影片，並將其加入集合的末尾。 |
| [`add_from_html(self, html_text)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_from_html/#str) | 從 HTML 文字建立投影片，並將其加入集合的末尾。 |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 從 HTML 文字建立投影片，並將其加入集合的末尾。 |
| [`add_from_html(self, html_stream)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_from_html/#iorawiobase) | 從 HTML 文字建立投影片，並將其加入集合的末尾。 |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_from_html/#int-str) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [`add_empty_slide(self, layout)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | 在集合的末尾加入一個新的空白投影片。 |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | 在集合的指定位置插入指定投影片的副本。 |
| [`remove(self, value)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/remove/#islide) | 從集合中移除特定物件的第一次出現。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/remove_at/#int) | 移除集合中指定索引處的元素。 |
| [`index_of(self, slide)`](/slides/python-net/zh-hant/aspose.slides/islidecollection/index_of/#islide) | 傳回集合中指定投影片的索引。 |

### 另請參閱
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)