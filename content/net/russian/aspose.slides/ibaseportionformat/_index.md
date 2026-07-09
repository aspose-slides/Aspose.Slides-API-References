---
title: IBasePortionFormat
second_title: Aspose.Sildes для .NET справка по API
description: Этот класс содержит свойства форматирования текстовой части. В отличие от IPortionFormatEffectiveData./iportionformateffectivedata, все свойства этого класса доступны для записи.
type: docs
weight: 5310
url: /ru/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat интерфейс

Этот класс содержит свойства форматирования текстовой части. В отличие от [`IPortionFormatEffectiveData`](../iportionformateffectivedata), все свойства этого класса доступны для записи.

```csharp
public interface IBasePortionFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает идентификатор альтернативного языка. Чтение/запись String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о шрифте сложных скриптов. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию о шрифте восточно-азиатского языка. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Возвращает свойства текстового EffectFormat. Наследование не применяется. Только чтение [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Возвращает или задает надстрочный или подстрочный текст. Значение от -100 % (подстрочный) до 100 % (надстрочный). **float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Возвращает свойства текстового FillFormat. Наследование не применяется. Только чтение [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт полужирным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Возвращает или задает высоту шрифта части. **float.NaN** означает, что высота не определена и должна наследоваться от Master. Чтение/запись Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчёркивания текста. Наследование не применяется. Чтение/запись [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для подсветки текста. Наследование не применяется. Только чтение [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчёркивания собственные свойства FillFormat или наследует их из FillFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчёркивания собственные свойства LineFormat или наследует их из LineFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, при котором включается кернинг. **float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Определяет, должны ли числа игнорировать вертикальное расположение текста, специфическое для восточных языков. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Возвращает или задает идентификатор языка корректуры. Используется для проверки орфографии и грамматики. Чтение/запись String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для обводки текста. Наследование не применяется. Только чтение [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Определяет, не должна ли проверяться орфография текста. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Возвращает или задает приращение межсимвольного интервала. **float.NaN** означает, что значение не определено и должно наследоваться от Master. Чтение/запись Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Получает или задает значение, указывающее, включена ли проверка правописания для части текста. При установке свойства в false проверки орфографии для текстовых элементов подавляются. При установке в true проверка разрешена. Значение по умолчанию `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Возвращает или задает тип зачёркивания текста. Наследование не применяется. Чтение/запись [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчёркивания. Наследование не применяется. Только чтение [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для обводки линии подчёркивания. Наследование не применяется. Только чтение [`ILineFormat`](../ilineformat). |

### Примечание

Этот класс используется для получения и изменения свойств форматирования текстовых частей, определённых для конкретной части. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [`GetEffective`](../iportionformat/geteffective) , который возвращает экземпляр [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Смотрите также

* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->