---
title: IHyperlink class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ihyperlink/
---
## IHyperlink 类

Represents a hyperlink.

The IHyperlink type exposes the following members:

## 属性

| 属性 | 描述 |
| :- | :- |
| [`action_type`](/slides/python-net/zh/aspose.slides/ihyperlink/action_type/) | 返回 HyperLinkEx 动作的类型。<br/>            只读 [`HyperlinkActionType`](/slides/python-net/zh/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/zh/aspose.slides/ihyperlink/external_url/) | 指定外部 URL<br/>            如果此属性不为 None，则属性 TargetSlide 为 None。<br/>            只读 **str**. |
| [`external_url_original`](/slides/python-net/zh/aspose.slides/ihyperlink/external_url_original/) | 表示为此部分设置的超链接，而不考虑该部分的实际内容。<br/>            <br/>            PowerPoint 对部分中的链接及其相应文本有特定行为。它允许以有效 URL 的形式为超链接创建文本，该 URL 与链接的真实地址不同。在这种情况下，当您在编辑窗口中查看链接时，它将被更改以匹配文本部分。此属性表示超链接的原始值. |
| [`target_slide`](/slides/python-net/zh/aspose.slides/ihyperlink/target_slide/) | 如果 HyperlinkEx 目标为特定幻灯片，则返回该幻灯片。<br/>            如果此属性不为 None，则属性 ExternalUrl 为 None。<br/>            只读 [`ISlide`](/slides/python-net/zh/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/zh/aspose.slides/ihyperlink/target_frame/) | 返回父 HTML 框架集中父超链接目标所在的框架（如果存在）。<br/>            读/写 **str**. |
| [`tooltip`](/slides/python-net/zh/aspose.slides/ihyperlink/tooltip/) | 返回可在用户界面中显示的字符串，用于关联父超链接。<br/>            读/写 **str**. |
| [`history`](/slides/python-net/zh/aspose.slides/ihyperlink/history/) | 确定在调用时是否将父超链接的目标添加到已查看超链接的列表中。<br/>            读/写 **bool**. |
| [`highlight_click`](/slides/python-net/zh/aspose.slides/ihyperlink/highlight_click/) | 确定点击时是否应突出显示超链接。<br/>            读/写 **bool**. |
| [`stop_sound_on_click`](/slides/python-net/zh/aspose.slides/ihyperlink/stop_sound_on_click/) | 确定在点击超链接时是否应停止声音。<br/>            读/写 **bool**. |
| [`sound`](/slides/python-net/zh/aspose.slides/ihyperlink/sound/) | 表示超链接的播放声音。<br/>            读/写 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/zh/aspose.slides/ihyperlink/color_source/) | 表示超链接颜色的来源——样式或部分格式。<br/>            读/写 [`HyperlinkColorSource`](/slides/python-net/zh/aspose.slides/hyperlinkcolorsource). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/zh/aspose.slides/ihyperlink/equals/#ihyperlink) | 确定两个 Hyperlink 实例是否相等. |


### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)