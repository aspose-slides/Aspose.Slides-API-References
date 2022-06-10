---
title: ChartPortionFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Этот класс содержит свойства форматирования частей диаграммы используемые в диаграммах. В отличие отIPortionFormatEffectiveData../aspose.slides/iportionformateffectivedataвсе свойства этого класса доступны для записи.
type: docs
weight: 1290
url: /ru/net/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat class

Этот класс содержит свойства форматирования частей диаграммы, используемые в диаграммах. В отличие от[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)все свойства этого класса доступны для записи.

```csharp
public class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает идентификатор альтернативного языка. Чтение/записьString. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения[`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или устанавливает информацию о сложном шрифте сценария. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или устанавливает информацию о восточноазиатском шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства текста EffectFormat. Наследование не применяется. Только для чтения[`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или задает текст верхнего или нижнего индекса. Значение от -100% (нижний индекс) до 100% (верхний индекс).  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения[`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт полужирным. Наследование не применяется. Чтение/запись[`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или устанавливает высоту шрифта части.  **float.NaN** означает, что высота не определена и должна быть унаследована от Мастера. Чтение/записьSingle. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись[`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись[`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения[`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Чтение/запись[`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Чтение/запись[`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого должен быть включен кернинг.  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли числа игнорировать вертикальное расположение текста для восточного языка. Наследование не применяется. Чтение/запись[`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или задает идентификатор языка проверки правописания. Используется для проверки орфографии и грамматики. Чтение/записьString. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или устанавливает информацию о латинском шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для обводки текста. Наследование не применяется. Только для чтения[`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, следует ли нормализовать высоту текста. Наследование не применяется. Чтение/запись[`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, нужно ли проверять текст. Наследование не применяется. Чтение/запись[`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или задает приращение межсимвольного интервала.  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или задает зачеркивание текста. Наследование не применяется. Чтение/запись[`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или устанавливает информацию о символическом шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись[`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения[`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для выделения линии подчеркивания. Наследование не применяется. Только для чтения[`ILineFormat`](../../aspose.slides/ilineformat). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### Примечания

Этот класс используется для возврата и управления форматированием текстовой части свойствами определяется для конкретной части. Это означает, что при получении значений не применяется наследование, поэтому в большинстве случаев вы получите значения, означающие "undefined".

Чтобы получить эффективные значения параметров форматирования, включая унаследованные , вам необходимо использовать[`GetEffective`](../../aspose.slides/portionformat/geteffective)метод который возвращает экземпляр[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Смотрите также

* class [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
