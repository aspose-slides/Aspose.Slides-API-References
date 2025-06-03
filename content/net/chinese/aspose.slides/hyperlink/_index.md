---
title: Hyperlink
second_title: Aspose.Slides for .NET API 参考
description: 表示一个超链接。
type: docs
weight: 4920
url: /zh/aspose.slides/hyperlink/
---

## Hyperlink 类

表示一个超链接。

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | 创建指向特定幻灯片的超链接实例。注意：创建的超链接应分配给同一演示文稿中的某个对象，否则链接将被保存为 NoAction。 |
| [Hyperlink](hyperlink#constructor_2)(string) | 创建一个超链接实例。 |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | 使用另一个超链接作为源创建超链接实例，并覆盖次要属性。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | 返回结束演示的超链接。只读 [`Hyperlink`](../hyperlink)。 |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | 返回指向演示文稿中第一张幻灯片的超链接。只读 [`Hyperlink`](../hyperlink)。 |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | 返回指向演示文稿中最后一张幻灯片的超链接。只读 [`Hyperlink`](../hyperlink)。 |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | 返回指向最后查看的幻灯片的超链接。只读 [`Hyperlink`](../hyperlink)。 |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | 返回一个特殊的“播放媒体文件”超链接。用于 AudioFrame 和 VideoFrame。只读 [`Hyperlink`](../hyperlink)。 |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | 返回指向下一张幻灯片的超链接。只读 [`Hyperlink`](../hyperlink)。 |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | 返回一个特殊的“无操作”超链接。只读 [`Hyperlink`](../hyperlink)。 |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | 返回指向上一张幻灯片的超链接。只读 [`Hyperlink`](../hyperlink)。 |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | 返回超链接的操作类型。只读 [`HyperlinkActionType`](../hyperlinkactiontype)。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基础 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | 表示超链接颜色的来源 - 可以是样式或部分格式。读/写 [`HyperlinkColorSource`](../hyperlinkcolorsource)。 |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | 指定外部 URL。只读字符串。 |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | 表示为该部分设置的超链接，不考虑该部分的实际内容。PowerPoint 对于链接及其对应文本在部分中的行为特定。它允许以有效 URL 的形式为超链接创建文本，不同于链接的真实地址。在这种情况下，当您在编辑窗口查看链接时，它将被更改以匹配文本部分。此属性表示超链接的原始值。 |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | 决定超链接在点击时是否应突出显示。读/写布尔值。 |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | 决定父级超链接被调用时其目标是否应添加到已查看超链接列表中。读/写布尔值。 |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | 表示超链接播放的声音。读/写 [`IAudio`](../iaudio)。 |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | 决定在超链接点击时声音是否应停止。读/写布尔值。 |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | 返回父级 HTML frameset 中的目标超链接框架（如果存在）。读/写字符串。 |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | 如果超链接目标是特定幻灯片，则返回该幻灯片。只读 [`ISlide`](../islide)。 |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | 返回可能在用户界面中作为与父级超链接关联的字符串。读/写字符串。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | 确定两个 Hyperlink 实例是否相等。 |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | 确定两个 Hyperlink 实例是否相等。 |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | 作为特定类型的哈希函数，可用于哈希算法和数据结构，如哈希表。 |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | 检测两个超链接是否相等。 |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | 检测两个超链接是否不相等。 |

### 另请参阅

* 类 [PVIObject](../pviobject)
* 接口 [IHyperlink](../ihyperlink)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)