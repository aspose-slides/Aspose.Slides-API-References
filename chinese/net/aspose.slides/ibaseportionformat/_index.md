---
title: IBasePortionFormat
second_title: Aspose.Slides for .NET API 参考
description: 此类包含文本部分格式属性与IPortionFormatEffectiveData./iportionformateffectivedata不同此类的所有属性都是可写的
type: docs
weight: 4830
url: /zh/net/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

此类包含文本部分格式属性。与[`IPortionFormatEffectiveData`](../iportionformateffectivedata)不同，此类的所有属性都是可写的。

```csharp
public interface IBasePortionFormat
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | 返回或设置替代语言的 ID。 读/写String。 |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | 返回或设置复杂的脚本字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | 返回或设置东亚字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | 返回文本 EffectFormat 属性。未应用继承。 只读[`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | 返回或设置上标或下标文本。 值从 -100%（下标）到 100%（上标）。  **float.NaN** 表示值未定义，应从 Master 继承。 读/写Single。 |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | 返回文本 FillFormat 属性。未应用继承。 只读[`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | 确定字体是否为粗体。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | 返回或设置部分的字体高度。  **float.NaN** 表示高度未定义，应从 Master 继承。 读/写Single。 |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | 确定字体是否为斜体。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | 返回或设置文本下划线类型。未应用继承。 读/写[`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | 返回用于突出显示文本的颜色。未应用继承。 只读[`IColorFormat`](../icolorformat)。 |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | 确定下划线样式是否有自己的 FillFormat 属性或从文本的 FillFormat 属性继承 。 读/写[`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | 确定下划线样式是否具有自己的 LineFormat 属性或从文本的 LineFormat 属性继承 。 读/写[`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | 返回或设置最小字体大小，为此应打开字距调整。  **float.NaN** 表示值未定义，应从 Master 继承。 读/写Single。 |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | 确定数字是否应忽略文本东方语言特定的垂直文本布局。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | 返回或设置校对语言的 ID。用于检查拼写和语法。 读/写String。 |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | 返回或设置拉丁字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | 返回文本轮廓的 LineFormat 属性。未应用继承。 只读[`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | 确定文本的高度是否应该标准化。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | 确定文本是否不应校对。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | 返回或设置字符间距增量。  **float.NaN** 表示值未定义，应从 Master 继承。 读/写Single。 |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | 返回或设置文本的删除线类型。未应用继承。 读/写[`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | 返回或设置符号字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | 返回或设置文本大写的类型。未应用继承。 读/写[`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | 返回下划线行的 FillFormat 属性。未应用继承。 只读[`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | 返回用于勾勒下划线的 LineFormat 属性。未应用继承。 只读[`ILineFormat`](../ilineformat)。 |

### 评论

此类用于返回和操作为特定部分定义的文本部分格式化属性。这意味着 在获取值时不应用继承，因此在大多数情况下，您将获得意味着“未定义”的值。

为了获得包括继承在内的有效格式化参数值，您需要使用[`GetEffective`](../iportionformat/geteffective)方法 返回一个[`IPortionFormatEffectiveData`](../iportionformateffectivedata)实例。

### 也可以看看

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->