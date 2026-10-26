---
title: IHyperlink class
second_title: Aspose.Slides 用於 Python 之 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ihyperlink/
---
## IHyperlink 類別

表示一個超連結。

IHyperlink 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`action_type`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/action_type/) | 回傳 HyperLinkEx 動作的類型。<br/>            唯讀 [`HyperlinkActionType`](/slides/python-net/zh-hant/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/external_url/) | 指定外部 URL<br/>            若此屬性不為 None，則屬性 TargetSlide 會變為 None。<br/>            唯讀 **str**. |
| [`external_url_original`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/external_url_original/) | 代表為此部分設定的超連結，且不考慮該部分的實際內容。<br/>            <br/>            PowerPoint 會對部分中的連結及其對應文字有特定的處理方式。它允許以有效的 URL 形式為超連結建立文字，該文字可與實際連結位址不同。在此情況下，當您在編輯視窗中檢視連結時，會自動變更以符合文字部分。此屬性代表超連結的原始值。 |
| [`target_slide`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/target_slide/) | 如果 HyperlinkEx 目標為特定投影片，則回傳該投影片。<br/>            若此屬性不為 None，則屬性 ExternalUrl 會變為 None。<br/>            唯讀 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/target_frame/) | 回傳父 HTML frameset 中目標的框架（若存在）。<br/>            可讀寫 **str**. |
| [`tooltip`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/tooltip/) | 回傳可能在使用者介面中顯示的字串，與父超連結相關聯。<br/>            可讀寫 **str**. |
| [`history`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/history/) | 決定在觸發時是否將父超連結的目標加入已檢視超連結清單。<br/>            可讀寫 **bool**. |
| [`highlight_click`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/highlight_click/) | 決定在點擊時是否將超連結標示為已選取。<br/>            可讀寫 **bool**. |
| [`stop_sound_on_click`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/stop_sound_on_click/) | 決定在點擊超連結時是否停止聲音。<br/>            可讀寫 **bool**. |
| [`sound`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/sound/) | 代表超連結的播放音效。<br/>            可讀寫 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/color_source/) | 代表超連結顏色的來源——樣式或部分格式。<br/>            可讀寫 [`HyperlinkColorSource`](/slides/python-net/zh-hant/aspose.slides/hyperlinkcolorsource). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/zh-hant/aspose.slides/ihyperlink/equals/#ihyperlink) | 判斷兩個 Hyperlink 實例是否相等。 |


### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)