---
title: BulletFormat
second_title: Aspose.Sildes for .NET API Reference
description: 表示段落的项目符号格式属性。
type: docs
weight: 990
url: /zh/aspose.slides/bulletformat/
---

## BulletFormat class

表示段落的项目符号格式属性。

```csharp
public sealed class BulletFormat : PVIObject, IBulletFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基本的 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [Char](../../aspose.slides/bulletformat/char) { get; set; } | 返回或设置段落的项目符号字符，不继承。可读写 Char。 |
| [Color](../../aspose.slides/bulletformat/color) { get; } | 返回段落项目符号的颜色格式，不继承。只读 [`IColorFormat`](../icolorformat)。 |
| [Font](../../aspose.slides/bulletformat/font) { get; set; } | 返回或设置段落的项目符号字体，不继承。可读写 [`IFontData`](../ifontdata)。 |
| [Height](../../aspose.slides/bulletformat/height) { get; set; } | 返回或设置段落的项目符号高度，不继承。值 float.NaN 表示项目符号从段落的第一个部分继承高度。可读写 Single。 |
| [IsBulletHardColor](../../aspose.slides/bulletformat/isbullethardcolor) { get; set; } | 确定项目符号是否具有自己的颜色，或从段落的第一个部分继承颜色。如果项目符号具有自己的颜色，则为 **NullableBool.True**，如果从段落的第一个部分继承颜色，则为 **NullableBool.False**。可读写 [`NullableBool`](../nullablebool)。 |
| [IsBulletHardFont](../../aspose.slides/bulletformat/isbullethardfont) { get; set; } | 确定项目符号是否具有自己的字体，或从段落的第一个部分继承字体。如果项目符号具有自己的字体，则为 **NullableBool.True**，如果从段落的第一个部分继承字体，则为 **NullableBool.False**。可读写 [`NullableBool`](../nullablebool)。 |
| [NumberedBulletStartWith](../../aspose.slides/bulletformat/numberedbulletstartwith) { get; set; } | 返回或设置未继承的编号项目符号的起始数字。可读写 Int16。 |
| [NumberedBulletStyle](../../aspose.slides/bulletformat/numberedbulletstyle) { get; set; } | 返回或设置未继承的编号项目符号的样式。可读写 [`NumberedBulletStyle`](../numberedbulletstyle)。 |
| [Picture](../../aspose.slides/bulletformat/picture) { get; } | 返回作为段落中的项目符号使用的图片，不继承。只读 [`ISlidesPicture`](../islidespicture)。 |
| [Type](../../aspose.slides/bulletformat/type) { get; set; } | 返回或设置段落的项目符号类型，不继承。可读写 [`BulletType`](../bullettype)。 |

## Methods

| Name | Description |
| --- | --- |
| [ApplyDefaultParagraphIndentsShifts](../../aspose.slides/bulletformat/applydefaultparagraphindentsshifts)() | 在启用项目符号时（如 PowerPoint 在启用段落项目符号/编号时所做的那样），设置有效段落缩进和 MarginLeft 的默认非零偏移量。如果禁用项目符号，则仅重置段落缩进和 MarginLeft（如 PowerPoint 在禁用段落项目符号/编号时所做的那样）。缩进偏移量是在考虑当前项目符号上下文的情况下应用的 - IBulletFormat.Type、.NumberedBulletStyle 和第一个部分的 FontHeight。非零缩进偏移量应用于当前段落的有效缩进和 MarginLeft（使结果值成为本地值）。 |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象进行比较。 |
| [GetEffective](../../aspose.slides/bulletformat/geteffective)() | 获取应用继承的有效项目符号格式数据。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希代码。 |

### See Also

* class [PVIObject](../pviobject)
* interface [IBulletFormat](../ibulletformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->