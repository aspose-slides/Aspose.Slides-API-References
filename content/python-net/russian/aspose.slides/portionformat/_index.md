---
title: PortionFormat class
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides/portionformat/
---
## PortionFormat класс

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

**Inheritance:**[`PortionFormat`](/slides/python-net/ru/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/ru/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)

The PortionFormat type exposes the following members:

## Конструкторы

| Constructor | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/portionformat/__init__/#) | Инициализирует новый экземпляр класса [`PortionFormat`](/slides/python-net/ru/aspose.slides/portionformat). |

## Свойства

| Property | Описание |
| :- | :- |
| [`line_format`](/slides/python-net/ru/aspose.slides/portionformat/line_format/) | Возвращает свойства LineFormat для контурного отображения текста. Наследование не применяется.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/portionformat/fill_format/) | Возвращает свойства FillFormat текста. Наследование не применяется.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/portionformat/effect_format/) | Возвращает свойства EffectFormat текста. Наследование не применяется.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/ru/aspose.slides/portionformat/highlight_color/) | Возвращает цвет, используемый для выделения текста. Наследование не применяется.<br/>            Только для чтения [`IColorFormat`](/slides/python-net/ru/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/ru/aspose.slides/portionformat/underline_line_format/) | Возвращает свойства LineFormat, используемые для контурного отображения подчеркивающей линии. Наследование не применяется.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/ru/aspose.slides/portionformat/underline_fill_format/) | Возвращает свойства FillFormat подчеркивающей линии. Наследование не применяется.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/ru/aspose.slides/portionformat/font_bold/) | Определяет, жирный ли шрифт. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/ru/aspose.slides/portionformat/font_italic/) | Определяет, курсивный ли шрифт. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/ru/aspose.slides/portionformat/kumimoji/) | Определяет, должны ли номера игнорировать специфическую для восточно-азиатских языков вертикальную раскладку текста. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/ru/aspose.slides/portionformat/normalise_height/) | Определяет, должна ли высота текста быть нормализована. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/ru/aspose.slides/portionformat/proof_disabled/) | Определяет, не следует ли проверять текст. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/ru/aspose.slides/portionformat/font_underline/) | Возвращает или задает тип подчеркивания текста. Наследование не применяется.<br/>            Чтение/запись [`TextUnderlineType`](/slides/python-net/ru/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/ru/aspose.slides/portionformat/text_cap_type/) | Возвращает или задает тип буквенного регистра текста. Наследование не применяется.<br/>            Чтение/запись [`TextCapType`](/slides/python-net/ru/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/ru/aspose.slides/portionformat/strikethrough_type/) | Возвращает или задает тип зачеркивания текста. Наследование не применяется.<br/>            Чтение/запись [`TextStrikethroughType`](/slides/python-net/ru/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/ru/aspose.slides/portionformat/is_hard_underline_line/) | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их<br/>            от свойств LineFormat текста.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/ru/aspose.slides/portionformat/is_hard_underline_fill/) | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их<br/>            от свойств FillFormat текста.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/ru/aspose.slides/portionformat/font_height/) | Возвращает или задает высоту шрифта части.<br/>            **float.NaN**  означает, что высота не определена и должна наследоваться от Master.<br/>            Чтение/запись **float**. |
| [`latin_font`](/slides/python-net/ru/aspose.slides/portionformat/latin_font/) | Возвращает или задает информацию о латинском шрифте.<br/>            Null означает, что шрифт не определен и должен наследоваться от Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/ru/aspose.slides/portionformat/east_asian_font/) | Возвращает или задает информацию о восточно-азиатском шрифте.<br/>            Null означает, что шрифт не определен и должен наследоваться от Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/ru/aspose.slides/portionformat/complex_script_font/) | Возвращает или задает информацию о шрифте сложных сценариев.<br/>            Null означает, что шрифт не определен и должен наследоваться от Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/ru/aspose.slides/portionformat/symbol_font/) | Возвращает или задает информацию о символическом шрифте.<br/>            Null означает, что шрифт не определен и должен наследоваться от Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/ru/aspose.slides/portionformat/escapement/) | Возвращает или задает надстрочный или подстрочный текст.<br/>            Значение от -100 % (подстрочный) до 100 % (надстрочный).<br/>            **float.NaN**  означает, что значение не определено и должно наследоваться от Master.<br/>            Чтение/запись **float**. |
| [`kerning_minimal_size`](/slides/python-net/ru/aspose.slides/portionformat/kerning_minimal_size/) | Возвращает или задает минимальный размер шрифта, при котором включается кернинг.<br/>            **float.NaN**  означает, что значение не определено и должно наследоваться от Master.<br/>            Чтение/запись **float**. |
| [`language_id`](/slides/python-net/ru/aspose.slides/portionformat/language_id/) | Возвращает или задает идентификатор языка проверки. Используется для проверки орфографии и грамматики.<br/>            Чтение/запись **str**. |
| [`alternative_language_id`](/slides/python-net/ru/aspose.slides/portionformat/alternative_language_id/) | Возвращает или задает идентификатор альтернативного языка.<br/>            Чтение/запись **str**. |
| [`spacing`](/slides/python-net/ru/aspose.slides/portionformat/spacing/) | Возвращает или задает прирост межсимвольного интервала.<br/>            **float.NaN**  означает, что значение не определено и должно наследоваться от Master.<br/>            Чтение/запись **float**. |
| [`spell_check`](/slides/python-net/ru/aspose.slides/portionformat/spell_check/) | Получает или задает значение, указывающее, включена ли проверка орфографии для части текста.<br/>            Когда это свойство установлено в false, проверка орфографии для текстовых элементов подавляется.<br/>            Когда установлено в true, проверка орфографии разрешена.<br/>            Значение по умолчанию `false`. |
| [`bookmark_id`](/slides/python-net/ru/aspose.slides/portionformat/bookmark_id/) | Возвращает или задает идентификатор закладки.<br/>            Чтение/запись **str**. |
| [`smart_tag_clean`](/slides/python-net/ru/aspose.slides/portionformat/smart_tag_clean/) | Определяет, следует ли очищать смарт-тег. Наследование не применяется.<br/>            Чтение/запись **bool**. |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/portionformat/hyperlink_click/) | Возвращает или задает гиперссылку, определенную для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/portionformat/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определенную для наведения мыши.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/portionformat/hyperlink_manager/) | Менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/ru/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/portionformat/presentation/) |  |

## Методы

| Method | Описание |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ru/aspose.slides/portionformat/get_effective/#) | Получает эффективные данные форматирования части с примененным наследованием. |

### Примечания

Этот класс используется для получения и изменения свойств форматирования текста, определённых для конкретной части. Это означает, что
            при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [`PortionFormat.get_effective`](/slides/python-net/ru/aspose.slides/portionformat/get_effective) 
            который возвращает экземпляр [`IPortionFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iportionformateffectivedata).

### Смотрите также
* класс [`BasePortionFormat`](/slides/python-net/ru/aspose.slides/baseportionformat)
* класс [`IPortionFormatEffectiveData`](/slides/python-net/ru/aspose.slides/iportionformateffectivedata)
* класс [`PortionFormat`](/slides/python-net/ru/aspose.slides/portionformat)
* класс [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)