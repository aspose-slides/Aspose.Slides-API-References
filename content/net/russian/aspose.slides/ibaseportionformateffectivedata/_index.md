---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides для .NET API Справочник
description: Базовый интерфейс для неизменяемых объектов, содержащих свойства форматирования текстовых порций.
type: docs
weight: 5120
url: /ru/aspose.slides/ibaseportionformateffectivedata/
---

## Интерфейс IBasePortionFormatEffectiveData

Базовый интерфейс для неизменяемых объектов, содержащих свойства форматирования текстовых порций.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Возвращает Id альтернативного языка. Только для чтения String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Возвращает информацию о сложном шрифте. Только для чтения [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Возвращает информацию о восточноазиатском шрифте. Только для чтения [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Возвращает свойства EffectFormat текста. Только для чтения [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Возвращает текст в верхнем или нижнем регистре. Значение от -100% (нижний регистр) до 100% (верхний регистр). Только для чтения Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Возвращает свойства FillFormat текста. Только для чтения [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Определяет, является ли шрифт жирным. Только для чтения Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Возвращает высоту шрифта порции. Только для чтения Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Определяет, является ли шрифт курсивом. Только для чтения Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Возвращает тип подчеркивания текста. Только для чтения [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Только для чтения Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Только для чтения Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Только для чтения Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Возвращает минимальный размер шрифта, для которого должно быть включено кернинг. Только для чтения Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Определяет, должны ли числа игнорировать верстку текста, специфичную для восточных языков. Только для чтения Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Возвращает Id языка. Только для чтения String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Возвращает информацию о латинском шрифте. Только для чтения [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Возвращает свойства LineFormat для обводки текста. Только для чтения [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Определяет, должна ли быть нормализована высота текста. Только для чтения Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Определяет, не должен ли текст быть проверен. Только для чтения Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Определяет, следует ли очистить смарт-тег. Только для чтения Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Возвращает величину межсимвольного интервала. Только для чтения Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Возвращает тип зачеркивания текста. Только для чтения [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Возвращает информацию о символическом шрифте. Только для чтения [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Возвращает тип капитализации текста. Только для чтения [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Только для чтения [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемое для обводки линии подчеркивания. Только для чтения [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Также см. 

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->