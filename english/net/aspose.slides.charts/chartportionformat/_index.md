---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: This class contains the chart portion formatting properties used in charts. Unlike IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata all properties of this class are writeable.
type: docs
weight: 1310
url: /net/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat class

This class contains the chart portion formatting properties used in charts. Unlike [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

```csharp
public class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Returns or sets the Id of an alternative language. Read/write String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Returns the text EffectFormat properties. No inheritance applied. Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Returns the text FillFormat properties. No inheritance applied. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determines whether the font is bold. No inheritance applied. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Returns or sets the font height of a portion. **float.NaN** means height is undefined and should be inherited from the Master. Read/write Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determines whether the font is itallic. No inheritance applied. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Returns or sets the text underline type. No inheritance applied. Read/write [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Returns the color used to highlight a text. No inheritance applied. Read-only [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Returns or sets the minimal font size, for which kerning should be switched on. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Returns the LineFormat properties for text outlining. No inheritance applied. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determines whether the height of a text should be normalized. No inheritance applied. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Returns or sets the intercharacter spacing increment. **float.NaN** means value is undefined and should be inherited from the Master. Read/write Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Returns or sets the strikethrough type of a text. No inheritance applied. Read/write [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Returns or sets the type of text capitalization. No inheritance applied. Read/write [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Returns the underline line FillFormat properties. No inheritance applied. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Returns the LineFormat properties used to outline underline line. No inheritance applied. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compares with specified object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returns hash code. |

### Remarks

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [`GetEffective`](../../aspose.slides/portionformat/geteffective) method which returns a [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) instance.

### See Also

* class [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
