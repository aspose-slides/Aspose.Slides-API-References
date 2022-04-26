---
title: IBasePortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 4830
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
| [AlternativeLanguageId](alternativelanguageid) { get; set; } | Returns or sets the Id of an alternative language. Read/write String. |
| [ComplexScriptFont](complexscriptfont) { get; set; } | Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [EastAsianFont](eastasianfont) { get; set; } | Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [EffectFormat](effectformat) { get; } | Returns the text EffectFormat properties. No inheritance applied. Read-only [`IEffectFormat`](../ieffectformat). |
| [Escapement](escapement) { get; set; } | Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [FillFormat](fillformat) { get; } | Returns the text FillFormat properties. No inheritance applied. Read-only [`IFillFormat`](../ifillformat). |
| [FontBold](fontbold) { get; set; } | Determines whether the font is bold. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [FontHeight](fontheight) { get; set; } | Returns or sets the font height of a portion. **float.NaN** means height is undefined and should be inherited from the Master. Read/write Single. |
| [FontItalic](fontitalic) { get; set; } | Determines whether the font is itallic. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [FontUnderline](fontunderline) { get; set; } | Returns or sets the text underline type. No inheritance applied. Read/write [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](highlightcolor) { get; } | Returns the color used to highlight a text. No inheritance applied. Read-only [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](ishardunderlinefill) { get; set; } | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](ishardunderlineline) { get; set; } | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](kerningminimalsize) { get; set; } | Returns or sets the minimal font size, for which kerning should be switched on. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [Kumimoji](kumimoji) { get; set; } | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](languageid) { get; set; } | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |
| [LatinFont](latinfont) { get; set; } | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [LineFormat](lineformat) { get; } | Returns the LineFormat properties for text outlining. No inheritance applied. Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](normaliseheight) { get; set; } | Determines whether the height of a text should be normalized. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](proofdisabled) { get; set; } | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write [`NullableBool`](../nullablebool). |
| [Spacing](spacing) { get; set; } | Returns or sets the intercharacter spacing increment. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [StrikethroughType](strikethroughtype) { get; set; } | Returns or sets the strikethrough type of a text. No inheritance applied. Read/write [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](symbolfont) { get; set; } | Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../ifontdata). |
| [TextCapType](textcaptype) { get; set; } | Returns or sets the type of text capitalization. No inheritance applied. Read/write [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](underlinefillformat) { get; } | Returns the underline line FillFormat properties. No inheritance applied. Read-only [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](underlinelineformat) { get; } | Returns the LineFormat properties used to outline underline line. No inheritance applied. Read-only [`ILineFormat`](../ilineformat). |

### Remarks

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [`GetEffective`](../iportionformat/geteffective) method which returns a [`IPortionFormatEffectiveData`](../iportionformateffectivedata) instance.

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
