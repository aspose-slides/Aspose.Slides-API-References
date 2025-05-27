---
title: IBasePortionFormat
second_title: Aspose.Slides для .NET API Справочник
description: Этот класс содержит свойства форматирования текстовой части. В отличие от IPortionFormatEffectiveData, все свойства этого класса доступны для записи.
type: docs
weight: 5110
url: /ru/aspose.slides/ibaseportionformat/
---

## Интерфейс IBasePortionFormat

Этот класс содержит свойства форматирования текстовой части. В отличие от [`IPortionFormatEffectiveData`](../iportionformateffectivedata), все свойства этого класса доступны для записи.

```csharp
public interface IBasePortionFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает идентификатор альтернативного языка. Чтение/запись Строка. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о шрифте сложного скрипта. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию о восточноазиатском шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Возвращает свойства форматирования текста. Наследование не применяется. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Возвращает или задает надстрочный или подстрочный текст. Значение от -100% (подстрочный) до 100% (надстрочный). **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Возвращает свойства форматирования заливки текста. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт жирным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Возвращает или задает высоту шрифта части. **float.NaN** означает, что высота не определена и должна наследоваться от Мастера. Чтение/запись Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания свои собственные свойства форматирования заливки или наследует их от свойств форматирования заливки текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания свои собственные свойства форматирования линии или наследует их от свойств форматирования линии текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого следует включить кернинг. **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Определяет, должны ли числа игнорировать специфическую для восточного языка вертикальную раскладку текста. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Возвращает или задает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Чтение/запись Строка. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Возвращает свойства форматирования линии для обводки текста. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Определяет, не должен ли текст проверяться. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Возвращает или задает увеличение межсимвольного интервала. **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Возвращает или задает тип зачеркивания текста. Наследование не применяется. Чтение/запись [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Возвращает свойства форматирования заливки линии подчеркивания. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Возвращает свойства форматирования линии, используемые для обводки линии подчеркивания. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |

### Примечания

Этот класс используется для возврата и манипуляции свойствами форматирования текстовых частей, определяемыми для конкретной части. Это означает, что наследование не применяется при получении значений, поэтому в большинстве случаев вы получите значения, означающие "неопределенное".

Чтобы получить значения эффективных параметров форматирования, включая унаследованные, вам нужно использовать метод [`GetEffective`](../iportionformat/geteffective), который возвращает экземпляр [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### См. также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->