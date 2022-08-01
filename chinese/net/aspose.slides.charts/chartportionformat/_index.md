---
title: ChartPortionFormat
second_title: Aspose.Slides for .NET API 参考
description: 此类包含图表中使用的图表部分格式属性 不像IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata 这个类的所有属性都是可写的
type: docs
weight: 1290
url: /zh/net/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat class

此类包含图表中使用的图表部分格式属性。 不像[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) 这个类的所有属性都是可写的。

```csharp
public class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 返回或设置替代语言的 ID。 读/写String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基本 IPresentationComponent 接口。 只读[`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 返回或设置复杂脚本字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 返回或设置东亚字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 返回文本 EffectFormat 属性。未应用继承。 只读[`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 返回或设置上标或下标文本。 值从 -100%（下标）到 100%（上标）。  **浮点数.NaN**表示值未定义，应从 Master 继承。 读/写Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 返回文本 FillFormat 属性。未应用继承。 只读[`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 确定字体是否为粗体。未应用继承。 读/写[`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 返回或设置部分的字体高度。  **浮点数.NaN**表示高度未定义，应从 Master 继承。 读/写Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 确定字体是否为斜体。未应用继承。 读/写[`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 返回或设置文本下划线类型。未应用继承。 读/写[`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 返回用于突出显示文本的颜色。未应用继承。 只读[`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 确定下划线样式是否有自己的 FillFormat 属性或继承自文本的 FillFormat 属性 。 读/写[`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 确定下划线样式是有自己的 LineFormat 属性还是继承自文本的 LineFormat 属性 读/写[`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 返回或设置最小字体大小，为此应打开字距调整。  **浮点数.NaN**表示值未定义，应从 Master 继承。 读/写Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 确定数字是否应忽略文本东方语言特定的垂直文本布局。未应用继承。 读/写[`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 返回或设置校对语言的 ID。用于检查拼写和语法。 读/写String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 返回或设置拉丁字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 返回文本轮廓的 LineFormat 属性。未应用继承。 只读[`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 确定是否应标准化文本的高度。未应用继承。 读/写[`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 确定是否不应校对文本。未应用继承。 读/写[`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 返回或设置字符间距增量。  **浮点数.NaN**表示值未定义，应从 Master 继承。 读/写Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 返回或设置文本的删除线类型。未应用继承。 读/写[`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 返回或设置符号字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 返回或设置文本大写的类型。未应用继承。 读/写[`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 返回下划线行的 FillFormat 属性。未应用继承。 只读[`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 返回用于勾画下划线的 LineFormat 属性。未应用继承。 只读[`ILineFormat`](../../aspose.slides/ilineformat). |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象比较。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希码。 |

### 评论

此类用于返回和操作为特定部分定义的文本部分formatting 属性。这意味着在获取值时 没有应用继承，因此对于大多数情况 您将获得表示“未定义”的值。

为了获得有效的格式化参数值包括 继承你需要使用[`GetEffective`](../../aspose.slides/portionformat/geteffective)method 返回一个[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)实例。

### 也可以看看

* class [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
