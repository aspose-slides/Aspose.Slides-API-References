---
title: MasterNotesSlide class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/masternotesslide/
---
## MasterNotesSlide 類別

表示筆記的主投影片。

**繼承：**[`MasterNotesSlide`](/slides/python-net/zh-hant/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)

MasterNotesSlide 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/shapes/) | 傳回投影片的圖形。<br/>            唯讀 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/controls/) | 傳回投影片上 ActiveX 控制項的集合。<br/>            唯讀 [`IControlCollection`](/slides/python-net/zh-hant/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/name/) | 傳回或設定投影片的名稱。<br/>            讀/寫 **str**。 |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/slide_id/) | 傳回投影片的 ID。<br/>            唯讀 **int**。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/custom_data/) | 傳回投影片的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/timeline/) | 傳回動畫時間軸物件。<br/>            唯讀 [`IAnimationTimeLine`](/slides/python-net/zh-hant/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/slide_show_transition/) | 傳回 Transition 物件，其中包含有關<br/>            指定投影片在投影片放映期間如何前進的資訊。<br/>            唯讀 [`ISlideShowTransition`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/background/) | 傳回投影片的背景。<br/>            唯讀 [`IBackground`](/slides/python-net/zh-hant/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/hyperlink_queries/) | 提供對包含的超連結的簡易存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/show_master_shapes/) | 指定主投影片上的圖形是否應在投影片上顯示。<br/>            對於主投影片本身，此屬性始終傳回 `false`。<br/>            讀/寫 **bool**。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/presentation/) | 傳回 IPresentation 介面。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/header_footer_manager/) | 傳回主註記投影片的 HeaderFooter 管理器。<br/>            唯讀 [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/imasterhandoutslideheaderfootermanager)。 |
| [`theme_manager`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/theme_manager/) | 傳回佈景主題管理器。<br/>            唯讀 [`IMasterThemeManager`](/slides/python-net/zh-hant/aspose.slides.theme/imasterthememanager)。 |
| [`notes_style`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/notes_style/) | 傳回註記文字的樣式。<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle)。 |
| [`drawing_guides`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/drawing_guides/) | 傳回主註記投影片的繪圖指南集合。<br/>            唯讀 [`IDrawingGuidesCollection`](/slides/python-net/zh-hant/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/slide/) |  |
## 方法

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | 將所有可接受圖形中所有段落的相同格式的執行項合併。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | 將所有可接受圖形中所有段落的相同格式的執行項合併。 |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/equals/#ibaseslide) | 判斷兩個 IBaseSlide 實例是否相等。<br/>            傳回值是根據投影片的結構和靜態內容計算的。<br/>            若所有圖形、樣式、文字、動畫及其他設定等皆相等，則兩個投影片相等。比較不考慮唯一識別碼值，例如 SlideId，及動態內容，例如日期佔位符中的目前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/create_theme_effective/#) | 傳回此投影片的有效佈景主題。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | 尋找第一個具有指定替代文字的圖形。 |

### 另請參閱
* 類別 [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)
* 類別 [`MasterNotesSlide`](/slides/python-net/zh-hant/aspose.slides/masternotesslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)