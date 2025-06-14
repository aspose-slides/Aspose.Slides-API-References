---
title: ParagraphFormat
second_title: Aspose.Sildes for .NET API Reference
description: 该类包含段落格式属性。与 IParagraphFormatEffectiveData../iparagraphformateffectivedata 不同，这个类的所有属性都是可写的。
type: docs
weight: 9040
url: /zh/aspose.slides/paragraphformat/
---

## ParagraphFormat class

该类包含段落格式属性。与 [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) 不同，这个类的所有属性都是可写的。

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | 初始化 [`ParagraphFormat`](../paragraphformat) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | 返回或设置段落中的文本对齐方式，并不继承。读/写 [`TextAlignment`](../textalignment)。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基本的 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | 返回或设置默认制表符大小，并不继承。读/写 Single。 |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | 确定段落中是否使用东亚换行符。没有应用继承。读/写 [`NullableBool`](../nullablebool)。 |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | 返回或设置段落中的字体对齐方式，并不继承。读/写 [`FontAlignment`](../fontalignment)。 |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | 确定段落中是否使用悬挂标点。没有应用继承。读/写 [`NullableBool`](../nullablebool)。 |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | 返回或设置段落的首行缩进/悬挂缩进，并不继承。悬挂缩进可以用负值定义。读/写 Single。 |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | 确定段落中是否使用拉丁换行符。没有应用继承。读/写 [`NullableBool`](../nullablebool)。 |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | 返回或设置段落的左边距，并不继承。读/写 Single。 |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | 返回或设置段落的右边距，并不继承。读/写 Single。 |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | 确定段落中是否使用从右到左的书写方式。没有应用继承。读/写 [`NullableBool`](../nullablebool)。 |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | 返回或设置段落最后一行之后的空白量，并不继承。正值指定空白应占字体大小的百分比。负值指定空白的点大小。读/写 Single。 |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | 返回或设置段落第一行之前的空白量，并不继承。正值指定空白应占字体大小的百分比。负值指定空白的点大小。读/写 Single。 |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | 返回或设置段落基线之间的空白量。正值表示百分比，负值表示点数大小。没有应用继承。读/写 Single。 |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | 返回段落的制表符。没有应用继承。只读 [`ITabCollection`](../itabcollection)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定的对象进行比较。 |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | 获取有效的段落格式数据，并应用继承。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希码。 |

### 备注

该类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时没有应用继承，因此在大多数情况下，您将获得表示“未定义”的值。

为了获取包括继承的有效格式参数值，您需要使用 [`GetEffective`](./geteffective) 方法，该方法返回一个 [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) 实例。

### 另见

* 类 [PVIObject](../pviobject)
* 接口 [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* 接口 [IParagraphFormat](../iparagraphformat)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->