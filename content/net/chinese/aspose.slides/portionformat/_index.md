---
title: PortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: 该类包含文本部分格式化属性。与 IPortionFormatEffectiveData../iportionformateffectivedata 不同的是，该类的所有属性都是可写的。
type: docs
weight: 9220
url: /zh/aspose.slides/portionformat/
---

## PortionFormat class

该类包含文本部分格式化属性。与 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 不同的是，该类的所有属性都是可写的。

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructors

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | 初始化 [`PortionFormat`](../portionformat) 类的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 返回或设置备用语言的 ID。可读写字符串。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基本 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | 返回或设置书签标识符。可读写字符串。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 返回或设置复杂脚本字体信息。空值表示字体未定义，应继承自母版。可读写 [`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 返回或设置东亚字体信息。空值表示字体未定义，应继承自母版。可读写 [`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 返回文本效果格式属性。不适用继承。只读 [`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 返回或设置上标或下标文本。值从 -100%（下标）到 100%（上标）。**float.NaN** 表示值未定义，应继承自母版。可读写单精度浮点数。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 返回文本填充格式属性。不适用继承。只读 [`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 确定字体是否为粗体。不适用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 返回或设置字体的高度。**float.NaN** 表示高度未定义，应继承自母版。可读写单精度浮点数。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 确定字体是否为斜体。不适用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 返回或设置文本下划线类型。不适用继承。可读写 [`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 返回用于高亮显示文本的颜色。不适用继承。只读 [`IColorFormat`](../icolorformat)。 |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | 返回或设置为鼠标点击定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | 超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 确定下划线样式是否具有自己的填充格式属性，或从文本的填充格式属性继承。可读写 [`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 确定下划线样式是否具有自己的线条格式属性，或从文本的线条格式属性继承。可读写 [`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 返回或设置应开启字距调整的最小字体大小。**float.NaN** 表示值未定义，应继承自母版。可读写单精度浮点数。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 确定数字是否应忽略文本东亚语言特定的垂直文本布局。不适用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 返回或设置校对语言的 ID。用于检查拼写和语法。可读写字符串。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 返回或设置拉丁字体信息。空值表示字体未定义，应继承自母版。可读写 [`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 返回文本轮廓的线条格式属性。不适用继承。只读 [`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 确定文本的高度是否应规范化。不适用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 确定文本是否不应进行校对。不适用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | 确定智能标签是否应被清除。不适用继承。可读写布尔值。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 返回或设置字符间距增量。**float.NaN** 表示值未定义，应继承自母版。可读写单精度浮点数。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 返回或设置文本的删除线类型。不适用继承。可读写 [`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 返回或设置符号字体信息。空值表示字体未定义，应继承自母版。可读写 [`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 返回或设置文本大写类型。不适用继承。可读写 [`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 返回下划线上填充格式属性。不适用继承。只读 [`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 返回用于勾勒下划线的线条格式属性。不适用继承。只读 [`ILineFormat`](../ilineformat)。 |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象进行比较。 |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | 获取应用了继承的有效部分格式数据。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希代码。 |

### Remarks

该类用于返回和操作为特定部分定义的文本部分格式化属性。这意味着在获取值时不适用继承，因此在大多数情况下，您将获得表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [`GetEffective`](./geteffective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 实例。

### Examples

以下示例向您展示如何将拉丁字体分配给 PowerPoint 演示文稿中的段落部分。

```csharp
[C#]
// 实例化一个表示演示文稿文件的演示文稿对象
using (Presentation pres = new Presentation("demo.pptx"))
{
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
    Paragraph paragraph = new Paragraph();
    Portion portion = new Portion("主题文本格式");
    paragraph.Portions.Add(portion);
    shape.TextFrame.Paragraphs.Add(paragraph);
    // Aspose.Slides 使用这些特殊标识符（类似于 PowerPoint 中使用的标识符）：
    // +mn-lt - 正文字体拉丁语（小拉丁字体）
    // +mj-lt - 标题字体拉丁语（大拉丁字体）
    // +mn-ea - 正文字体东亚语（小东亚字体）
    // +mj-ea - 标题字体东亚语（大东亚字体）
    portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### See Also

* class [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->