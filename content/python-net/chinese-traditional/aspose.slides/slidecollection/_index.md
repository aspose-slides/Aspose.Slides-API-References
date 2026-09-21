---
title: SlideCollection class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/slidecollection/
---
## SlideCollection 類別

表示投影片的集合。

SlideCollection 類型公開以下成員：

取得指定索引處的元素。  
唯讀 [`Slide`](/slides/python-net/zh-hant/aspose.slides/slide)。

## 索引器

| 名稱 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/slidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_clone/#islide) | 將指定投影片的副本新增至集合的末端。 |
| [`add_clone(self, source_slide, section)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_clone/#islide-isection) | 將指定投影片的副本新增至指定節的末端。 |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | 將指定投影片的副本新增至集合的末端。 |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | 將指定來源投影片的副本新增至集合的末端。<br/>            將自動從指定的主題中選取適當的版面配置（適當的版面配置是與來源投影片的版面配置具有相同 Type 或 Name 的版面配置）。如果沒有適當的版面配置，則會複製來源投影片的版面配置（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_clone/#int-islide) | 在集合的指定位置插入指定投影片的副本。 |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | 在集合的指定位置插入指定投影片的副本。 |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | 將指定來源投影片的副本插入至集合的指定位置。<br/>            將自動從指定的主題中選取適當的版面配置（適當的版面配置是與來源投影片的版面配置具有相同 Type 或 Name 的版面配置）。如果沒有適當的版面配置，則會複製來源投影片的版面配置（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/to_array/#) | 建立並傳回包含所有投影片的陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/to_array/#int-int) | 建立並傳回包含指定範圍內所有投影片的陣列。<br/>            第一張投影片的索引。要新增的投影片數量。 |
| [`reorder(self, index, slide)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/reorder/#int-islide) | 將投影片從集合中移動至指定位置。 |
| [`reorder(self, index, slides)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/reorder/#int-listislide) | 將投影片從集合中移動至指定位置。<br/>            投影片將從索引開始，依照在清單中的出現順序依序放置。 |
| [`add_from_pdf(self, path)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_from_pdf/#str) | 從 PDF 文件建立投影片，並將它們新增至集合的末端。 |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | 從 PDF 文件建立投影片，並考慮 pdf 匯入選項後將它們新增至集合的末端。 |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | 從 PDF 文件建立投影片，並將它們新增至集合的末端。 |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | 從 PDF 文件建立投影片，並將它們新增至集合的末端。 |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | 從 HTML 文字建立投影片，並將它們新增至集合的末端。 |
| [`add_from_html(self, html_text)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_from_html/#str) | 從 HTML 文字建立投影片，並將它們新增至集合的末端。 |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 從 HTML 文字建立投影片，並將它們新增至集合的末端。 |
| [`add_from_html(self, html_stream)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_from_html/#iorawiobase) | 從 HTML 文字建立投影片，並將它們新增至集合的末端。 |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_from_html/#int-str) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [`add_empty_slide(self, layout)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | 在集合末端新增一張空白投影片。 |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | 在集合的指定位置插入指定投影片的副本。 |
| [`remove(self, value)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/remove/#islide) | 從集合中移除特定物件的第一次出現。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/remove_at/#int) | 移除集合中指定索引處的元素。 |
| [`index_of(self, slide)`](/slides/python-net/zh-hant/aspose.slides/slidecollection/index_of/#islide) | 傳回集合中指定投影片的索引。 |

### 參見
* 類別 [`Slide`](/slides/python-net/zh-hant/aspose.slides/slide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)