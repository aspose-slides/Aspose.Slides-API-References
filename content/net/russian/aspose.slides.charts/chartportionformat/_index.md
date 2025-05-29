---
title: ChartPortionFormat
second_title: Aspose.Sildes для .NET API Reference
description: Этот класс содержит свойства форматирования частей диаграммы, используемые в диаграммах. В отличие от IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, все свойства этого класса могут быть записаны.
type: docs
weight: 1350
url: /ru/aspose.slides.charts/chartportionformat/
---

## Класс ChartPortionFormat

Этот класс содержит свойства форматирования частей диаграммы, используемые в диаграммах. В отличие от [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), все свойства этого класса могут быть записаны.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает идентификатор альтернативного языка. Читаемая/записываемая строка. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о шрифте сложного скрипта. Null означает, что шрифт не определен и должен наследоваться от мастера. Читаемая/записываемая [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию о восточноазиатском шрифте. Null означает, что шрифт не определен и должен наследоваться от мастера. Читаемая/записываемая [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства эффекта форматирования текста. Наследование не применяется. Только для чтения [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или задает текст надстрочным или подстрочным. Значение от -100% (подстрочный) до 100% (надстрочный). **float.NaN** означает, что значение не определено и должно наследоваться от мастера. Читаемая/записываемая Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства форматирования заливки текста. Наследование не применяется. Только для чтения [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт жирным. Наследование не применяется. Читаемая/записываемая [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или задает высоту шрифта части. **float.NaN** означает, что высота не определена и должна наследоваться от мастера. Читаемая/записываемая Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, наклонный ли шрифт. Наследование не применяется. Читаемая/записываемая [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Читаемая/записываемая [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Читаемая/записываемая [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Читаемая/записываемая [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого должно быть включено кернинг. **float.NaN** означает, что значение не определено и должно наследоваться от мастера. Читаемая/записываемая Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли цифры игнорировать макет текста вертикального текста, специфичный для восточных языков. Наследование не применяется. Читаемая/записываемая [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или задает идентификатор языка проверки. Используется для проверки правописания и грамматики. Читаемая/записываемая строка. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определен и должен наследоваться от мастера. Читаемая/записываемая [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для обрамления текста. Наследование не применяется. Только для чтения [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Читаемая/записываемая [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, не должен ли текст проходить проверку. Наследование не применяется. Читаемая/записываемая [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или задает интервал между символами. **float.NaN** означает, что значение не определено и должно наследоваться от мастера. Читаемая/записываемая Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или задает тип зачеркивания текста. Наследование не применяется. Читаемая/записываемая [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определен и должен наследоваться от мастера. Читаемая/записываемая [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Читаемая/записываемая [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для обрамления линии подчеркивания. Наследование не применяется. Только для чтения [`ILineFormat`](../../aspose.slides/ilineformat). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает код хеширования. |

### Примечания

Этот класс используется для получения и изменения свойств форматирования текста, определенных для конкретной части. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие "неопределено".

Чтобы получить эффективные параметры форматирования, включая унаследованные, необходимо использовать метод [`GetEffective`](../../aspose.slides/portionformat/geteffective), который возвращает экземпляр [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### См. также

* класс [BasePortionFormat](../../aspose.slides/baseportionformat)
* интерфейс [IChartPortionFormat](../ichartportionformat)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->