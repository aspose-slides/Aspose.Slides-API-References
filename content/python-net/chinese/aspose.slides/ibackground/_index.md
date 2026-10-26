---
title: IBackground class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/ibackground/
---
## IBackground 类

表示幻灯片的背景。

IBackground 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/zh/aspose.slides/ibackground/type/) | Returns a type of background fill.<br/>            读取/写入 [`BackgroundType`](/slides/python-net/zh/aspose.slides/backgroundtype). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/ibackground/fill_format/) | Returns a FillFormat for BackgroundType.OwnBackground fill.<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/ibackground/effect_format/) | Returns a EffectFormat for BackgroundType.OwnBackground fill.<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`style_color`](/slides/python-net/zh/aspose.slides/ibackground/style_color/) | Returns a ColorFormat for a BackgroundType.Themed fill.<br/>            只读 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat). |
| [`style_index`](/slides/python-net/zh/aspose.slides/ibackground/style_index/) | Returns an index of BackgroundType.Themed fill in background theme collection.<br/>            0 表示无填充。<br/>            1..999 - 索引。<br/>            读取/写入 **int**. |
| [`slide`](/slides/python-net/zh/aspose.slides/ibackground/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/ibackground/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/ibackground/get_effective/#) | 获取应用继承后的有效背景数据。 |


### 参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)