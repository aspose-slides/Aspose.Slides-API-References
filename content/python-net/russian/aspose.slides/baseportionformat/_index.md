---
title: BasePortionFormat class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/baseportionformat/
---
## BasePortionFormat класс

Общие свойства форматирования текстовых фрагментов.

**Inheritance:**[`BasePortionFormat`](/slides/python-net/ru/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)

Тип BasePortionFormat предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`line_format`](/slides/python-net/ru/aspose.slides/baseportionformat/line_format/) | Возвращает свойства LineFormat для обводки текста. Наследование не применяется.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/baseportionformat/fill_format/) | Возвращает свойства FillFormat текста. Наследование не применяется.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/baseportionformat/effect_format/) | Возвращает свойства EffectFormat текста. Наследование не применяется.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/ru/aspose.slides/baseportionformat/highlight_color/) | Возвращает цвет, используемый для выделения текста. Наследование не применяется.<br/>            Только для чтения [`IColorFormat`](/slides/python-net/ru/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/ru/aspose.slides/baseportionformat/underline_line_format/) | Возвращает свойства LineFormat, используемые для обводки линии подчеркивания. Наследование не применяется.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/ru/aspose.slides/baseportionformat/underline_fill_format/) | Возвращает свойства FillFormat линии подчеркивания. Наследование не применяется.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/ru/aspose.slides/baseportionformat/font_bold/) | Определяет, является ли шрифт жирным. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/ru/aspose.slides/baseportionformat/font_italic/) | Определяет, является ли шрифт курсивным. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/ru/aspose.slides/baseportionformat/kumimoji/) | Определяет, должны ли числа игнорировать специфическое для восточных языков вертикальное расположение текста. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/ru/aspose.slides/baseportionformat/normalise_height/) | Определяет, следует ли нормализовать высоту текста. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/ru/aspose.slides/baseportionformat/proof_disabled/) | Определяет, не следует ли проверять текст. Наследование не применяется.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/ru/aspose.slides/baseportionformat/font_underline/) | Возвращает или задает тип подчеркивания текста. Наследование не применяется.<br/>            Чтение/запись [`TextUnderlineType`](/slides/python-net/ru/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/ru/aspose.slides/baseportionformat/text_cap_type/) | Возвращает или задает тип капитализации текста. Наследование не применяется.<br/>            Чтение/запись [`TextCapType`](/slides/python-net/ru/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/ru/aspose.slides/baseportionformat/strikethrough_type/) | Возвращает или задает тип зачеркивания текста. Наследование не применяется.<br/>            Чтение/запись [`TextStrikethroughType`](/slides/python-net/ru/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/ru/aspose.slides/baseportionformat/is_hard_underline_line/) | Определяет, имеет ли стиль подчеркивания собственные свойства LineFormat или наследует их из свойств LineFormat текста.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/ru/aspose.slides/baseportionformat/is_hard_underline_fill/) | Определяет, имеет ли стиль подчеркивания собственные свойства FillFormat или наследует их из свойств FillFormat текста.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/ru/aspose.slides/baseportionformat/font_height/) | Возвращает или задает высоту шрифта в фрагменте.<br/>            **float.NaN**  означает, что высота не определена и должна наследоваться от Master.<br/>            Чтение/запись **float**. |
| [`latin_font`](/slides/python-net/ru/aspose.slides/baseportionformat/latin_font/) | Возвращает или задает информацию о латинском шрифте.<br/>            Null означает, что шрифт не определен и должен наследоваться от Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/ru/aspose.slides/baseportionformat/east_asian_font/) | Возвращает или задает информацию о шрифте восточноазиатского текста.<br/>            Null означает, что шрифт не определен и должен наследоваться от Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/ru/aspose.slides/baseportionformat/complex_script_font/) | Возвращает или задает информацию о шрифте сложного скрипта.<br/>            Null означает, что шрифт не определен и должен наследоваться от Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/ru/aspose.slides/baseportionformat/symbol_font/) | Возвращает или задает информацию о символическом шрифте.<br/>            Null означает, что шрифт не определен и должен наследоваться от Master.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/ru/aspose.slides/baseportionformat/escapement/) | Возвращает или задает текст верхнего или нижнего индекса.<br/>            Значение от -100% (нижний индекс) до 100% (верхний индекс).<br/>            **float.NaN**  означает, что значение не определено и должно наследоваться от Master.<br/>            Чтение/запись **float**. |
| [`kerning_minimal_size`](/slides/python-net/ru/aspose.slides/baseportionformat/kerning_minimal_size/) | Возвращает или задает минимальный размер шрифта, при котором включается кернинг.<br/>            **float.NaN**  означает, что значение не определено и должно наследоваться от Master.<br/>            Чтение/запись **float**. |
| [`language_id`](/slides/python-net/ru/aspose.slides/baseportionformat/language_id/) | Возвращает или задает Id языка проверки. Используется для проверки орфографии и грамматики.<br/>            Чтение/запись **str**. |
| [`alternative_language_id`](/slides/python-net/ru/aspose.slides/baseportionformat/alternative_language_id/) | Возвращает или задает Id альтернативного языка.<br/>            Чтение/запись **str**. |
| [`spacing`](/slides/python-net/ru/aspose.slides/baseportionformat/spacing/) | Возвращает или задает прирост межсимвольного интервала.<br/>            **float.NaN**  означает, что значение не определено и должно наследоваться от Master.<br/>            Чтение/запись **float**. |
| [`spell_check`](/slides/python-net/ru/aspose.slides/baseportionformat/spell_check/) | Получает или задает значение, указывающее, включена ли проверка орфографии для текстового фрагмента.<br/>            Когда это свойство установлено в false, проверка правописания для текстовых элементов подавляется.<br/>            Когда установлено в true, проверка орфографии разрешена.<br/>            Значение по умолчанию — `false`. |
| [`slide`](/slides/python-net/ru/aspose.slides/baseportionformat/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/baseportionformat/presentation/) |  |

### Смотрите также
* класс [`BasePortionFormat`](/slides/python-net/ru/aspose.slides/baseportionformat)
* класс [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)