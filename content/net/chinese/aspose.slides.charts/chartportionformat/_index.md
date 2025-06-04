---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: 该类包含在图表中使用的图表部分格式属性。与 IPortionFormatEffectiveDataaspose.slides/aspose.slides/iportionformateffectivedata 不同，该类的所有属性都是可写的。
type: docs
weight: 1350
url: /zh/aspose.slides.charts/chartportionformat/
---

## ChartPortionFormat class

该类包含在图表中使用的图表部分格式属性。与 [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) 不同，该类的所有属性都是可写的。

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Properties

| 名称 | 描述 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 返回或设置替代语言的 Id。可读写字符串。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基础 IPresentationComponent 接口。只读 [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent)。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 返回或设置复杂脚本字体信息。空值表示字体未定义，应从主版继承。可读写 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 返回或设置东亚字体信息。空值表示字体未定义，应从主版继承。可读写 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 返回文本 EffectFormat 属性。没有应用继承。只读 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 返回或设置上标或下标文本。值从 -100%（下标）到 100%（上标）。**float.NaN** 表示值未定义，应从主版继承。可读写单一值。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 返回文本 FillFormat 属性。没有应用继承。只读 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 确定字体是否为粗体。没有应用继承。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 返回或设置部分的字体高度。**float.NaN** 表示高度未定义，应从主版继承。可读写单一值。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 确定字体是否为斜体。没有应用继承。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 返回或设置文本下划线类型。没有应用继承。可读写 [`TextUnderlineType`](../../aspose.slides/textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 返回用于突出显示文本的颜色。没有应用继承。只读 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 确定下划线样式是否具有自己的 FillFormat 属性或从文本的 FillFormat 属性继承。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 确定下划线样式是否具有自己的 LineFormat 属性或从文本的 LineFormat 属性继承。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 返回或设置应开启字符间距调整的最小字体大小。**float.NaN** 表示值未定义，并应从主版继承。可读写单一值。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 确定数字是否应忽略东亚语言特有的垂直文本布局。没有应用继承。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 返回或设置校对语言的 Id。用于检查拼写和语法。可读写字符串。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 返回或设置拉丁字体信息。空值表示字体未定义，应从主版继承。可读写 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 返回文本轮廓的 LineFormat 属性。没有应用继承。只读 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 确定文本的高度是否应被标准化。没有应用继承。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 确定文本是否不应进行拼写检查。没有应用继承。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 返回或设置字符间距增量。**float.NaN** 表示值未定义，并应从主版继承。可读写单一值。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 返回或设置文本的删除线类型。没有应用继承。可读写 [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 返回或设置符号字体信息。空值表示字体未定义，并应从主版继承。可读写 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 返回或设置文本大写类型。没有应用继承。可读写 [`TextCapType`](../../aspose.slides/textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 返回下划线线条的 FillFormat 属性。没有应用继承。只读 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 返回用于轮廓下划线线条的 LineFormat 属性。没有应用继承。只读 [`ILineFormat`](../../aspose.slides/ilineformat)。 |

## Methods

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象进行比较。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希代码。 |

### Remarks

该类用于返回和操作为特定部分定义的文本部分格式属性。这意味着在获取值时没有应用继承，因此在大多数情况下，您将获得“未定义”的值。

要获取包括继承在内的有效格式参数值，您需要使用 [`GetEffective`](../../aspose.slides/portionformat/geteffective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) 实例。

### See Also

* class [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->