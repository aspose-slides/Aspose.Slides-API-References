---
title: IBasePortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: This class contains the text portion formatting properties. Unlike IPortionFormatEffectiveData./iportionformateffectivedata all properties of this class are writeable.
type: docs
weight: 4960
url: /net/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public interface IBasePortionFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Returns or sets the Id of an alternative language. Read/write String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Returns the text EffectFormat properties. No inheritance applied. Read-only [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Returns the text FillFormat properties. No inheritance applied. Read-only [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Determines whether the font is bold. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Returns or sets the font height of a portion. **float.NaN** means height is undefined and should be inherited from the Master. Read/write Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Determines whether the font is itallic. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Returns or sets the text underline type. No inheritance applied. Read/write [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Returns the color used to highlight a text. No inheritance applied. Read-only [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Returns or sets the minimal font size, for which kerning should be switched on. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Returns the LineFormat properties for text outlining. No inheritance applied. Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Determines whether the height of a text should be normalized. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Returns or sets the intercharacter spacing increment. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Returns or sets the strikethrough type of a text. No inheritance applied. Read/write [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Returns or sets the type of text capitalization. No inheritance applied. Read/write [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Returns the underline line FillFormat properties. No inheritance applied. Read-only [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Returns the LineFormat properties used to outline underline line. No inheritance applied. Read-only [`ILineFormat`](../ilineformat). |

### Remarks

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [`GetEffective`](../iportionformat/geteffective) method which returns a [`IPortionFormatEffectiveData`](../iportionformateffectivedata) instance.

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
