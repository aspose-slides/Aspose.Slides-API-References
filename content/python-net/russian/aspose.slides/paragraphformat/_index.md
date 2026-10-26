---
title: ParagraphFormat class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/paragraphformat/
---
## ParagraphFormat класс

Этот класс содержит свойства форматирования абзаца. В отличие от [`IParagraphFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iparagraphformateffectivedata), все свойства этого класса доступны для записи.

**Наследование:**[`ParagraphFormat`](/slides/python-net/ru/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)

Тип ParagraphFormat предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/paragraphformat/__init__/#) | Инициализирует новый экземпляр класса [`ParagraphFormat`](/slides/python-net/ru/aspose.slides/paragraphformat). |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`alignment`](/slides/python-net/ru/aspose.slides/paragraphformat/alignment/) | Возвращает или задает выравнивание текста в абзаце без наследования.<br/>            Чтение/запись [`TextAlignment`](/slides/python-net/ru/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/ru/aspose.slides/paragraphformat/space_within/) | Возвращает или задает величину расстояния между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется.<br/>            Чтение/запись **float**. |
| [`space_before`](/slides/python-net/ru/aspose.slides/paragraphformat/space_before/) | Возвращает или задает величину пространства перед первой строкой в абзаце без наследования.<br/>            Положительное значение указывает процент от размера шрифта, который должен занимать пробел.<br/>            Отрицательное значение указывает размер пробела в пунктах.<br/>            Чтение/запись **float**. |
| [`space_after`](/slides/python-net/ru/aspose.slides/paragraphformat/space_after/) | Возвращает или задает величину пространства после последней строки в абзаце без наследования.<br/>            Положительное значение указывает процент от размера шрифта, который должен занимать пробел.<br/>            Отрицательное значение указывает размер пробела в пунктах.<br/>            Чтение/запись **float**. |
| [`east_asian_line_break`](/slides/python-net/ru/aspose.slides/paragraphformat/east_asian_line_break/) | Определяет, используется ли разрыв строки восточноазиатского типа в абзаце. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/ru/aspose.slides/paragraphformat/right_to_left/) | Определяет, используется ли направление письма справа налево в абзаце. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/ru/aspose.slides/paragraphformat/latin_line_break/) | Определяет, используется ли разрыв строки латинского типа в абзаце. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/ru/aspose.slides/paragraphformat/hanging_punctuation/) | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/ru/aspose.slides/paragraphformat/margin_left/) | Возвращает или задает левый отступ в абзаце без наследования.<br/>            Чтение/запись **float**. |
| [`margin_right`](/slides/python-net/ru/aspose.slides/paragraphformat/margin_right/) | Возвращает или задает правый отступ в абзаце без наследования.<br/>            Чтение/запись **float**. |
| [`indent`](/slides/python-net/ru/aspose.slides/paragraphformat/indent/) | Возвращает или задает отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может задаваться отрицательными значениями.<br/>            Чтение/запись **float**. |
| [`default_tab_size`](/slides/python-net/ru/aspose.slides/paragraphformat/default_tab_size/) | Возвращает или задает размер табуляции по умолчанию без наследования.<br/>            Чтение/запись **float**. |
| [`tabs`](/slides/python-net/ru/aspose.slides/paragraphformat/tabs/) | Возвращает табуляции абзаца. Наследование не применяется.<br/>            Только чтение [`ITabCollection`](/slides/python-net/ru/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/ru/aspose.slides/paragraphformat/font_alignment/) | Возвращает или задает выравнивание шрифта в абзаце без наследования.<br/>            Чтение/запись [`FontAlignment`](/slides/python-net/ru/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/ru/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/ru/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/ru/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/ru/aspose.slides/paragraphformat/default_portion_format/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ru/aspose.slides/paragraphformat/get_effective/#) | Получает эффективные данные форматирования абзаца с учётом наследования. |

### Примечания

Этот класс используется для получения и изменения свойств форматирования абзаца, определённых для конкретного абзаца. Это означает, что
            при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие \"неопределено\".

Чтобы получить эффективные значения параметров форматирования, включая наследованные, необходимо использовать метод [`ParagraphFormat.get_effective`](/slides/python-net/ru/aspose.slides/paragraphformat/get_effective)
            который возвращает экземпляр [`IParagraphFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iparagraphformateffectivedata).

### См. также
* класс [`IParagraphFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iparagraphformateffectivedata)
* класс [`ParagraphFormat`](/slides/python-net/ru/aspose.slides/paragraphformat)
* класс [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)