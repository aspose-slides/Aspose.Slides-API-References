---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: อินเทอร์เฟซฐานสำหรับวัตถุที่ไม่เปลี่ยนแปลงซึ่งมีคุณลักษณะการจัดรูปแบบส่วนข้อความที่มีผล
type: docs
weight: 5340
url: /th/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData อินเทอร์เฟซ

Base interface for immutable objects which contain effective text portion formatting properties.

```csharp
public interface IBasePortionFormatEffectiveData
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Returns the Id of an alternative language. อ่านอย่างเดียว String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Returns the complex script font info. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Returns the East Asian font info. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Returns the text EffectFormat properties. อ่านอย่างเดียว [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Returns the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). อ่านอย่างเดียว Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Returns the text FillFormat properties. อ่านอย่างเดียว [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Determines whether the font is bold. อ่านอย่างเดียว Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Returns the font height of the text portion, in points. อ่านอย่างเดียว Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Determines whether the font is itallic. อ่านอย่างเดียว Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Returns the text underline type. อ่านอย่างเดียว [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Returns the color used to highlight a text. อ่านอย่างเดียว Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. อ่านอย่างเดียว Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. อ่านอย่างเดียว Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Returns the minimal font size, for which kerning should be switched on. อ่านอย่างเดียว Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Determines whether the numbers should ignore text eastern language-specific vertical text layout. อ่านอย่างเดียว Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Returns the Id of a language. อ่านอย่างเดียว String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Returns the Latin font info. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Returns the LineFormat properties for text outlining. อ่านอย่างเดียว [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Determines whether the height of a text should be normalized. อ่านอย่างเดียว Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Determines whether the text shouldn't be proofed. อ่านอย่างเดียว Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Determines whether the smart tag should be cleaned. อ่านอย่างเดียว Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Returns the intercharacter spacing increment, in points. อ่านอย่างเดียว Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Returns the strikethrough type of a text. อ่านอย่างเดียว [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Returns the symbolic font info. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Returns the type of text capitalization. อ่านอย่างเดียว [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Returns the underline line FillFormat properties. อ่านอย่างเดียว [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Returns the LineFormat properties used to outline underline line. อ่านอย่างเดียว [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->