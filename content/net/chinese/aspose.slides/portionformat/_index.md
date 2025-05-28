---
title: PortionFormat
second_title: Aspose.Sildes for .NET API 参考
description: 此类包含文本部分格式化属性。与 IPortionFormatEffectiveData../iportionformateffectivedata 不同，此类的所有属性都是可写的。
type: docs
weight: 9220
url: /zh/aspose.slides/portionformat/
---

## PortionFormat 类

此类包含文本部分格式化属性。与 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 不同，此类的所有属性都是可写的。

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PortionFormat](portionformat)() | 初始化一个新的 [`PortionFormat`](../portionformat) 类实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 获取或设置备用语言的 Id。可读写字符串。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基本 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | 获取或设置书签标识符。可读写字符串。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 获取或设置复杂脚本字体信息。为 null 表示字体未定义，应从母版中继承。可读写 [`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 获取或设置东亚字体信息。为 null 表示字体未定义，应从母版中继承。可读写 [`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 获取文本 EffectFormat 属性。未应用继承。只读 [`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 获取或设置上标或下标文本。值范围为 -100%（下标）到 100%（上标）。**float.NaN** 表示值未定义，应从母版中继承。可读写单精度浮点数。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 获取文本 FillFormat 属性。未应用继承。只读 [`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 确定字体是否加粗。未应用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 获取或设置部分的字体高度。**float.NaN** 表示高度未定义，应从母版中继承。可读写单精度浮点数。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 确定字体是否斜体。未应用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 获取或设置文本下划线类型。未应用继承。可读写 [`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 获取用于突出显示文本的颜色。未应用继承。只读 [`IColorFormat`](../icolorformat)。 |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | 获取或设置定义的超链接，用于鼠标点击。可读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | 超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | 获取或设置定义的超链接，用于鼠标悬停。可读写 [`IHyperlink`](../ihyperlink)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 确定下划线样式是否具有自己的 FillFormat 属性或从文本的 FillFormat 属性中继承。可读写 [`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 确定下划线样式是否具有自己的 LineFormat 属性或从文本的 LineFormat 属性中继承。可读写 [`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 获取或设置最小字体大小，启用字距调整。**float.NaN** 表示值未定义，应从母版中继承。可读写单精度浮点数。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 确定数字是否应忽略文本的东亚语言特定的垂直文本布局。未应用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 获取或设置校对语言的 Id。用于检查拼写和语法。可读写字符串。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 获取或设置拉丁字体信息。为 null 表示字体未定义，应从母版中继承。可读写 [`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 获取用于文本轮廓的 LineFormat 属性。未应用继承。只读 [`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 确定文本的高度是否应归一化。未应用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 确定文本是否不应进行校对。未应用继承。可读写 [`NullableBool`](../nullablebool)。 |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | 确定是否应清除智能标签。未应用继承。可读写布尔值。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 获取或设置字符间距增量。**float.NaN** 表示值未定义，应从母版中继承。可读写单精度浮点数。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 获取或设置文本的删除线类型。未应用继承。可读写 [`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 获取或设置符号字体信息。为 null 表示字体未定义，应从母版中继承。可读写 [`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 获取或设置文本大写类型。未应用继承。可读写 [`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 获取下划线线条的 FillFormat 属性。未应用继承。只读 [`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 获取用于轮廓下划线线条的 LineFormat 属性。未应用继承。只读 [`ILineFormat`](../ilineformat)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象进行比较。 |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | 获取有效的部分格式化数据，包括继承的属性。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希代码。 |

### 备注

此类用于返回和操作为特定部分定义的文本部分格式化属性。这意味着在获取值时不会应用继承，因此在大多数情况下，您将获得值，表示“未定义”。

为了获取包括继承在内的有效格式化参数值，您需要使用 [`GetEffective`](./geteffective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 实例。

### 示例

以下示例显示如何将拉丁字体分配给 PowerPoint 演示文稿中的段落部分。

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
// +mn-lt - 主体字体拉丁文（次要拉丁字体）
// +mj-lt - 标题字体拉丁文（主要拉丁字体）
// +mn-ea - 主体字体东亚文（次要东亚字体）
// +mj-ea - 主体字体东亚文（主要东亚字体）
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### 另请参阅

* 类 [BasePortionFormat](../baseportionformat)
* 接口 [IPortionFormat](../iportionformat)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->