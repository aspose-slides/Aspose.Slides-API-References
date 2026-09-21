---
title: ISlide class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/islide/
---
## ISlide 類別

表示簡報中的投影片。

ISlide 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/islide/header_footer_manager/) | 返回投影片的 HeaderFooter 管理器。<br/>            唯讀 [`ISlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/islideheaderfootermanager)。 |
| [`slide_number`](/slides/python-net/zh-hant/aspose.slides/islide/slide_number/) | 返回投影片的編號。<br/>            [`IPresentation.slides`](/slides/python-net/zh-hant/aspose.slides/ipresentation/slides) 集合中投影片的索引總是等於 SlideNumber - 1。<br/>            可讀寫 **int**。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/islide/hidden/) | 判斷指定的投影片在投影片放映期間是否被隱藏。<br/>            可讀寫 **bool**。 |
| [`layout_slide`](/slides/python-net/zh-hant/aspose.slides/islide/layout_slide/) | 返回或設定目前投影片的版面配置投影片。<br/>            可讀寫 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)。 |
| [`notes_slide_manager`](/slides/python-net/zh-hant/aspose.slides/islide/notes_slide_manager/) | 允許存取備註投影片，並可新增或移除。<br/>            唯讀 [`INotesSlideManager`](/slides/python-net/zh-hant/aspose.slides/inotesslidemanager)。 |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/zh-hant/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/zh-hant/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/zh-hant/aspose.slides/islide/theme_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/islide/get_image/#float-float) | 返回具有自訂縮放的圖像物件。 |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/islide/get_image/#) | 返回縮圖圖像物件（實際大小的 20%）。 |
| [`get_image(self, image_size)`](/slides/python-net/zh-hant/aspose.slides/islide/get_image/#asposepydrawingsize) | 返回具有指定尺寸的圖像物件。 |
| [`get_image(self, options)`](/slides/python-net/zh-hant/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | 返回具有指定參數的縮圖 TIFF 位圖物件。 |
| [`get_image(self, options)`](/slides/python-net/zh-hant/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | 返回縮圖位圖物件。 |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | 返回具有自訂縮放的縮圖位圖物件。 |
| [`get_image(self, options, image_size)`](/slides/python-net/zh-hant/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | 返回具有指定尺寸的縮圖位圖物件。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/islide/write_as_svg/#iorawiobase) | 將投影片內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將投影片內容儲存為 SVG 檔案。 |
| [`get_slide_comments(self, author)`](/slides/python-net/zh-hant/aspose.slides/islide/get_slide_comments/#icommentauthor) | 返回特定作者新增的所有投影片註解。 |
| [`write_as_emf(self, stream)`](/slides/python-net/zh-hant/aspose.slides/islide/write_as_emf/#iorawiobase) | 將投影片內容儲存為 EMF 檔案。 |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides/islide/remove/#) | 從簡報中移除投影片。 |
| [`reset(self)`](/slides/python-net/zh-hant/aspose.slides/islide/reset/#) | 重設在 LayoutSlide 上具有原型的每個圖形的位置、尺寸和格式。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/islide/create_theme_effective/#) |  |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)