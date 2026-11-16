---
title: IBasePortionFormatEffectiveData
second_title: Справочник API Aspose.Slides для .NET
description: Базовый интерфейс для неизменяемых объектов, содержащих свойства эффективного форматирования текстовых частей.
type: docs
weight: 5340
url: /ru/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData интерфейс

Базовый интерфейс для неизменяемых объектов, содержащих свойства эффективного форматирования текстовых частей.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Возвращает идентификатор альтернативного языка. Только для чтения String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Возвращает информацию о шрифте сложных сценариев. Только для чтения [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Возвращает информацию о шрифте восточноазиатского текста. Только для чтения [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Возвращает свойства EffectFormat текста. Только для чтения [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Возвращает надстрочный или нижний индекс текста. Значение от -100% (нижний индекс) до 100% (надстрочный). Только для чтения Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Возвращает свойства FillFormat текста. Только для чтения [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Определяет, является ли шрифт полужирным. Только для чтения Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Возвращает высоту шрифта текстовой части в пунктах. Только для чтения Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Определяет, является ли шрифт курсивным. Только для чтения Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Возвращает тип подчеркивания текста. Только для чтения [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Только для чтения Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста. Только для чтения Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста. Только для чтения Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Возвращает минимальный размер шрифта, при котором включается кернинг. Только для чтения Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную раскладку текста. Только для чтения Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Возвращает идентификатор языка. Только для чтения String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Возвращает информацию о латинском шрифте. Только для чтения [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Возвращает свойства LineFormat для обводки текста. Только для чтения [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Определяет, должна ли высота текста быть нормализована. Только для чтения Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Определяет, не следует ли проверять текст на орфографию. Только для чтения Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Определяет, следует ли очистить смарт-тег. Только для чтения Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Возвращает прибавку интервала между символами в пунктах. Только для чтения Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Возвращает тип зачеркивания текста. Только для чтения [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Возвращает информацию о символическом шрифте. Только для чтения [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Возвращает тип написания текста. Только для чтения [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Только для чтения [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для обводки линии подчеркивания. Только для чтения [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### См. также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->