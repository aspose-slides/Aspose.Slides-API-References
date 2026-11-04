---
title: PortionFormat
second_title: Aspose.Sildes .NET API 参考
description: 此类包含文本段落格式属性。不同于 IPortionFormatEffectiveData./iportionformateffectivedata，此类的所有属性均可写。
type: docs
weight: 9510
url: /zh/aspose.slides/portionformat/
---
## PortionFormat 类

此类包含文本段落格式属性。不同于 [`IPortionFormatEffectiveData`](../iportionformateffectivedata)，此类的所有属性均可写。

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PortionFormat](portionformat)() | 初始化 [`PortionFormat`](../portionformat) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 返回或设置备用语言的 Id。读写 String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基础 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | 返回或设置书签标识符。读写 String。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 返回或设置复合脚本字体信息。Null 表示字体未定义，应从母版继承。读写 [`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 返回或设置东亚字体信息。Null 表示字体未定义，应从母版继承。读写 [`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 返回文本 EffectFormat 属性。未应用继承。只读 [`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 返回或设置上标或下标文本。值范围为 -100%（下标）到 100%（上标）。**float.NaN** 表示值未定义，应从母版继承。读写 Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 返回文本 FillFormat 属性。未应用继承。只读 [`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 确定字体是否为粗体。未应用继承。读写 [`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 返回或设置段落的字体高度。**float.NaN** 表示高度未定义，应从母版继承。读写 Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 确定字体是否为斜体。未应用继承。读写 [`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 返回或设置文本下划线类型。未应用继承。读写 [`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 返回用于突出显示文本的颜色。未应用继承。只读 [`IColorFormat`](../icolorformat)。 |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | 返回或设置鼠标点击时定义的超链接。读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | 超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | 返回或设置鼠标悬停时定义的超链接。读写 [`IHyperlink`](../ihyperlink)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 确定下划线样式是否具有独立的 FillFormat 属性，或从文本的 FillFormat 属性继承。读写 [`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 确定下划线样式是否具有独立的 LineFormat 属性，或从文本的 LineFormat 属性继承。读写 [`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 返回或设置应开启字距调整的最小字体大小。**float.NaN** 表示值未定义，应从母版继承。读写 Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 确定数字是否应忽略文本东亚语言特定的垂直布局。未应用继承。读写 [`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 返回或设置校对语言的 Id。用于拼写和语法检查。读写 String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 返回或设置拉丁字体信息。Null 表示字体未定义，应从母版继承。读写 [`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 返回文本轮廓的 LineFormat 属性。未应用继承。只读 [`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 确定文本高度是否应标准化。未应用继承。读写 [`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 确定文本是否不应进行校对。未应用继承。读写 [`NullableBool`](../nullablebool)。 |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | 确定是否应清除智能标签。未应用继承。读写 Boolean。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 返回或设置字符间距增量。**float.NaN** 表示值未定义，应从母版继承。读写 Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | 获取或设置指示是否为文本段落启用拼写检查的值。当此属性设为 false 时，文本元素的拼写检查被抑制。设为 true 时，允许拼写检查。默认值为 `false`。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 返回或设置文本的删除线类型。未应用继承。读写 [`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 返回或设置符号字体信息。Null 表示字体未定义，应从母版继承。读写 [`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 返回或设置文本大小写类型。未应用继承。读写 [`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 返回下划线线条的 FillFormat 属性。未应用继承。只读 [`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 返回用于描绘下划线线条的 LineFormat 属性。未应用继承。只读 [`ILineFormat`](../ilineformat)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象进行比较。 |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | 获取应用继承后的有效段落格式数据。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希码。 |

### 备注

此类用于返回和操作为特定段落定义的文本段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下会得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，需要使用 [`GetEffective`](./geteffective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 实例。

### 示例

以下示例展示了如何将拉丁字体分配给 PowerPoint 演示文稿中段落的段落部分。

```csharp
[C#]
//实例化一个代表演示文件的 Presentation 对象
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides 使用这些特殊标识符（类似于 PowerPoint 中使用的）:
// +mn-lt - 正文字体拉丁文（次要拉丁字体）
// +mj-lt -标题字体拉丁文（主要拉丁字体）
// +mn-ea - 正文字体东亚（次要东亚字体）
// +mj-ea - 正文字体东亚（次要东亚字体）
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### 参见

* 类 [BasePortionFormat](../baseportionformat)
* 接口 [IPortionFormat](../iportionformat)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->