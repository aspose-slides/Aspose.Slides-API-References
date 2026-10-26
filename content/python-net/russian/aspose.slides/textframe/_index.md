---
title: TextFrame class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/textframe/
---
## TextFrame класс

Represents a TextFrame.

The TextFrame type exposes the following members:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`paragraphs`](/slides/python-net/ru/aspose.slides/textframe/paragraphs/) | Returns the list of all paragraphs in a frame.<br/>            Только для чтения [`IParagraphCollection`](/slides/python-net/ru/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ru/aspose.slides/textframe/text/) | Получает или задает обычный текст для TextFrame.<br/>            Чтение/запись **str**. |
| [`text_frame_format`](/slides/python-net/ru/aspose.slides/textframe/text_frame_format/) | Возвращает объект форматирования для этого объекта TextFrame.<br/>            Только для чтения [`ITextFrameFormat`](/slides/python-net/ru/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/textframe/hyperlink_queries/) | Обеспечивает простой доступ к содержащимся гиперссылкам.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/ru/aspose.slides/textframe/slide/) | Возвращает родительский слайд TextFrame.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/textframe/presentation/) | Возвращает родительскую презентацию TextFrame.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/ru/aspose.slides/textframe/parent_shape/) | Возвращает родительскую форму или None, если родительский объект не реализует интерфейс IShape<br/>            Только для чтения [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ru/aspose.slides/textframe/parent_cell/) | Возвращает родительскую ячейку или None, если родительский объект не реализует интерфейс ICell.<br/>            Только для чтения [`ICell`](/slides/python-net/ru/aspose.slides/icell). |

## Методы

| Метод | Описание |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ru/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Выделяет все совпадения образца текста указанным цветом. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ru/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Выделяет все совпадения образца текста указанным цветом. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ru/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Выделяет все совпадения образца текста указанным цветом. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ru/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Выделяет все совпадения регулярного выражения указанным цветом. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ru/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Выделяет все совпадения регулярного выражения указанным цветом. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/textframe/join_portions_with_same_formatting/#) | Объединяет участки с одинаковым форматированием во всех абзацах. |
| [`split_text_by_columns(self)`](/slides/python-net/ru/aspose.slides/textframe/split_text_by_columns/#) | Разделяет текстовое содержимое [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe) на массив строк,  <br/>            где каждый элемент соответствует отдельному текстовому столбцу внутри кадра. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ru/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ru/aspose.slides/textframe/replace_regex/#str-str) | Заменяет все совпадения регулярного выражения указанной строкой. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)