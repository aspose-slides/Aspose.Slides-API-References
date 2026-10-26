---
title: Hyperlink class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/hyperlink/
---
## Hyperlink 类

表示一个超链接。

**继承:**[`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

Hyperlink 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/zh/aspose.slides/hyperlink/__init__/#str) | 创建一个超链接的实例。 |
| [`__init__(self, slide)`](/slides/python-net/zh/aspose.slides/hyperlink/__init__/#islide) | 创建一个指向特定幻灯片的超链接实例。<br/>            注：创建的超链接应分配给同一演示文稿中的某个对象，否则链接将被保存为 NoAction。 |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/zh/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | 使用另一个超链接作为源创建超链接实例，覆盖次要属性。 |

## 属性

| Property | Description |
| :- | :- |
| [`no_action`](/slides/python-net/zh/aspose.slides/hyperlink/no_action/) | 返回一个特殊的 “do nothing” 超链接。<br/>            只读 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)。 |
| [`media`](/slides/python-net/zh/aspose.slides/hyperlink/media/) | 返回一个特殊的 “play mediafile” 超链接。用于 AudioFrame 和 VideoFrame。<br/>            只读 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)。 |
| [`next_slide`](/slides/python-net/zh/aspose.slides/hyperlink/next_slide/) | 返回指向下一张幻灯片的超链接。<br/>            只读 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)。 |
| [`previous_slide`](/slides/python-net/zh/aspose.slides/hyperlink/previous_slide/) | 返回指向上一张幻灯片的超链接。<br/>            只读 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)。 |
| [`first_slide`](/slides/python-net/zh/aspose.slides/hyperlink/first_slide/) | 返回指向演示文稿第一张幻灯片的超链接。<br/>            只读 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)。 |
| [`last_slide`](/slides/python-net/zh/aspose.slides/hyperlink/last_slide/) | 返回指向演示文稿最后一张幻灯片的超链接。<br/>            只读 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)。 |
| [`last_vieved_slide`](/slides/python-net/zh/aspose.slides/hyperlink/last_vieved_slide/) | 返回指向最近查看的幻灯片的超链接。<br/>            只读 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)。 |
| [`end_show`](/slides/python-net/zh/aspose.slides/hyperlink/end_show/) | 返回结束演示的超链接。<br/>            只读 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)。 |
| [`action_type`](/slides/python-net/zh/aspose.slides/hyperlink/action_type/) | 返回 Hyperlink 动作的类型。<br/>            只读 [`HyperlinkActionType`](/slides/python-net/zh/aspose.slides/hyperlinkactiontype)。 |
| [`external_url`](/slides/python-net/zh/aspose.slides/hyperlink/external_url/) | 指定外部 URL。<br/>            只读 **str**。 |
| [`target_slide`](/slides/python-net/zh/aspose.slides/hyperlink/target_slide/) | 如果 Hyperlink 指向特定幻灯片，则返回该幻灯片。<br/>            只读 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)。 |
| [`external_url_original`](/slides/python-net/zh/aspose.slides/hyperlink/external_url_original/) | 表示为该部分设置的超链接，而不考虑该部分的实际内容。<br/>            <br/>            PowerPoint 对链接及其对应的文本在同一部分中有特定的行为。它允许以有效 URL 的形式创建超链接文本，与链接的真实地址不同。在这种情况下，当你在编辑窗口中查看链接时，它将被更改为匹配文本部分。此属性表示超链接的原始值。 |
| [`target_frame`](/slides/python-net/zh/aspose.slides/hyperlink/target_frame/) | 返回父 HTML frameset 中目标的框架（当父超链接存在时）。<br/>            可读/可写 **str**。 |
| [`tooltip`](/slides/python-net/zh/aspose.slides/hyperlink/tooltip/) | 返回可能在用户界面中显示的字符串，作为与父超链接关联的内容。<br/>            可读/可写 **str**。 |
| [`history`](/slides/python-net/zh/aspose.slides/hyperlink/history/) | 确定在调用时是否将父超链接的目标添加到已查看超链接列表中。<br/>            可读/可写 **bool**。 |
| [`highlight_click`](/slides/python-net/zh/aspose.slides/hyperlink/highlight_click/) | 确定在点击时是否应突出显示超链接。<br/>            可读/可写 **bool**。 |
| [`stop_sound_on_click`](/slides/python-net/zh/aspose.slides/hyperlink/stop_sound_on_click/) | 确定在点击超链接时是否应停止声音。<br/>            可读/可写 **bool**。 |
| [`sound`](/slides/python-net/zh/aspose.slides/hyperlink/sound/) | 表示超链接的播放声音。<br/>            可读/可写 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio)。 |
| [`color_source`](/slides/python-net/zh/aspose.slides/hyperlink/color_source/) | 表示超链接颜色的来源——样式或部分格式。<br/>            可读/可写 [`HyperlinkColorSource`](/slides/python-net/zh/aspose.slides/hyperlinkcolorsource)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/hyperlink/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/zh/aspose.slides/hyperlink/equals/#ihyperlink) | 确定两个 Hyperlink 实例是否相等。 |

### 另见
* 类 [`Hyperlink`](/slides/python-net/zh/aspose.slides/hyperlink)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)