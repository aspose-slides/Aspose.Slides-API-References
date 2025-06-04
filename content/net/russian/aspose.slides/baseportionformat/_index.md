---
title: BasePortionFormat
second_title: Aspose.Slides для .NET API Reference
description: Общие свойства форматирования текстовых частей.
type: docs
weight: 890
url: /ru/aspose.slides/baseportionformat/
---

## BasePortionFormat class

Общие свойства форматирования текстовых частей.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает Id альтернативного языка. Чтение/запись String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о шрифте для сложных скриптов. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию о шрифте Восточной Азии. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства EffectFormat текста. Наследование не применяется. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или задает текст верхнего или нижнего индекса. Значение от -100% (нижний индекс) до 100% (верхний индекс). **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт жирным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или задает высоту шрифта части. **float.NaN** означает, что высота не определена и должна наследоваться от Мастера. Чтение/запись Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания свои собственные свойства FillFormat или наследует их от FillFormat свойств текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания свои собственные свойства LineFormat или наследует их от LineFormat свойств текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого должен быть включен кернинг. **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную компоновку текста. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или задает Id языка проверки. Используется для проверки правописания и грамматики. Чтение/запись String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для обрамления текста. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, не должен ли текст быть проверен. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или задает увеличение межсимвольного интервала. **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или задает тип зачеркивания текста. Наследование не применяется. Чтение/запись [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для обрамления линии подчеркивания. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хеш-код. |

### See Also

* class [PVIObject](../pviobject)
* interface [IBasePortionFormat](../ibaseportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->