---
title: IBasePortionFormatEffectiveData
second_title: Справочник по API Aspose.Slides для .NET
description: Базовый интерфейс для неизменяемых объектов которые содержат эффективные свойства форматирования текстовой части.
type: docs
weight: 4840
url: /ru/net/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interface

Базовый интерфейс для неизменяемых объектов, которые содержат эффективные свойства форматирования текстовой части.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Возвращает идентификатор альтернативного языка. Только для чтенияString . |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Возвращает информацию о сложном шрифте скрипта. Только для чтения[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Возвращает информацию о восточноазиатском шрифте. Только для чтения[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Возвращает свойства текста EffectFormat. Только для чтения[`IEffectFormatEffectiveData`](../ieffectformateffectivedata) . |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Возвращает текст верхнего или нижнего индекса. Значение от -100% (нижний индекс) до 100% (верхний индекс). Только для чтенияSingle . |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Возвращает свойства текста FillFormat. Только для чтения[`IFillFormatEffectiveData`](../ifillformateffectivedata) . |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Определяет, является ли шрифт полужирным. Только для чтенияBoolean . |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Возвращает высоту шрифта части. Только для чтенияSingle . |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Определяет, является ли шрифт курсивом. Только для чтенияBoolean . |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Возвращает тип подчеркивания текста. Только для чтения[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Только для чтенияColor . |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует его от свойств FillFormat текста. Только для чтенияBoolean . |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует его от свойств LineFormat текста. Только для чтенияBoolean . |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Возвращает минимальный размер шрифта, для которого должен быть включен кернинг. Только для чтенияSingle . |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Определяет, должны ли числа игнорировать текст Вертикальное расположение текста для восточного языка. Только для чтенияBoolean . |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Возвращает идентификатор языка. Только для чтенияString . |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Возвращает информацию о латинском шрифте. Только для чтения[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Возвращает свойства LineFormat для выделения текста. Только для чтения[`ILineFormatEffectiveData`](../ilineformateffectivedata) . |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Определяет, следует ли нормализовать высоту текста. Только для чтенияBoolean . |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Определяет, следует ли проверять текст. Только для чтенияBoolean . |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Определяет необходимость очистки смарт-тега. Только для чтенияBoolean . |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Возвращает приращение межсимвольного интервала. Только для чтенияSingle . |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Возвращает зачеркнутый тип текста. Только для чтения[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Возвращает информацию о символическом шрифте. Только для чтения[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Возвращает тип капитализации текста. Только для чтения[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Только для чтения[`IFillFormatEffectiveData`](../ifillformateffectivedata) . |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для выделения линии подчеркивания. Только для чтения[`ILineFormatEffectiveData`](../ilineformateffectivedata) . |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
