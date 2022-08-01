---
title: BasePortionFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Общие свойства форматирования текстовой части.
type: docs
weight: 870
url: /ru/net/aspose.slides/baseportionformat/
---
## BasePortionFormat class

Общие свойства форматирования текстовой части.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает идентификатор альтернативного языка. Чтение/записьString . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения[`IPresentationComponent`](../ipresentationcomponent) . |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о сложном шрифте сценария. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию о восточноазиатском шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства текста EffectFormat. Наследование не применяется. Только для чтения[`IEffectFormat`](../ieffectformat) . |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или задает текст верхнего или нижнего индекса. Значение от -100% (нижний индекс) до 100% (верхний индекс).  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle . |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения[`IFillFormat`](../ifillformat) . |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт полужирным. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool) . |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или устанавливает высоту шрифта части.  **float.NaN** означает, что высота не определена и должна быть унаследована от Мастера. Чтение/записьSingle . |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool) . |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения[`IColorFormat`](../icolorformat) . |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует его от свойств FillFormat текста. Чтение/запись[`NullableBool`](../nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует его от свойств LineFormat текста. Чтение/запись[`NullableBool`](../nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого должен быть включен кернинг.  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle . |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли числа игнорировать вертикальное расположение текста для восточного языка. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool) . |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или задает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Чтение/записьString . |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для выделения текста. Наследование не применяется. Только для чтения[`ILineFormat`](../ilineformat) . |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, следует ли нормализовать высоту текста. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool) . |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, нужно ли проверять текст. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool) . |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или задает приращение межсимвольного интервала.  **float.NaN** означает, что значение не определено и должно быть унаследовано от Мастера. Чтение/записьSingle . |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или устанавливает тип зачеркивания текста. Наследование не применяется. Чтение/запись[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или устанавливает информацию о символическом шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Чтение/запись[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения[`IFillFormat`](../ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для выделения линии подчеркивания. Наследование не применяется. Только для чтения[`ILineFormat`](../ilineformat) . |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### Смотрите также

* class [PVIObject](../pviobject)
* interface [IBasePortionFormat](../ibaseportionformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
