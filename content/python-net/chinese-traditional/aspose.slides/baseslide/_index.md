---
title: BaseSlide class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/baseslide/
---
## BaseSlide 類別

表示所有投影片類型的通用資料。

BaseSlide 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/baseslide/shapes/) | 傳回投影片的圖形。<br/>            唯讀 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/baseslide/controls/) | 傳回投影片上的 ActiveX 控制項集合。<br/>            唯讀 [`IControlCollection`](/slides/python-net/zh-hant/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/baseslide/name/) | 傳回或設定投影片的名稱。<br/>            可讀寫 **str**。 |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/baseslide/slide_id/) | 傳回投影片的 ID。<br/>            唯讀 **int**。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/baseslide/custom_data/) | 傳回投影片的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/baseslide/timeline/) | 傳回動畫時間軸物件。<br/>            唯讀 [`IAnimationTimeLine`](/slides/python-net/zh-hant/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/baseslide/slide_show_transition/) | 傳回 Transition 物件，其中包含有關<br/>            指定投影片在投影片放映期間如何前進的資訊。<br/>            唯讀 [`ISlideShowTransition`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/zh-hant/aspose.slides/baseslide/background/) | 傳回投影片的背景。<br/>            唯讀 [`IBackground`](/slides/python-net/zh-hant/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/baseslide/hyperlink_queries/) | 提供對內含超連結的簡易存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/baseslide/show_master_shapes/) | 指定母片上的圖形是否應顯示於投影片上。<br/>            對於母片本身，此屬性永遠傳回 `false`。<br/>            可讀寫 **bool**。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/baseslide/presentation/) | 傳回 IPresentation 介面。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/baseslide/slide/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/baseslide/join_portions_with_same_formatting/#) | 合併所有可接受圖形中所有段落中格式相同的 runs。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh-hant/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | 合併所有可接受圖形中所有段落中格式相同的 runs。 |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/baseslide/equals/#ibaseslide) | 判斷兩個 IBaseSlide 實例是否相等。<br/>            傳回值基於投影片的結構與靜態內容計算。<br/>            若所有圖形、樣式、文字、動畫及其他設定等均相等，則兩投影片相等。比較時不考慮唯一識別碼值，例如 SlideId，亦不考慮動態內容，例如日期佔位元中的目前日期值。 |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/baseslide/create_theme_effective/#) | 傳回此投影片的有效主題。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/baseslide/find_shape_by_alt_text/#str) | 尋找第一個具有指定替代文字的圖形。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)