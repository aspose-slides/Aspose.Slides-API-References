---
title: MasterHandoutSlide class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide 類別

表示用於講義的母版投影片。

**繼承:**[`MasterHandoutSlide`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)

MasterHandoutSlide 類型會公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/shapes/) | 傳回投影片的形狀。<br/>            唯讀 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/controls/) | 傳回投影片上 ActiveX 控制項的集合。<br/>            唯讀 [`IControlCollection`](/slides/python-net/zh-hant/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/name/) | 傳回或設定投影片的名稱。<br/>            可讀寫 **str**。 |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/slide_id/) | 傳回投影片的 ID。<br/>            唯讀 **int**。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/custom_data/) | 傳回投影片的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/timeline/) | 傳回動畫時間軸物件。<br/>            唯讀 [`IAnimationTimeLine`](/slides/python-net/zh-hant/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/slide_show_transition/) | 傳回 Transition 物件，其中包含有關指定投影片在投影片放映期間如何前進的資訊。<br/>            唯讀 [`ISlideShowTransition`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/background/) | 傳回投影片的背景。<br/>            唯讀 [`IBackground`](/slides/python-net/zh-hant/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/hyperlink_queries/) | 提供對內含超連結的便利存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/show_master_shapes/) | 指定母版投影片上的形狀是否應該在投影片上顯示。<br/>            對於母版投影片本身，此屬性總是傳回 `false`。<br/>            可讀寫 **bool**。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/presentation/) | 傳回 IPresentation 介面。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/header_footer_manager/) | 傳回母版講義投影片的 HeaderFooter 管理器。<br/>            唯讀 [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/imasterhandoutslideheaderfootermanager)。 |
| [`theme_manager`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/theme_manager/) | 傳回佈景主題管理器。<br/>            唯讀 [`IMasterThemeManager`](/slides/python-net/zh-hant/aspose.slides.theme/imasterthememanager)。 |
| [`drawing_guides`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/drawing_guides/) | 傳回母版講義投影片的繪圖參考線集合。<br/>            唯讀 [`IDrawingGuidesCollection`](/slides/python-net/zh-hant/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/slide/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | 在所有段落的所有可接受形狀中，合併具有相同格式的執行序。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | 在所有可接受形狀的所有段落中，合併具有相同格式的執行序。 |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/equals/#ibaseslide) | 判斷兩個 IBaseSlide 實例是否相等。<br/>            回傳值是根據投影片的結構和靜態內容計算的。<br/>            若所有形狀、樣式、文字、動畫及其他設定等皆相等，則兩張投影片相等。比較不會考慮唯一識別碼的值，例如 SlideId，亦不考慮動態內容，例如日期佔位符中的當前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/create_theme_effective/#) | 傳回此投影片的有效佈景主題。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | 尋找首次出現具指定替代文字的形狀。 |

### 另請參閱
* 類別 [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)
* 類別 [`MasterHandoutSlide`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)