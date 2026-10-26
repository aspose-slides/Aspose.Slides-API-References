---
title: ITextFrame class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/itextframe/
---
## ITextFrame класс

Представляет TextFrame.

Тип ITextFrame содержит следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`paragraphs`](/slides/python-net/ru/aspose.slides/itextframe/paragraphs/) | Возвращает список всех абзацев в кадре.<br/>            Только для чтения [`IParagraphCollection`](/slides/python-net/ru/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ru/aspose.slides/itextframe/text/) | Получает или задает обычный текст для TextFrame.<br/>            Чтение/запись **str**. |
| [`text_frame_format`](/slides/python-net/ru/aspose.slides/itextframe/text_frame_format/) | Возвращает объект форматирования для этого объекта TextFrame.<br/>            Только для чтения [`ITextFrameFormat`](/slides/python-net/ru/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/itextframe/hyperlink_queries/) | Обеспечивает простой доступ к содержащимся гиперссылкам.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/ru/aspose.slides/itextframe/parent_shape/) | Возвращает родительскую форму или None, если родительский объект не реализует интерфейс IShape<br/>            Только для чтения [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ru/aspose.slides/itextframe/parent_cell/) | Возвращает родительскую ячейку или None, если родительский объект не реализует интерфейс ICell.<br/>            Только для чтения [`ICell`](/slides/python-net/ru/aspose.slides/icell). |
| [`slide`](/slides/python-net/ru/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/itextframe/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Выделяет все совпадения образца текста заданным цветом. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Выделяет все совпадения образца текста заданным цветом. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Выделяет все совпадения образца текста заданным цветом. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Выделяет все совпадения регулярного выражения заданным цветом. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ru/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Выделяет все совпадения регулярного выражения заданным цветом. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Объединяет участки с одинаковым форматированием во всех абзацах. |
| [`split_text_by_columns(self)`](/slides/python-net/ru/aspose.slides/itextframe/split_text_by_columns/#) | Разделяет текстовое содержание [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe) на массив строк,  <br/>            где каждый элемент соответствует отдельному текстовому столбцу внутри кадра. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ru/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ru/aspose.slides/itextframe/replace_regex/#str-str) | Заменяет все совпадения регулярного выражения указанной строкой. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)