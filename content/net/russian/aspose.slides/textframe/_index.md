---
title: TextFrame
second_title: Aspose.Sildes для справочной информации по API .NET
description: Представляет TextFrame.
type: docs
weight: 10640
url: /ru/aspose.slides/textframe/
---

## Класс TextFrame

Представляет TextFrame.

```csharp
public sealed class TextFrame : ITextFrame
```

## Свойства

| Название | Описание |
| --- | --- |
| [HyperlinkQueries](../../aspose.slides/textframe/hyperlinkqueries) { get; } | Обеспечивает легкий доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Paragraphs](../../aspose.slides/textframe/paragraphs) { get; } | Возвращает список всех параграфов в фрейме. Только для чтения [`IParagraphCollection`](../iparagraphcollection). |
| [ParentCell](../../aspose.slides/textframe/parentcell) { get; } | Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс ICell. Только для чтения [`ICell`](../icell). |
| [ParentShape](../../aspose.slides/textframe/parentshape) { get; } | Возвращает родительскую фигуру или null, если родительский объект не реализует интерфейс IShape. Только для чтения [`IShape`](../ishape). |
| [Presentation](../../aspose.slides/textframe/presentation) { get; } | Возвращает родительскую презентацию для TextFrame. Только для чтения [`IPresentation`](../ipresentation). |
| [Slide](../../aspose.slides/textframe/slide) { get; } | Возвращает родительский слайд для TextFrame. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [Text](../../aspose.slides/textframe/text) { get; set; } | Получает или устанавливает обычный текст для TextFrame. Чтение и запись строка. |
| [TextFrameFormat](../../aspose.slides/textframe/textframeformat) { get; } | Возвращает объект форматирования для этого объекта TextFrame. Только для чтения [`ITextFrameFormat`](../itextframeformat). |

## Методы

| Название | Описание |
| --- | --- |
| [HighlightRegex](../../aspose.slides/textframe/highlightregex#highlightregex_1)(Regex, Color, IFindResultCallback) | Выделяет все совпадения регулярного выражения с указанным цветом. |
| [HighlightText](../../aspose.slides/textframe/highlighttext#highlighttext)(string, Color) | Выделяет все совпадения образца текста с указанным цветом. |
| [HighlightText](../../aspose.slides/textframe/highlighttext#highlighttext_2)(string, Color, ITextSearchOptions, IFindResultCallback) | Выделяет все совпадения образца текста с указанным цветом. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/textframe/joinportionswithsameformatting)() | Объединяет части с одинаковым форматированием во всех параграфах. |
| [ReplaceRegex](../../aspose.slides/textframe/replaceregex)(Regex, string, IFindResultCallback) | Заменяет все совпадения регулярного выражения на указанную строку. |
| [ReplaceText](../../aspose.slides/textframe/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Заменяет все вхождения указанного текста на другой указанный текст. |
| [SplitTextByColumns](../../aspose.slides/textframe/splittextbycolumns)() | Делит текстовое содержимое [`ITextFrame`](../itextframe) на массив строк, где каждый элемент соответствует отдельной текстовой колонке внутри фрейма. |

### См. также

* интерфейс [ITextFrame](../itextframe)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано с помощью xmldocmd для Aspose.Slides.dll -->