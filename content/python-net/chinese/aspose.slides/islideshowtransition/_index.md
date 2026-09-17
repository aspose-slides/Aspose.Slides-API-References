---
title: ISlideShowTransition class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islideshowtransition/
---
## ISlideShowTransition 类

表示幻灯片放映过渡。

ISlideShowTransition 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`sound`](/slides/python-net/zh/aspose.slides/islideshowtransition/sound/) | 返回或设置嵌入的音频数据。<br/>            读写 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio)。 |
| [`sound_mode`](/slides/python-net/zh/aspose.slides/islideshowtransition/sound_mode/) | 设置或返回幻灯片过渡的声音模式。<br/>            读写 [`TransitionSoundMode`](/slides/python-net/zh/aspose.slides.slideshow/transitionsoundmode)。 |
| [`sound_loop`](/slides/python-net/zh/aspose.slides/islideshowtransition/sound_loop/) | 此属性指定声音是否会循环，直到在幻灯片放映中出现下一个声音事件。<br/>            读写 **bool**。 |
| [`advance_on_click`](/slides/python-net/zh/aspose.slides/islideshowtransition/advance_on_click/) | 指定鼠标点击是否会前进到下一张幻灯片。如果未指定此属性，则假设其值为 true。<br/>            读写 **bool**。 |
| [`advance_after`](/slides/python-net/zh/aspose.slides/islideshowtransition/advance_after/) | 此属性指定幻灯片放映是否会在一定时间后移动到下一张幻灯片。<br/>            读/写 **bool**。 |
| [`advance_after_time`](/slides/python-net/zh/aspose.slides/islideshowtransition/advance_after_time/) | 指定过渡应在多少毫秒后开始。此设置可与 advClick 属性一起使用。如果未指定此属性，则假定不会自动前进。<br/>            读写 **int**。 |
| [`speed`](/slides/python-net/zh/aspose.slides/islideshowtransition/speed/) | 指定从当前幻灯片过渡到下一张幻灯片时使用的过渡速度。<br/>            读写 [`TransitionSpeed`](/slides/python-net/zh/aspose.slides.slideshow/transitionspeed)。 |
| [`value`](/slides/python-net/zh/aspose.slides/islideshowtransition/value/) | 幻灯片放映过渡值。<br/>            只读 [`ITransitionValueBase`](/slides/python-net/zh/aspose.slides.slideshow/itransitionvaluebase)。 |
| [`type`](/slides/python-net/zh/aspose.slides/islideshowtransition/type/) | 过渡的类型。<br/>            读写 [`TransitionType`](/slides/python-net/zh/aspose.slides.slideshow/transitiontype)。 |
| [`sound_is_built_in`](/slides/python-net/zh/aspose.slides/islideshowtransition/sound_is_built_in/) | 指定此声音是否为内置声音。如果此属性设为 true，则会提示生成应用检查此声音在其内置声音列表中指定的 name 属性，并可根据需要显示自定义名称或 UI。<br/>            读写 **bool**。 |
| [`sound_name`](/slides/python-net/zh/aspose.slides/islideshowtransition/sound_name/) | 指定过渡声音的人类可读名称。必须为 [`ISlideShowTransition.sound`](/slides/python-net/zh/aspose.slides/islideshowtransition/sound) 属性赋值才能获取或设置声音名称。<br/>            读写 **str**。 |
| [`duration`](/slides/python-net/zh/aspose.slides/islideshowtransition/duration/) | 获取或设置幻灯片过渡效果的持续时间（毫秒）。<br/>            读/写 **int**。 |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)