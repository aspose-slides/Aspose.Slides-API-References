---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API 参考
description: 此类包含在图表中使用的图表部分格式属性。与 IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata 不同，本类的所有属性均可写。
type: docs
weight: 1430
url: /zh/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat 类

此类包含在图表中使用的图表部分格式属性。与 [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) 不同，本类的所有属性均可写。

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 返回或设置替代语言的 Id。读/写 String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基础 IPresentationComponent 接口。只读 [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent)。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 返回或设置复杂脚本字体信息。Null 表示字体未定义，应从母版继承。读/写 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 返回或设置东亚字体信息。Null 表示字体未定义，应从母版继承。读/写 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 返回文本 EffectFormat 属性。未应用继承。只读 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 返回或设置上标或下标文本。值范围为 -100%（下标）至 100%（上标）。**float.NaN** 表示值未定义，应从母版继承。读/写 Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 返回文本 FillFormat 属性。未应用继承。只读 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 确定字体是否为粗体。未应用继承。读/写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 返回或设置部分的字体高度。**float.NaN** 表示高度未定义，应从母版继承。读/写 Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 确定字体是否为斜体。未应用继承。读/写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 返回或设置文本下划线类型。未应用继承。读/写 [`TextUnderlineType`](../../aspose.slides/textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 返回用于突出显示文本的颜色。未应用继承。只读 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 确定下划线样式是否拥有自己的 FillFormat 属性，或从文本的 FillFormat 属性继承。读/写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 确定下划线样式是否拥有自己的 LineFormat 属性，或从文本的 LineFormat 属性继承。读/写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 返回或设置开启字距调整所需的最小字体大小。**float.NaN** 表示值未定义，应从母版继承。读/写 Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 确定数字是否应忽略文本的东亚特定垂直布局。未应用继承。读/写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 返回或设置校对语言的 Id。用于拼写和语法检查。读/写 String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 返回或设置拉丁字体信息。Null 表示字体未定义，应从母版继承。读/写 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 返回文本轮廓的 LineFormat 属性。未应用继承。只读 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 确定文本的高度是否应归一化。未应用继承。读/写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 确定文本是否不进行校对。未应用继承。读/写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 返回或设置字符间距增量。**float.NaN** 表示值未定义，应从母版继承。读/写 Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | 获取或设置一个值，指示是否为文本部分启用拼写检查。当此属性设置为 false 时，文本元素的拼写检查被抑制。设置为 true 时，允许拼写检查。默认值为 `false`。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 返回或设置文本的删除线类型。未应用继承。读/写 [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 返回或设置符号字体信息。Null 表示字体未定义，应从母版继承。读/写 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 返回或设置文本大小写类型。未应用继承。读/写 [`TextCapType`](../../aspose.slides/textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 返回下划线线条的 FillFormat 属性。未应用继承。只读 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 返回用于勾勒下划线线条的 LineFormat 属性。未应用继承。只读 [`ILineFormat`](../../aspose.slides/ilineformat)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象进行比较。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希码。 |

### 备注

此类用于返回和操作为特定部分定义的文本部分格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，需要使用 [`GetEffective`](../../aspose.slides/portionformat/geteffective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) 实例。

### 另见

* 类 [BasePortionFormat](../../aspose.slides/baseportionformat)
* 接口 [IChartPortionFormat](../ichartportionformat)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->