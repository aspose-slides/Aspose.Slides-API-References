---
title: BasePortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: Common text portion formatting properties.
type: docs
weight: 880
url: /net/aspose.slides/baseportionformat/
---
## BasePortionFormat class

Common text portion formatting properties.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Returns or sets the Id of an alternative language. Read/write String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
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
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Returns or sets the minimal font size, for which kerning should be switched on. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Returns the LineFormat properties for text outlining. No inheritance applied. Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determines whether the height of a text should be normalized. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
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
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returns hash code. |

### See Also

* class [PVIObject](../pviobject)
* interface [IBasePortionFormat](../ibaseportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
