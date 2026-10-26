---
title: Hyperlink class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/hyperlink/
---
## Hyperlink 類別

表示一個超連結。

**Inheritance:**[`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)

Hyperlink 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/zh-hant/aspose.slides/hyperlink/__init__/#str) | 建立 Hyperlink 實例。 |
| [`__init__(self, slide)`](/slides/python-net/zh-hant/aspose.slides/hyperlink/__init__/#islide) | 建立指向特定投影片的 Hyperlink 實例。<br/>            注意：建立的超連結應指派給同一簡報中的某個物件，否則連結將儲存為 NoAction。 |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/zh-hant/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | 使用另一個 Hyperlink 作為來源，覆寫次要屬性，建立 Hyperlink 實例。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`no_action`](/slides/python-net/zh-hant/aspose.slides/hyperlink/no_action/) | 傳回特殊的「不執行任何操作」超連結。<br/>            唯讀 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)。 |
| [`media`](/slides/python-net/zh-hant/aspose.slides/hyperlink/media/) | 傳回特殊的「播放媒體檔案」超連結。用於 AudioFrame 和 VideoFrame。<br/>            唯讀 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)。 |
| [`next_slide`](/slides/python-net/zh-hant/aspose.slides/hyperlink/next_slide/) | 傳回指向下一張投影片的超連結。<br/>            唯讀 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)。 |
| [`previous_slide`](/slides/python-net/zh-hant/aspose.slides/hyperlink/previous_slide/) | 傳回指向前一張投影片的超連結。<br/>            唯讀 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)。 |
| [`first_slide`](/slides/python-net/zh-hant/aspose.slides/hyperlink/first_slide/) | 傳回指向簡報第一張投影片的超連結。<br/>            唯讀 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)。 |
| [`last_slide`](/slides/python-net/zh-hant/aspose.slides/hyperlink/last_slide/) | 傳回指向簡報最後一張投影片的超連結。<br/>            唯讀 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)。 |
| [`last_vieved_slide`](/slides/python-net/zh-hant/aspose.slides/hyperlink/last_vieved_slide/) | 傳回指向最後檢視的投影片的超連結。<br/>            唯讀 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)。 |
| [`end_show`](/slides/python-net/zh-hant/aspose.slides/hyperlink/end_show/) | 傳回結束簡報的超連結。<br/>            唯讀 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)。 |
| [`action_type`](/slides/python-net/zh-hant/aspose.slides/hyperlink/action_type/) | 傳回 Hyperlink 動作的類型。<br/>            唯讀 [`HyperlinkActionType`](/slides/python-net/zh-hant/aspose.slides/hyperlinkactiontype)。 |
| [`external_url`](/slides/python-net/zh-hant/aspose.slides/hyperlink/external_url/) | 指定外部 URL。<br/>            唯讀 **str**。 |
| [`target_slide`](/slides/python-net/zh-hant/aspose.slides/hyperlink/target_slide/) | 如果 Hyperlink 目標為特定投影片，則傳回該投影片。<br/>            唯讀 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)。 |
| [`external_url_original`](/slides/python-net/zh-hant/aspose.slides/hyperlink/external_url_original/) | 表示對此區段設定的超連結，且不考慮該區段的實際內容。<br/>            <br/>            PowerPoint 對於區段中連結及其相應文字有特殊行為。它允許以有效的 URL 形式建立超連結文字，與連結的實際位址不同。在此情況下，當您在編輯視窗中檢視連結時，它會被更改為符合文字區段。此屬性表示超連結的原始值。 |
| [`target_frame`](/slides/python-net/zh-hant/aspose.slides/hyperlink/target_frame/) | 傳回父 HTML frameset 中針對目標的框架<br/>            （當父超連結存在時）。<br/>            可讀寫 **str**。 |
| [`tooltip`](/slides/python-net/zh-hant/aspose.slides/hyperlink/tooltip/) | 傳回可能在使用者介面中顯示的字串<br/>            ，作為與父超連結相關聯的資訊。<br/>            可讀寫 **str**。 |
| [`history`](/slides/python-net/zh-hant/aspose.slides/hyperlink/history/) | 決定在呼叫父超連結時，是否將其目標加入已檢視超連結清單。<br/>            可讀寫 **bool**。 |
| [`highlight_click`](/slides/python-net/zh-hant/aspose.slides/hyperlink/highlight_click/) | 決定點擊時是否將超連結以高亮方式顯示。<br/>            可讀寫 **bool**。 |
| [`stop_sound_on_click`](/slides/python-net/zh-hant/aspose.slides/hyperlink/stop_sound_on_click/) | 決定點擊超連結時是否停止聲音。<br/>            可讀寫 **bool**。 |
| [`sound`](/slides/python-net/zh-hant/aspose.slides/hyperlink/sound/) | 表示超連結播放的聲音。<br/>            可讀寫 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio)。 |
| [`color_source`](/slides/python-net/zh-hant/aspose.slides/hyperlink/color_source/) | 表示超連結顏色的來源 ─ 樣式或區段格式。<br/>            可讀寫 [`HyperlinkColorSource`](/slides/python-net/zh-hant/aspose.slides/hyperlinkcolorsource)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/hyperlink/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/zh-hant/aspose.slides/hyperlink/equals/#ihyperlink) | 判斷兩個 Hyperlink 實例是否相等。 |


### 另請參閱
* 類別 [`Hyperlink`](/slides/python-net/zh-hant/aspose.slides/hyperlink)
* 類別 [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)