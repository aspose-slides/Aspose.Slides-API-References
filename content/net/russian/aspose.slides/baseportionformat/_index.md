---
title: BasePortionFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Свойства форматирования текстовой порции.
type: docs
weight: 890
url: /ru/aspose.slides/baseportionformat/
---

## Класс BasePortionFormat

Общие свойства форматирования текстовых порций.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или устанавливает идентификатор альтернативного языка. Чтение/запись String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или устанавливает информацию о шрифте для сложных сценариев. Null означает, что шрифт не определен и должен быть унаследован от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или устанавливает информацию о шрифте восточноазиатского типа. Null означает, что шрифт не определен и должен быть унаследован от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства EffectFormat текста. Наследование не применяется. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или устанавливает текст верхнего или нижнего индекса. Значение от -100% (нижний индекс) до 100% (верхний индекс). **float.NaN** означает, что значение не определено и должно быть унаследовано от Master. Чтение/запись Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт жирным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или устанавливает высоту шрифта порции. **float.NaN** означает, что высота не определена и должна быть унаследована от Master. Чтение/запись Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или устанавливает тип подчеркивания текста. Наследование не применяется. Чтение/запись [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или устанавливает минимальный размер шрифта, для которого должно быть включено кернинг. **float.NaN** означает, что значение не определено и должно быть унаследовано от Master. Чтение/запись Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли цифры игнорировать специфическую для восточных языков ориентацию текста. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или устанавливает идентификатор языка проверки. Используется для проверки правописания и грамматики. Чтение/запись String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или устанавливает информацию о латинском шрифте. Null означает, что шрифт не определен и должен быть унаследован от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для обводки текста. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, следует ли нормализовать высоту текста. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, не должен ли текст быть проверен. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или устанавливает интервал между символами. **float.NaN** означает, что значение не определено и должно быть унаследовано от Master. Чтение/запись Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или устанавливает тип зачеркивания текста. Наследование не применяется. Чтение/запись [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или устанавливает информацию о символическом шрифте. Null означает, что шрифт не определен и должен быть унаследован от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или устанавливает тип капитализации текста. Наследование не применяется. Чтение/запись [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для обводки линии подчеркивания. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IBasePortionFormat](../ibaseportionformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->