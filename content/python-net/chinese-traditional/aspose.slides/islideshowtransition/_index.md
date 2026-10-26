---
title: ISlideShowTransition class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/islideshowtransition/
---
## ISlideShowTransition 類別

表示投影片放映過渡效果。

The ISlideShowTransition type exposes the following members:
## 屬性

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/sound/) | Returns or sets the embedded audio data.<br/>            讀寫 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/sound_mode/) | Set or returns sound mode for slide transition.<br/>            讀寫 [`TransitionSoundMode`](/slides/python-net/zh-hant/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/sound_loop/) | This attribute specifies if the sound will loop until the next sound event occurs in<br/>            slideshow.<br/>            讀寫 **bool**. |
| [`advance_on_click`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/advance_on_click/) | Specifies whether a mouse click will advance the slide or not. If this attribute is not<br/>            specified then a value of true is assumed.<br/>            讀寫 **bool**. |
| [`advance_after`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/advance_after/) | This attribute specifies if the slideshow will move to the next slide after a certain time.<br/>            讀寫 **bool**. |
| [`advance_after_time`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/advance_after_time/) | Specifies the time, in milliseconds, after which the transition should start. This setting<br/>            may be used in conjunction with the advClick attribute. If this attribute is not specified<br/>            then it is assumed that no auto-advance will occur.<br/>            讀寫 **int**. |
| [`speed`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/speed/) | Specifies the transition speed that is to be used when transitioning from the current slide<br/>            to the next.<br/>            讀寫 [`TransitionSpeed`](/slides/python-net/zh-hant/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/value/) | Slide show transition value.<br/>            唯讀 [`ITransitionValueBase`](/slides/python-net/zh-hant/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/type/) | Type of transition.<br/>            讀寫 [`TransitionType`](/slides/python-net/zh-hant/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/sound_is_built_in/) | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then<br/>            the generating application is alerted to check the name attribute specified for this sound<br/>            in it's list of built-in sounds and can then surface a custom name or UI as needed.<br/>            讀寫 **bool**. |
| [`sound_name`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/sound_name/) | Specifies a human readable name for the sound of the transition. The [`ISlideShowTransition.sound`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/sound) property must be assigned to get or set the sound name.<br/>            讀寫 **str**. |
| [`duration`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/duration/) | Gets or sets the duration of the slide transition effect in milliseconds.<br/>            讀寫 **int**. |


### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)