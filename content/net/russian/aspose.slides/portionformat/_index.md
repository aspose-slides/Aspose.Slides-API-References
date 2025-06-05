---
title: PortionFormat
second_title: Aspose.Sildes для .NET API Reference
description: Этот класс содержит свойства форматирования текстовых порций. В отличие от IPortionFormatEffectiveData, все свойства этого класса могут быть записаны.
type: docs
weight: 9220
url: /ru/aspose.slides/portionformat/
---

## Класс PortionFormat

Этот класс содержит свойства форматирования текстовых порций. В отличие от [`IPortionFormatEffectiveData`](../iportionformateffectivedata), все свойства этого класса могут быть записаны.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [PortionFormat](portionformat)() | Инициализирует новый экземпляр класса [`PortionFormat`](../portionformat). |

## Свойства

| Название | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или устанавливает идентификатор альтернативного языка. Чтение/запись строка. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Возвращает или устанавливает идентификатор закладки. Чтение/запись строка. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или устанавливает информацию о шрифте для сложного скрипта. Null означает, что шрифт не определен и должен наследоваться от главного. Чтение/запись [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или устанавливает информацию о шрифте для восточноазиатских языков. Null означает, что шрифт не определен и должен наследоваться от главного. Чтение/запись [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства EffectFormat текста. Наследование не применяется. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или устанавливает текст верхнего или нижнего индекса. Значение от -100% (нижний индекс) до 100% (верхний индекс). **float.NaN** означает, что значение не определено и должно наследоваться от главного. Чтение/запись одиночное значение. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт жирным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или устанавливает высоту шрифта порции. **float.NaN** означает, что высота не определена и должна наследоваться от главного. Чтение/запись одиночное значение. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или устанавливает тип подчеркивания текста. Наследование не применяется. Чтение/запись [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, использованный для выделения текста. Наследование не применяется. Только для чтения [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для клика мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их от свойств FillFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их от свойств LineFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или устанавливает минимальный размер шрифта, для которого следует включить кернинг. **float.NaN** означает, что значение не определено и должно наследоваться от главного. Чтение/запись одиночное значение. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли цифры игнорировать специфическую для восточных языков верстку текста. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или устанавливает идентификатор языка проверки. Используется для проверки правописания и грамматики. Чтение/запись строка. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или устанавливает информацию о латинском шрифте. Null означает, что шрифт не определен и должен наследоваться от главного. Чтение/запись [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для контурирования текста. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, не должно ли производиться проверка текста. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Определяет, должен ли умный тег быть очищен. Наследование не применяется. Чтение/запись булево значение. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или устанавливает интервал межбуквенного пробела. **float.NaN** означает, что значение не определено и должно наследоваться от главного. Чтение/запись одиночное значение. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или устанавливает тип зачеркивания текста. Наследование не применяется. Чтение/запись [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или устанавливает информацию о символьном шрифте. Null означает, что шрифт не определен и должен наследоваться от главного. Чтение/запись [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или устанавливает тип капитализации текста. Наследование не применяется. Чтение/запись [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat для линии подчеркивания. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для контурирования линии подчеркивания. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |

## Методы

| Название | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Получает эффективные данные форматирования порции с применением наследования. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хеш-код. |

### Примечания

Этот класс используется для возврата и манипуляции свойствами форматирования текстовых порций, определенными для конкретной порции. Это означает, что наследование не применяется при получении значений, поэтому в большинстве случаев вы получите значения, означающие "неопределено".

Чтобы получить эффективные параметры форматирования, включая унаследованные, вам необходимо использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Примеры

Следующие примеры показывают, как назначить латинский шрифт для порции параграфа в презентации PowerPoint.

```csharp
[C#]
//Создайте объект презентации, представляющий файл презентации
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Текстовое форматирование темы");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides использует эти специальные идентификаторы (аналогично тем, которые используются в PowerPoint):
// +mn-lt - Шрифт тела латиница (Шрифт минорной латиницы)
// +mj-lt - Шрифт заголовка латиница (Шрифт майорной латиницы)
// +mn-ea - Шрифт тела восточноазиатский (Шрифт минорного восточноазиатского)
// +mj-ea - Шрифт заголовка восточноазиатский (Шрифт майорного восточноазиатского)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Смотрите Также

* класс [BasePortionFormat](../baseportionformat)
* интерфейс [IPortionFormat](../iportionformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->