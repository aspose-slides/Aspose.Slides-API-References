---
title: PortionFormat
second_title: Aspose.Slides for .NET API 参考
description: 此类包含文本部分格式属性与IPortionFormatEffectiveData./iportionformateffectivedata不同此类的所有属性都是可写的
type: docs
weight: 8760
url: /zh/net/aspose.slides/portionformat/
---
## PortionFormat class

此类包含文本部分格式属性。与[`IPortionFormatEffectiveData`](../iportionformateffectivedata)不同，此类的所有属性都是可写的。

```csharp
public class PortionFormat : BasePortionFormat, IPortionFormat
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PortionFormat](portionformat)() | 初始化[`PortionFormat`](../portionformat)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 返回或设置替代语言的 ID。 读/写String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基本 IPresentationComponent 接口。 只读[`IPresentationComponent`](../ipresentationcomponent)。 |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | 返回或设置书签标识符。 读/写String。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 返回或设置复杂的脚本字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 返回或设置东亚字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 返回文本 EffectFormat 属性。未应用继承。 只读[`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 返回或设置上标或下标文本。 值从 -100%（下标）到 100%（上标）。  **float.NaN** 表示值未定义，应从 Master 继承。 读/写Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 返回文本 FillFormat 属性。未应用继承。 只读[`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 确定字体是否为粗体。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 返回或设置部分的字体高度。  **float.NaN** 表示高度未定义，应从 Master 继承。 读/写Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 确定字体是否为斜体。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 返回或设置文本下划线类型。未应用继承。 读/写[`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 返回用于突出显示文本的颜色。未应用继承。 只读[`IColorFormat`](../icolorformat)。 |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | 返回或设置为鼠标单击定义的超链接。 读/写[`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | 超链接管理器。 只读[`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。 读/写[`IHyperlink`](../ihyperlink)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 确定下划线样式是否有自己的 FillFormat 属性或从文本的 FillFormat 属性继承 。 读/写[`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 确定下划线样式是否具有自己的 LineFormat 属性或从文本的 LineFormat 属性继承 。 读/写[`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 返回或设置最小字体大小，为此应打开字距调整。  **float.NaN** 表示值未定义，应从 Master 继承。 读/写Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 确定数字是否应忽略文本东方语言特定的垂直文本布局。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 返回或设置校对语言的 ID。用于检查拼写和语法。 读/写String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 返回或设置拉丁字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 返回文本轮廓的 LineFormat 属性。未应用继承。 只读[`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 确定文本的高度是否应该标准化。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 确定文本是否不应校对。未应用继承。 读/写[`NullableBool`](../nullablebool)。 |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | 确定是否应清除智能标记。未应用继承。 读/写Boolean。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 返回或设置字符间距增量。  **float.NaN** 表示值未定义，应从 Master 继承。 读/写Single。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 返回或设置文本的删除线类型。未应用继承。 读/写[`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 返回或设置符号字体信息。 Null 表示字体未定义，应从 Master 继承。 读/写[`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 返回或设置文本大写的类型。未应用继承。 读/写[`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 返回下划线行的 FillFormat 属性。未应用继承。 只读[`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 返回用于勾勒下划线的 LineFormat 属性。未应用继承。 只读[`ILineFormat`](../ilineformat)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象比较。 |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | 获取应用继承的有效部分格式化数据。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希码。 |

### 评论

此类用于返回和操作为特定部分定义的文本部分格式化属性。这意味着 在获取值时不应用继承，因此在大多数情况下，您将获得意味着“未定义”的值。

为了获得包括继承在内的有效格式化参数值，您需要使用[`GetEffective`](./geteffective)方法 返回一个[`IPortionFormatEffectiveData`](../iportionformateffectivedata)实例。

### 也可以看看

* class [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
