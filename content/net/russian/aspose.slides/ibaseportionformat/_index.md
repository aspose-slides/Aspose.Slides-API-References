---
title: IBasePortionFormat
second_title: Aspose.Slides для .NET API Справочник
description: Этот класс содержит свойства форматирования текстовых частей. В отличие от IPortionFormatEffectiveData все свойства этого класса доступны для записи.
type: docs
weight: 5110
url: /ru/aspose.slides/ibaseportionformat/
---

## Интерфейс IBasePortionFormat

Этот класс содержит свойства форматирования текстовых частей. В отличие от [`IPortionFormatEffectiveData`](../iportionformateffectivedata), все свойства этого класса доступны для записи.

```csharp
public interface IBasePortionFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает идентификатор альтернативного языка. Чтение/запись String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о сложном шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию об восточноазиатском шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Возвращает свойства EffectFormat текста. Наследование не применяется. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Возвращает или задает текст в верхнем или нижнем регистре. Значение от -100% (нижний регистр) до 100% (верхний регистр). **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Определяет, жирный ли шрифт. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Возвращает или задает высоту шрифта части. **float.NaN** означает, что высота не определена и должна наследоваться от Мастера. Чтение/запись Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Определяет, курсивный ли шрифт. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Чтение/запись [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого должно быть включено кернинг. **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Определяет, должны ли числа игнорировать вертикальную раскладку текста, специфичную для восточных языков. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Возвращает или задает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Чтение/запись String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для контурирования текста. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Определяет, не должна ли текст проверяться. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Возвращает или задает интервал между символами. **float.NaN** означает, что значение не определено и должно наследоваться от Мастера. Чтение/запись Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Возвращает или задает тип зачеркивания текста. Наследование не применяется. Чтение/запись [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определен и должен наследоваться от Мастера. Чтение/запись [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat для линии подчеркивания текста. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для обрисовки линии подчеркивания. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |

### Примечания

Этот класс используется для возврата и манипуляции свойствами форматирования текстовых частей, определенными для конкретной части. Это означает, что наследование не применяется при получении значений, поэтому в большинстве случаев вы получите значения, означающие "неопределено".

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, вам необходимо использовать метод [`GetEffective`](../iportionformat/geteffective), который возвращает экземпляр [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->