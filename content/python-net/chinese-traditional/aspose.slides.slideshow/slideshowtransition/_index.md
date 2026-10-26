---
title: SlideShowTransition class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition 類別

表示投影片放映過渡效果。

SlideShowTransition 類型會公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`sound`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/sound/) | 取得或設定嵌入的音訊資料。<br/>            讀寫 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio)。 |
| [`sound_mode`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/sound_mode/) | 設定或取得投影片過渡的聲音模式。<br/>            讀寫 [`TransitionSoundMode`](/slides/python-net/zh-hant/aspose.slides.slideshow/transitionsoundmode)。 |
| [`sound_loop`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/sound_loop/) | 此屬性指定聲音是否會循環，直至下一個聲音事件在投影片放映中發生。<br/>            讀寫 **bool**。 |
| [`advance_on_click`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | 指定滑鼠點擊是否會前進投影片。若未指定此屬性，則假設值為 true。<br/>            讀寫 **bool**。 |
| [`advance_after`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/advance_after/) | 此屬性指定投影片放映是否會在特定時間後切換到下一張投影片。<br/>            讀寫 **bool**。 |
| [`advance_after_time`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | 指定過渡應開始的時間（以毫秒為單位）。此設定可與 advClick 屬性一起使用。若未指定此屬性，則假設不會自動前進。<br/>            讀寫 **int**。 |
| [`speed`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/speed/) | 指定從目前投影片過渡到下一張投影片時使用的過渡速度。<br/>            讀寫 [`TransitionSpeed`](/slides/python-net/zh-hant/aspose.slides.slideshow/transitionspeed)。 |
| [`value`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/value/) | 投影片放映過渡值。<br/>            唯讀 [`ITransitionValueBase`](/slides/python-net/zh-hant/aspose.slides.slideshow/itransitionvaluebase)。 |
| [`type`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/type/) | 過渡類型。<br/>            讀寫 [`TransitionType`](/slides/python-net/zh-hant/aspose.slides.slideshow/transitiontype)。 |
| [`sound_is_built_in`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | 指定此聲音是否為內建聲音。若此屬性設為 true，則會提示產生應用程式檢查此聲音在內建聲音清單中指定的 name 屬性，並可根據需要顯示自訂名稱或介面。<br/>            讀寫 **bool**。 |
| [`sound_name`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/sound_name/) | 指定過渡聲音的人類可讀名稱。必須指派 [`SlideShowTransition.sound`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/sound) 屬性才能取得或設定聲音名稱。<br/>            讀寫 **str**。 |
| [`duration`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/duration/) | 取得或設定投影片過渡效果的持續時間（以毫秒為單位）。<br/>            讀寫 **int**。 |

### 另見
* 模組 [`aspose.slides.slideshow`](/slides/python-net/zh-hant/aspose.slides.slideshow)
* 函式庫 [`Aspose.Slides`](/slides/python-net)