---
title: PortionFormat
second_title: Aspose.Sildes для .NET API Справочник
description: Этот класс содержит свойства форматирования текстовых порций. В отличие от IPortionFormatEffectiveData../iportionformateffectivedata, все свойства этого класса могут быть записаны.
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

| Имя | Описание |
| --- | --- |
| [PortionFormat](portionformat)() | Инициализирует новый экземпляр класса [`PortionFormat`](../portionformat). |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Возвращает или задает идентификатор альтернативного языка. Читаемый/записываемый String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Возвращает или задает идентификатор закладки. Читаемый/записываемый String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Возвращает или задает информацию о шрифте для сложных текстов. Null означает, что шрифт не определен и должен быть унаследован от мастера. Читаемый/записываемый [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Возвращает или задает информацию о шрифте для восточноазиатских языков. Null означает, что шрифт не определен и должен быть унаследован от мастера. Читаемый/записываемый [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Возвращает свойства форматирования текста. Наследование не применяется. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Возвращает или задает текст верхнего или нижнего регистра. Значение от -100% (нижний индекс) до 100% (верхний индекс). **float.NaN** означает, что значение не определено и должно быть унаследовано от мастера. Читаемый/записываемый Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Возвращает свойства форматирования заливки текста. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Определяет, является ли шрифт жирным. Наследование не применяется. Читаемый/записываемый [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Возвращает или задает высоту шрифта порции. **float.NaN** означает, что высота не определена и должна быть унаследована от мастера. Читаемый/записываемый Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Определяет, является ли шрифт курсивным. Наследование не применяется. Читаемый/записываемый [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Возвращает или задает тип подчеркивания текста. Наследование не применяется. Читаемый/записываемый [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для клика мышью. Читаемый/записываемый [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения мыши. Читаемый/записываемый [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Определяет, имеет ли стиль подчеркивания свои собственные свойства форматирования заливки или наследует их от свойств форматирования заливки текста. Читаемый/записываемый [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Определяет, имеет ли стиль подчеркивания свои собственные свойства форматирования линии или наследует их от свойств форматирования линии текста. Читаемый/записываемый [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Возвращает или задает минимальный размер шрифта, для которого следует включить кернинг. **float.NaN** означает, что значение не определено и должно быть унаследовано от мастера. Читаемый/записываемый Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Определяет, должны ли цифры игнорировать восточноазиатскую специфику вертикального расположения текста. Наследование не применяется. Читаемый/записываемый [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Возвращает или задает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Читаемый/записываемый String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Возвращает или задает информацию о латинском шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Читаемый/записываемый [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Возвращает свойства форматирования линии для контурирования текста. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Читаемый/записываемый [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Определяет, не должен ли текст проверяться. Наследование не применяется. Читаемый/записываемый [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Определяет, должен ли смарт тег быть очищен. Наследование не применяется. Читаемый/записываемый Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Возвращает или задает интервал между символами. **float.NaN** означает, что значение не определено и должно быть унаследовано от мастера. Читаемый/записываемый Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Возвращает или задает тип зачеркивания текста. Наследование не применяется. Читаемый/записываемый [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Возвращает или задает информацию о символическом шрифте. Null означает, что шрифт не определен и должен быть унаследован от мастера. Читаемый/записываемый [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Возвращает или задает тип капитализации текста. Наследование не применяется. Читаемый/записываемый [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется. Только для чтения [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Возвращает свойства LineFormat, используемые для контурирования линии подчеркивания. Наследование не применяется. Только для чтения [`ILineFormat`](../ilineformat). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Получает эффективные данные форматирования порции с применением наследования. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### Примечания

Этот класс используется для возврата и манипуляции свойствами форматирования текстовых порций, определенными для конкретной порции. Это означает, что при получении значений наследование не применяется, и в большинстве случаев вы получите значения, означающие "не определено".

Чтобы получить значения параметров эффективного форматирования, включая унаследованные, нужно использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Примеры

Следующие примеры показывают, как назначить латинский шрифт порции абзаца презентации PowerPoint.

```csharp
[C#]
//Создайте объект презентации, представляющий файл презентации
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Формат текста темы");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides использует эти специальные идентификаторы (аналогичные тем, что используются в PowerPoint):
// +mn-lt - Основной латинский шрифт (минорный латинский шрифт)
// +mj-lt - Основной латинский шрифт (мажорный латинский шрифт)
// +mn-ea - Основной восточноазиатский шрифт (минорный восточноазиатский шрифт)
// +mj-ea - Основной восточноазиатский шрифт (мажорный восточноазиатский шрифт)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### См. также

* класс [BasePortionFormat](../baseportionformat)
* интерфейс [IPortionFormat](../iportionformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->