---
title: IBulletFormat
second_title: Aspose.Sildes for .NET API Reference
description: 表示段落项目符号格式属性。
type: docs
weight: 5190
url: /zh/aspose.slides/ibulletformat/
---

## IBulletFormat 接口

表示段落项目符号格式属性。

```csharp
public interface IBulletFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Char](../../aspose.slides/ibulletformat/char) { get; set; } | 返回或设置没有继承的段落的项目符号字符。可读/可写 Char。 |
| [Color](../../aspose.slides/ibulletformat/color) { get; } | 返回没有继承的段落中项目符号的颜色格式。只读 [`IColorFormat`](../icolorformat)。 |
| [Font](../../aspose.slides/ibulletformat/font) { get; set; } | 返回或设置没有继承的段落的项目符号字体。可读/可写 [`IFontData`](../ifontdata)。 |
| [Height](../../aspose.slides/ibulletformat/height) { get; set; } | 返回或设置没有继承的段落的项目符号高度。值为 float.NaN 表示项目符号从段落中的第一个部分继承高度。可读/可写 Single。 |
| [IsBulletHardColor](../../aspose.slides/ibulletformat/isbullethardcolor) { get; set; } | 确定项目符号是否具有自己的颜色或从段落中第一个部分继承颜色。如果项目符号具有自己的颜色则为 **NullableBool.True**，如果项目符号从段落中的第一个部分继承颜色则为 **NullableBool.False**。可读/可写 [`NullableBool`](../nullablebool)。 |
| [IsBulletHardFont](../../aspose.slides/ibulletformat/isbullethardfont) { get; set; } | 确定项目符号是否具有自己的字体或从段落中第一个部分继承字体。如果项目符号具有自己的字体则为 **NullableBool.True**，如果项目符号从段落中的第一个部分继承字体则为 **NullableBool.False**。可读/可写 [`NullableBool`](../nullablebool)。 |
| [NumberedBulletStartWith](../../aspose.slides/ibulletformat/numberedbulletstartwith) { get; set; } | 返回或设置没有继承的编号项目符号组的第一个数字。可读/可写 Int16。 |
| [NumberedBulletStyle](../../aspose.slides/ibulletformat/numberedbulletstyle) { get; set; } | 返回或设置没有继承的编号项目符号的样式。可读/可写 [`NumberedBulletStyle`](./numberedbulletstyle)。 |
| [Picture](../../aspose.slides/ibulletformat/picture) { get; } | 返回没有继承的段落中作为项目符号使用的图片。只读 [`ISlidesPicture`](../islidespicture)。 |
| [Type](../../aspose.slides/ibulletformat/type) { get; set; } | 返回或设置没有继承的段落的项目符号类型。可读/可写 [`BulletType`](../bullettype)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ApplyDefaultParagraphIndentsShifts](../../aspose.slides/ibulletformat/applydefaultparagraphindentsshifts)() | 为启用项目符号时有效的段落缩进和左边距设置默认的非零偏移（就像 PowerPoint 启用段落项目符号/编号时那样）。如果禁用项目符号，则只需重置段落缩进和左边距（就像 PowerPoint 禁用段落项目符号/编号时那样）。缩进偏移是根据当前项目符号上下文 - IBulletFormat.Type、.NumberedBulletStyle 和第一个部分的 FontHeight 应用的。非零缩进偏移应用于当前段落的有效缩进和左边距（使结果值成为局部值）。 |
| [GetEffective](../../aspose.slides/ibulletformat/geteffective)() | 获取应用继承的有效项目符号格式数据。 |

### 参见

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->