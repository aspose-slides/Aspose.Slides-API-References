---
title: Hyperlink class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/hyperlink/
---
## Hyperlink класс

Represents a hyperlink.

**Inheritance:**[`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)

The Hyperlink type exposes the following members:

## Конструкторы

| Constructor | Description |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/ru/aspose.slides/hyperlink/__init__/#str) | Создает экземпляр гиперссылки. |
| [`__init__(self, slide)`](/slides/python-net/ru/aspose.slides/hyperlink/__init__/#islide) | Создает экземпляр гиперссылки, который указывает на конкретный слайд.<br/>            Примечание: созданную гиперссылку следует назначить объекту из той же презентации, иначе ссылка будет сохранена как NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/ru/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Создает экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства. |

## Свойства

| Property | Description |
| :- | :- |
| [`no_action`](/slides/python-net/ru/aspose.slides/hyperlink/no_action/) | Возвращает специальную гиперссылку «ничего не делать».<br/>            Только для чтения [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/ru/aspose.slides/hyperlink/media/) | Возвращает специальную гиперссылку «воспроизвести медиафайл». Используется в AudioFrame и VideoFrame.<br/>            Только для чтения [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/ru/aspose.slides/hyperlink/next_slide/) | Возвращает гиперссылку на следующий слайд.<br/>            Только для чтения [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/ru/aspose.slides/hyperlink/previous_slide/) | Возвращает гиперссылку на предыдущий слайд.<br/>            Только для чтения [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/ru/aspose.slides/hyperlink/first_slide/) | Возвращает гиперссылку на первый слайд презентации.<br/>            Только для чтения [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/ru/aspose.slides/hyperlink/last_slide/) | Возвращает гиперссылку на последний слайд презентации.<br/>            Только для чтения [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/ru/aspose.slides/hyperlink/last_vieved_slide/) | Возвращает гиперссылку на последний просмотренный слайд.<br/>            Только для чтения [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/ru/aspose.slides/hyperlink/end_show/) | Возвращает гиперссылку, завершающую показ.<br/>            Только для чтения [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/ru/aspose.slides/hyperlink/action_type/) | Возвращает тип действия Hyperlink.<br/>            Только для чтения [`HyperlinkActionType`](/slides/python-net/ru/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/ru/aspose.slides/hyperlink/external_url/) | Указывает внешний URL.<br/>            Только для чтения **str**. |
| [`target_slide`](/slides/python-net/ru/aspose.slides/hyperlink/target_slide/) | Если Hyperlink указывает на конкретный слайд, возвращает этот слайд.<br/>            Только для чтения [`ISlide`](/slides/python-net/ru/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/ru/aspose.slides/hyperlink/external_url_original/) | Представляет гиперссылку, установленную для этой части без учёта фактического содержимого части.<br/>            <br/>            PowerPoint ведёт себя особым образом для ссылок и их соответствующего текста в части. Он позволяет создавать текст гиперссылки в виде действительного URL, отличного от реального адреса ссылки. В этом случае, когда вы просматриваете ссылку в окне редактирования, она будет изменена, чтобы соответствовать текстовой части. Это свойство представляет оригинальное значение гиперссылки. |
| [`target_frame`](/slides/python-net/ru/aspose.slides/hyperlink/target_frame/) | Возвращает кадр внутри родительского HTML-фреймсета для цели<br/>            родительской гиперссылки, если он существует.<br/>            Чтение/запись **str**. |
| [`tooltip`](/slides/python-net/ru/aspose.slides/hyperlink/tooltip/) | Возвращает строку, которая может отображаться в пользовательском интерфейсе<br/>            как связанная с родительской гиперссылкой.<br/>            Чтение/запись **str**. |
| [`history`](/slides/python-net/ru/aspose.slides/hyperlink/history/) | Определяет, будет ли цель родительской гиперссылки добавлена<br/>            в список просмотренных гиперссылок при её вызове.<br/>            Чтение/запись **bool**. |
| [`highlight_click`](/slides/python-net/ru/aspose.slides/hyperlink/highlight_click/) | Определяет, должна ли гиперссылка подсвечиваться при клике.<br/>            Чтение/запись **bool**. |
| [`stop_sound_on_click`](/slides/python-net/ru/aspose.slides/hyperlink/stop_sound_on_click/) | Определяет, должно ли звучание прекращаться при клике по гиперссылке.<br/>            Чтение/запись **bool**. |
| [`sound`](/slides/python-net/ru/aspose.slides/hyperlink/sound/) | Представляет воспроизводимый звук гиперссылки.<br/>            Чтение/запись [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/ru/aspose.slides/hyperlink/color_source/) | Представляет источник цвета гиперссылки — стили или формат части.<br/>            Чтение/запись [`HyperlinkColorSource`](/slides/python-net/ru/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/ru/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/hyperlink/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/ru/aspose.slides/hyperlink/equals/#ihyperlink) | Определяет, равны ли два экземпляра Hyperlink. |

### Смотрите также
* класс [`Hyperlink`](/slides/python-net/ru/aspose.slides/hyperlink)
* класс [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)