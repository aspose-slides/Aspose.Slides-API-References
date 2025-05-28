---
title: IBasePortionFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Этот класс содержит свойства форматирования текстовой части. В отличие отIPortionFormatEffectiveData./iportionformateffectivedataвсе свойства этого класса доступны для записи.
type: docs
weight: 4830
url: /ru/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

Этот класс содержит свойства форматирования текстовой части. В отличие от[`IPortionFormatEffectiveData`](../iportionformateffectivedata)все свойства этого класса доступны для записи.

```csharp
public interface IBasePortionFormat
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает идентификатор альтернативного языка. Чтение/записьString. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Возвращает или устанавливает информацию о сложном шрифте сценария. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Возвращает или устанавливает информацию о восточноазиатском шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Возвращает свойства текста EffectFormat. Наследование не применяется. Только для чтения[`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Возвращает или задает текст верхнего или нижнего индекса. Значение от -100% (нижний индекс) до 100% (верхний индекс).  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения[`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт полужирным. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Возвращает или устанавливает высоту шрифта части.  **float.NaN** означает, что высота не определена и должна быть унаследована от Мастера. Чтение/записьSingle. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись[`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения[`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Чтение/запись[`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Чтение/запись[`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого должен быть включен кернинг.  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Определяет, должны ли числа игнорировать вертикальное расположение текста для восточного языка. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Возвращает или задает идентификатор языка проверки правописания. Используется для проверки орфографии и грамматики. Чтение/записьString. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Возвращает или устанавливает информацию о латинском шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для обводки текста. Наследование не применяется. Только для чтения[`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Определяет, следует ли нормализовать высоту текста. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Определяет, нужно ли проверять текст. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Возвращает или задает приращение межсимвольного интервала.  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Возвращает или задает зачеркивание текста. Наследование не применяется. Чтение/запись[`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Возвращает или устанавливает информацию о символическом шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись[`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения[`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для выделения линии подчеркивания. Наследование не применяется. Только для чтения[`ILineFormat`](../ilineformat). |

### Примечания

Этот класс используется для возврата и управления свойствами форматирования текстовой части, определенными для конкретной части. Это означает, что при получении значений не применяется наследование, поэтому в большинстве случаев вы получите значения, означающие «неопределенные».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, вам необходимо использовать метод[`GetEffective`](../iportionformat/geteffective) который возвращает экземпляр[`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
