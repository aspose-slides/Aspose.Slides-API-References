---
title: ChartPortionFormat
second_title: Aspose.Sildes для .NET API Reference
description: Этот класс содержит свойства форматирования частей диаграмм, используемые в диаграммах. В отличие от IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, все свойства этого класса подлежат записи.
type: docs
weight: 1350
url: /ru/aspose.slides.charts/chartportionformat/
---

## ChartPortionFormat class

Этот класс содержит свойства форматирования частей диаграмм, используемые в диаграммах. В отличие от [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), все свойства этого класса подлежат записи.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает Id альтернативного языка. Чтение/запись Строка. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базинй интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о шрифте для сложных текстов. Null означает, что шрифт не определён и должен наследоваться от мастера. Чтение/запись [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию о шрифте восточноазиатских языков. Null означает, что шрифт не определён и должен наследоваться от мастера. Чтение/запись [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства EffectFormat текста. Наследование не применяется. Только для чтения [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или задает степень надстрочного или подстрочного текста. Значение от -100% (подстрочный) до 100% (надстрочный). **float.NaN** означает, что значение не определено и должно наследоваться от мастера. Чтение/запись Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт жирным. Наследование не применяется. Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или задает высоту шрифта части. **float.NaN** означает, что высота не определена и должна наследоваться от мастера. Чтение/запись Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивом. Наследование не применяется. Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого должно быть включено кернинг. **float.NaN** означает, что значение не определено и должно наследоваться от мастера. Чтение/запись Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли цифры игнорировать текстовый вертикальный макет, специфичный для восточных языков. Наследование не применяется. Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или задает Id языка проверки. Используется для проверки орфографии и грамматики. Чтение/запись Строка. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определён и должен наследоваться от мастера. Чтение/запись [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для обводки текста. Наследование не применяется. Только для чтения [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, не следует ли проверять текст. Наследование не применяется. Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или задает увеличение межсимвольного интервала. **float.NaN** означает, что значение не определено и должно наследоваться от мастера. Чтение/запись Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или задает тип зачеркивания текста. Наследование не применяется. Чтение/запись [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или задает информацию о символьном шрифте. Null означает, что шрифт не определён и должен наследоваться от мастера. Чтение/запись [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для обводки линии подчеркивания. Наследование не применяется. Только для чтения [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хеш-код. |

### Remarks

Этот класс используется для возврата и манипуляции свойствами форматирования текстовых частей, определенными для конкретной части. Это означает, что наследование не применяется при получении значений, поэтому в большинстве случаев вы получите значения, означающие "неопределено".

Чтобы получить эффективные значения параметров форматирования, включая наследуемые, вам нужно использовать метод [`GetEffective`](../../aspose.slides/portionformat/geteffective), который возвращает экземпляр [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### See Also

* класс [BasePortionFormat](../../aspose.slides/baseportionformat)
* интерфейс [IChartPortionFormat](../ichartportionformat)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->