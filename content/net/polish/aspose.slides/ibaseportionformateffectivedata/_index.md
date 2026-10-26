---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Podstawowy interfejs niezmiennych obiektów zawierających skuteczne właściwości formatowania fragmentu tekstu.
type: docs
weight: 5320
url: /pl/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interfejs

Podstawowy interfejs dla niezmiennych obiektów zawierających skuteczne właściwości formatowania fragmentu tekstu.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Zwraca identyfikator alternatywnego języka. Tylko do odczytu String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Zwraca informacje o czcionce skryptu złożonego. Tylko do odczytu [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Zwraca informacje o czcionce wschodnioazjatyckiej. Tylko do odczytu [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Zwraca właściwości EffectFormat tekstu. Tylko do odczytu [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Zwraca tekst w indeksie górnym lub dolnym. Wartość od -100 % (indeks dolny) do 100 % (indeks górny). Tylko do odczytu Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Zwraca właściwości FillFormat tekstu. Tylko do odczytu [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Określa, czy czcionka jest pogrubiona. Tylko do odczytu Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Zwraca wysokość czcionki fragmentu tekstu w punktach. Tylko do odczytu Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Określa, czy czcionka jest kursywą. Tylko do odczytu Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Zwraca typ podkreślenia tekstu. Tylko do odczytu [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Zwraca kolor używany do wyróżnienia tekstu. Tylko do odczytu Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Tylko do odczytu Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Tylko do odczytu Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Zwraca minimalny rozmiar czcionki, dla którego kerning powinien być włączony. Tylko do odczytu Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków układ pionowy tekstu. Tylko do odczytu Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Zwraca identyfikator języka. Tylko do odczytu String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Zwraca informacje o czcionce łacińskiej. Tylko do odczytu [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Zwraca właściwości LineFormat dla obrysu tekstu. Tylko do odczytu [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Określa, czy wysokość tekstu powinna być znormalizowana. Tylko do odczytu Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Określa, czy tekst nie powinien być sprawdzany pod kątem błędów. Tylko do odczytu Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Określa, czy inteligentny znacznik powinien zostać wyczyszczony. Tylko do odczytu Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Zwraca przyrost odstępu między znakami w punktach. Tylko do odczytu Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Zwraca typ przekreślenia tekstu. Tylko do odczytu [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Zwraca informacje o czcionce symbolicznej. Tylko do odczytu [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Zwraca typ kapitalizacji tekstu. Tylko do odczytu [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Zwraca właściwości FillFormat linii podkreślenia. Tylko do odczytu [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Zwraca właściwości LineFormat używane do obrysu linii podkreślenia. Tylko do odczytu [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Zobacz także

* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->