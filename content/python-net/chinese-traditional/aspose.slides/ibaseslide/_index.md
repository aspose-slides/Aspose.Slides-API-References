---
title: IBaseSlide class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ibaseslide/
---
## IBaseSlide class

表示所有投影片類型的共用資料。

IBaseSlide 類型公開下列成員：

## Properties

| 屬性 | 說明 |
| :- | :- |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/shapes/) | 返回投影片的圖形。<br/>            唯讀 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/controls/) | 返回投影片上 ActiveX 控制元件的集合。<br/>            唯讀 [`IControlCollection`](/slides/python-net/zh-hant/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/name/) | 返回或設定投影片的名稱。<br/>            可讀寫 **str**。 |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/slide_id/) | 返回投影片的 ID。<br/>            唯讀 **int**。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/custom_data/) | 返回投影片的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/timeline/) | 返回動畫時間軸物件。<br/>            唯讀 [`IAnimationTimeLine`](/slides/python-net/zh-hant/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/slide_show_transition/) | 返回 TransitionEx 物件，該物件包含有關<br/>            指定投影片在投影片放映期間如何前進的資訊。<br/>            唯讀 [`ISlideShowTransition`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/background/) | 返回投影片的背景。<br/>            唯讀 [`IBackground`](/slides/python-net/zh-hant/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/hyperlink_queries/) | 提供對包含之超連結的簡易存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/show_master_shapes/) | 指定母投影片上的圖形是否應在投影片上顯示。<br/>            對於母投影片本身，此屬性始終返回 `false`。<br/>            可讀寫 **bool**。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/presentation/) |  |

## Methods

| 方法 | 說明 |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | 尋找第一個具有指定替代文字的圖形。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | 在所有可接受的圖形中，將具有相同格式的 Run 合併於所有段落。 |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/equals/#ibaseslide) | 判斷兩個 IBaseSlide 實例是否相等。<br/>            返回值根據投影片的結構和靜態內容計算。<br/>            如果所有圖形、樣式、文字、動畫及其他設定等皆相等，則兩個投影片相等。比較不考慮唯一識別碼值，例如 SlideId，以及動態內容，例如日期佔位符中的當前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/ibaseslide/create_theme_effective/#) |  |


### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)