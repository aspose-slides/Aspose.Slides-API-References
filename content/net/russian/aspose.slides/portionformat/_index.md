---
title: PortionFormat
second_title: Aspose.Sildes для .NET — справочник API
description: Этот класс содержит свойства форматирования частей текста. В отличие от IPortionFormatEffectiveData./iportionformateffectivedata, все свойства этого класса доступны для записи.
type: docs
weight: 9490
url: /ru/aspose.slides/portionformat/
---
## PortionFormat класс

Этот класс содержит свойства форматирования частей текста. В отличие от [`IPortionFormatEffectiveData`](../iportionformateffectivedata), все свойства этого класса доступны для записи.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PortionFormat](portionformat)() | Инициализирует новый экземпляр класса [`PortionFormat`](../portionformat). |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает Id альтернативного языка. Чтение/запись String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только чтение [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Возвращает или задает идентификатор закладки. Чтение/запись String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о шрифте сложных сценариев. Null означает, что шрифт не определён и должен быть унаследован от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию о восточноазиатском шрифте. Null означает, что шрифт не определён и должен быть унаследован от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства EffectFormat текста. Наследование не применяется. Только чтение [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или задает надстрочный или подстрочный текст. Значение от -100 % (подстрочный) до 100 % (надстрочный). **float.NaN** означает, что значение не определено и должно быть унаследовано от Master. Чтение/запись Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства FillFormat текста. Наследование не применяется. Только чтение [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт полужирным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или задает высоту шрифта части текста. **float.NaN** означает, что высота не определена и должна быть унаследована от Master. Чтение/запись Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчёркивания текста. Наследование не применяется. Чтение/запись [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только чтение [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определённую для щелчка мышью. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Менеджер гиперссылок. Только чтение [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определённую для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчёркивания собственные свойства FillFormat или наследует их из FillFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчёркивания собственные свойства LineFormat или наследует их из LineFormat текста. Чтение/запись [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, при котором включается кернинг. **float.NaN** означает, что значение не определено и должно быть унаследовано от Master. Чтение/запись Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли числа игнорировать вертикальное расположение текста, специфичное для восточных языков. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или задает Id языка проверки. Используется для проверки орфографии и грамматики. Чтение/запись String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определён и должен быть унаследован от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства LineFormat для обводки текста. Наследование не применяется. Только чтение [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста нормализоваться. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, не следует ли проверять текст. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Определяет, следует ли очищать интеллектуальную метку. Наследование не применяется. Чтение/запись Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или задает приращение межсимвольного интервала. **float.NaN** означает, что значение не определено и должно быть унаследовано от Master. Чтение/запись Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Получает или задаёт значение, указывающее, включена ли проверка орфографии для части текста. При значении false проверка орфографии для текстовых элементов подавляется. При значении true проверка допускается. Значение по умолчанию `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или задает тип зачеркивания текста. Наследование не применяется. Чтение/запись [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определён и должен быть унаследован от Master. Чтение/запись [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Чтение/запись [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчёркивания. Наследование не применяется. Только чтение [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для обводки линии подчёркивания. Наследование не применяется. Только чтение [`ILineFormat`](../ilineformat). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Получает эффективные данные форматирования части с применением наследования. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает код хэша. |

### Примечания

Этот класс используется для получения и управления свойствами форматирования части текста, определёнными для конкретной части. Это значит, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «не определено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Примеры

Следующий пример показывает, как назначить латинский шрифт части Paragraph в презентации PowerPoint.

```csharp
[C#]
//Создайте объект презентации, представляющий файл презентации
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides использует эти специальные идентификаторы (аналогичные используемым в PowerPoint):
// +mn-lt - Шрифт тела Latin (второстепенный шрифт Latin)
// +mj-lt - Шрифт заголовка Latin (основной шрифт Latin)
// +mn-ea - Шрифт тела East Asian (второстепенный шрифт East Asian)
// +mj-ea - Шрифт тела East Asian (второстепенный шрифт East Asian)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Смотрите также

* класс [BasePortionFormat](../baseportionformat)
* интерфейс [IPortionFormat](../iportionformat)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->