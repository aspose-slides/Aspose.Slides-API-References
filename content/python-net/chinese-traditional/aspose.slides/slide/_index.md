---
title: Slide class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/slide/
---
## Slide 類別

代表簡報中的一張投影片。

**繼承:**[`Slide`](/slides/python-net/zh-hant/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)

Slide 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/slide/shapes/) | 返回投影片的形狀。<br/>            唯讀 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/slide/controls/) | 返回投影片上 ActiveX 控制項的集合。<br/>            唯讀 [`IControlCollection`](/slides/python-net/zh-hant/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/slide/name/) | 返回或設定投影片的名稱。<br/>            可讀寫 **str**。 |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/slide/slide_id/) | 返回投影片的 ID。<br/>            唯讀 **int**。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/slide/custom_data/) | 返回投影片的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/slide/timeline/) | 返回動畫時間軸物件。<br/>            唯讀 [`IAnimationTimeLine`](/slides/python-net/zh-hant/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/slide/slide_show_transition/) | 返回 Transition 物件，其中包含有關指定投影片在投影播放期間如何前進的資訊。<br/>            唯讀 [`ISlideShowTransition`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh-hant/aspose.slides/slide/background/) | 返回投影片的背景。<br/>            唯讀 [`IBackground`](/slides/python-net/zh-hant/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/slide/hyperlink_queries/) | 提供對內含超連結的簡易存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/slide/show_master_shapes/) | 指定母片上的形狀是否應顯示在投影片上。<br/>            可讀寫 **bool**。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/slide/presentation/) | 返回 IPresentation 介面。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/slide/header_footer_manager/) | 返回投影片的 HeaderFooter 管理器。<br/>            唯讀 [`ISlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/islideheaderfootermanager)。 |
| [`theme_manager`](/slides/python-net/zh-hant/aspose.slides/slide/theme_manager/) | 返回覆寫的佈景主題管理器。<br/>            唯讀 [`IOverrideThemeManager`](/slides/python-net/zh-hant/aspose.slides.theme/ioverridethememanager)。 |
| [`slide_number`](/slides/python-net/zh-hant/aspose.slides/slide/slide_number/) | 返回投影片的編號。<br/>            [`Presentation.slides`](/slides/python-net/zh-hant/aspose.slides/presentation/slides) 集合中的投影片索引始終等於 SlideNumber - Presentation.FirstSlideNumber。<br/>            可讀寫 **int**。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/slide/hidden/) | 確定指定投影片在播放時是否隱藏。<br/>            可讀寫 **bool**。 |
| [`layout_slide`](/slides/python-net/zh-hant/aspose.slides/slide/layout_slide/) | 返回或設定目前投影片的版面配置投影片。<br/>            可讀寫 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)。 |
| [`notes_slide_manager`](/slides/python-net/zh-hant/aspose.slides/slide/notes_slide_manager/) | 允許存取備註投影片，新增或移除。<br/>            唯讀 [`INotesSlideManager`](/slides/python-net/zh-hant/aspose.slides/inotesslidemanager)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/slide/slide/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/slide/join_portions_with_same_formatting/#) | 在所有可接受的形狀的所有段落中，合併具有相同格式的執行區。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh-hant/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | 在所有可接受的形狀的所有段落中，合併具有相同格式的執行區。 |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/slide/get_image/#float-float) | 返回具有自訂縮放的縮圖影像物件。 |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/slide/get_image/#) | 返回縮圖影像物件（實際大小的 20%）。 |
| [`get_image(self, image_size)`](/slides/python-net/zh-hant/aspose.slides/slide/get_image/#asposeslidessize) | 返回具有指定大小的縮圖影像物件。 |
| [`get_image(self, options)`](/slides/python-net/zh-hant/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | 返回具有指定參數的縮圖 TIFF 影像物件。 |
| [`get_image(self, options)`](/slides/python-net/zh-hant/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | 返回縮圖影像物件。 |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | 返回具有自訂縮放的縮圖影像物件。 |
| [`get_image(self, options, image_size)`](/slides/python-net/zh-hant/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | 返回具有指定大小的縮圖影像物件。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/slide/write_as_svg/#iorawiobase) | 將投影片內容另存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將投影片內容另存為 SVG 檔案。 |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/slide/equals/#ibaseslide) | 判斷兩個 IBaseSlide 實例是否相等。<br/>            回傳值基於投影片的結構與靜態內容計算。<br/>            若所有形狀、樣式、文字、動畫及其他設定等全部相等，則兩張投影片相等。比較不會考慮唯一識別碼值，例如 SlideId，亦不考慮動態內容，例如日期佔位符中的當前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/slide/create_theme_effective/#) | 返回此投影片的有效佈景主題。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/slide/find_shape_by_alt_text/#str) | 尋找具有指定替代文字的形狀的第一次出現。 |
| [`write_as_emf(self, stream)`](/slides/python-net/zh-hant/aspose.slides/slide/write_as_emf/#iorawiobase) | 將投影片內容另存為 EMF 檔案。 |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides/slide/remove/#) | 從簡報中移除投影片。 |
| [`reset(self)`](/slides/python-net/zh-hant/aspose.slides/slide/reset/#) | 重設在 LayoutSlide 上具有原型的每個形狀的位置、大小與格式。 |
| [`get_slide_comments(self, author)`](/slides/python-net/zh-hant/aspose.slides/slide/get_slide_comments/#icommentauthor) | 返回特定作者新增的所有投影片評論。 |

### 另見
* 類別 [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)
* 類別 [`Slide`](/slides/python-net/zh-hant/aspose.slides/slide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)