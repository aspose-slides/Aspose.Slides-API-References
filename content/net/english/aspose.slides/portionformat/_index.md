---
title: PortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: This class contains the text portion formatting properties. Unlike IPortionFormatEffectiveData./iportionformateffectivedata all properties of this class are writeable.
type: docs
weight: 9420
url: /aspose.slides/portionformat/
---

## PortionFormat class

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructors

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Initializes a new instance of [`PortionFormat`](../portionformat) class. |

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Returns or sets the Id of an alternative language. Read/write String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Returns or sets bookmark identifier. Read/write String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Returns the text EffectFormat properties. No inheritance applied. Read-only [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Returns the text FillFormat properties. No inheritance applied. Read-only [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determines whether the font is bold. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Returns or sets the font height of a portion. **float.NaN** means height is undefined and should be inherited from the Master. Read/write Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determines whether the font is itallic. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Returns or sets the text underline type. No inheritance applied. Read/write [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Returns the color used to highlight a text. No inheritance applied. Read-only [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Returns or sets the hyperlink defined for mouse click. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlinks manager. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Returns or sets the hyperlink defined for mouse over. Read/write [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Returns or sets the minimal font size, for which kerning should be switched on. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Returns the LineFormat properties for text outlining. No inheritance applied. Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determines whether the height of a text should be normalized. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Determines whether the smart tag should be cleaned. No inheritance applied. Read/write Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Returns or sets the intercharacter spacing increment. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Returns or sets the strikethrough type of a text. No inheritance applied. Read/write [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Returns or sets the type of text capitalization. No inheritance applied. Read/write [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Returns the underline line FillFormat properties. No inheritance applied. Read-only [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Returns the LineFormat properties used to outline underline line. No inheritance applied. Read-only [`ILineFormat`](../ilineformat). |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compares with specified object. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Gets effective portion formatting data with the inheritance applied. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returns hash code. |

### Remarks

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [`GetEffective`](./geteffective) method which returns a [`IPortionFormatEffectiveData`](../iportionformateffectivedata) instance.

### Examples

The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.

```csharp
[C#]
//Instantiate a presentation object that represents a presentation file
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides uses these special identifiers (similar to those used in PowerPoint):
// +mn-lt - Body Font Latin (Minor Latin Font)
// +mj-lt -Heading Font Latin (Major Latin Font)
// +mn-ea - Body Font East Asian (Minor East Asian Font)
// +mj-ea - Body Font East Asian (Minor East Asian Font)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### See Also

* class [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
